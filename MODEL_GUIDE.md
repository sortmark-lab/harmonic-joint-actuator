# 谐波关节执行器原理与模型说明 (Harmonic Drive Principles & Model Architecture)

> **归属实验室**: SORTMARK Open-Source Lab (`sortmark-opensource-lab`)  
> **所属项目**: `harmonic-joint-actuator`  
> **官方主页**: [https://sortmark.com](https://sortmark.com) | **商务咨询**: `contact@sortmark.com`

---

## 📌 1. 核心设计原则：纯 HTML 仿真，零外部 3D 模型依赖

本项目重点解析**同轴中空无刷电机 + 谐波减速机传动原理**，**不提供、亦不分发外部 3D CAD/STEP 模型**：

1. **商业资产合规红线**:
   - 谐波减速机柔轮双波渐开线齿形、波发生器椭圆凸轮精密公差是极高商业价值的制造 IP，严禁在公共开源中全量外泄。
2. **纯 HTML 原理仿真 (Zero-Dependency Concentric Simulation)**:
   - 定子绕组、中空转子轴、柔轮弹性杯体及刚轮固定环全部由代码在浏览器内通过原生网格参数动态构建。
   - 轴向爆炸分解（Exploded View）与柔轮波变直接通过前端交互滑块实时响应，完全不需要加载庞大的外部动画模型。
3. **商业定制渠道**:
   - 真实高扭矩中空关节模组、一体化伺服驱动板、定制减速比（50:1、80:1、100:1）采购请联系 `contact@sortmark.com`。

---

## 🏭 2. AI 模型生产流水线：`model-builder` 与 `model-factory`

对于精密执行器的选型问答、力矩曲线推导等模型需求，由工作区统一车间处理：

1. **微调与量化车间**:
   - 路径：`sortmark/sortmark-model-builder`
   - 使用 QLoRA 对机电工程、减速机参数问答语料进行微调，使用 llama.cpp 导出端侧 GGUF 模型。
2. **Hugging Face 矩阵发布车间**:
   - 路径：`social_matrix/custom-model-factory`
   - 通过 `publish_brand_models.sh` 脚本统一发布至 Hugging Face 官方组织 `sortmark/`，自动带入官网权威外链。
