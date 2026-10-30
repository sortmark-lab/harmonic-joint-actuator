# SORTMARK Harmonic Joint Actuator (3D Precision Mechanism)

<p align="center">
  <a href="#-english">English</a> | <a href="#-中文说明">简体中文</a> | <a href="#-日本語">日本語</a> | <a href="https://sortmark.com">Official Portal 官网</a>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License" /></a>
  <a href="https://threejs.org/"><img src="https://img.shields.io/badge/Render-WebGL%20Three.js-purple.svg" alt="WebGL" /></a>
  <a href="https://sortmark.com"><img src="https://img.shields.io/badge/Crafted%20by-SORTMARK-white.svg" alt="Brand" /></a>
</p>

---

## 🌐 English

An interactive, high-fidelity **3D Concentric Harmonic Drive Joint Actuator** simulation laboratory. Features cutaway cross-sections, axial exploded assemblies, and dry/wet physical isolation principles. Runs natively in-browser with local system fonts and zero external network bottlenecks.

Crafted by the **[SORTMARK Lab Team](https://sortmark.com)**.

### 🌟 Key Features
* **3-Block Modular Decoupling**:
  * Concentric frameless torque motor stator and rotor.
  * Sealed swappable reduction cartridge (1:50 Harmonic / 1:7 Planetary / 1:1 Direct Drive).
  * Back-end integrated FOC controller and absolute magnetic encoder chamber.
* **Cutaway & Axial Explosion Modes**:
  * Real-time 3D interactive slider inspecting internal wave generator, flexspline, circular spline, and cross-roller bearing.
  * Dry/wet boundary isolation (zero grease leakage design with double-lip fluororubber rotary seals).
* **Local System Fonts & Native Performance**:
  * Instant rendering without external font server dependencies, fully compatible with air-gapped engineering workstations.

### 🚀 Quick Start
```bash
git clone https://github.com/sortmark-lab/harmonic-joint-actuator.git
cd harmonic-joint-actuator
npx serve -l 3000 .
```

---

## 🇨🇳 中文说明

高拟真交互式 **3D 同轴一体化谐波关节执行器** 仿真实验室。支持内部剖面透视、轴向爆炸图分解与动静干湿物理隔离原理解析。纯浏览器端独立运行，零外部网络依赖。

由 **[SORTMARK Lab Team](https://sortmark.com)** 研发打造。

### 🌟 核心特性
* **3 段式模块化解耦架构**:
  * 前端同轴无框力矩电机定转子总成。
  * 中置可换式密封减速盒 (1:50 谐波 / 1:7 行星 / 1:1 直驱)。
  * 后端集成 FOC 矢量驱动控制板与双路绝对值高分辨率磁编码器腔室。
* **剖面透视与轴向爆炸分解模式**:
  * 实时 3D 滑块自由观察椭圆波发生器、柔轮、刚轮及交叉滚子轴承的啮合传动细节。
  * 干湿腔物理隔离边界展示（双唇氟橡胶旋转油封，有效防护润滑脂外溢与电机腔污染）。
* **离线就绪与系统原生字体栈**:
  * 无外部字体加载等待，适配工业自动化现场隔离控制终端。

### 🚀 快速启动
```bash
git clone https://github.com/sortmark-lab/harmonic-joint-actuator.git
cd harmonic-joint-actuator
npx serve -l 3000 .
```

---

## 🇯🇵 日本語

高精度・対話型 **3D 同軸ハーモニックドライブ関節アクチュエータ** シミュレーションラボ。内部断面カットモデル、軸方向分解ビュー、ドライ/ウェット物理隔離構造をブラウザ上で直感的に検証できます。

開発: **[SORTMARK Lab Team](https://sortmark.com)**

### 🌟 主な機能
* **3ブロックモジュラー分離アーキテクチャ**:
  * 同軸フレームレストルクモータ（ステータ・ロータ）。
  * 密閉型交換可能減速カートリッジ（1:50 波動歯車 / 1:7 遊星減速 / 1:1 ダイレクトドライブ）。
  * 後部統合FOCベクトル制御基板および絶対値磁気エンコーダチャンバー。
* **断面カット＆軸方向分解表示モード**:
  * ウェーブジェネレータ（楕円カム）、フレックスプライン（弾性歯車）、サーキュラスプライン（内歯車）、クロスローラーベアリングの噛み合いを3Dで詳細に確認。
  * ドライ／ウェット物理境界隔離設計（二重リップフッ素ゴムオイルシールによりグリース漏れやモータ汚染のリスクを効果的に抑制）。
* **オフライン対応＆ローカルシステムフォント設計**:
  * 外部フォントCDNへのアクセス遅延なしで、クローズドな産業用制御ワークステーションでも即座に描画。

### 🚀 クイックスタート
```bash
git clone https://github.com/sortmark-lab/harmonic-joint-actuator.git
cd harmonic-joint-actuator
npx serve -l 3000 .
```

---

---

## 🔬 Project Status, Evaluation Disclaimer & Feedback / 项目状态、免责声明与反馈

### 🌐 English
> ⚠️ **Evaluation Prototype Notice (Not Intended for Critical or Production Control)**:  
> This open-source repository is an experimental educational and simulation preview under active development. It is provided strictly **"AS IS"** for educational inspection, kinematics/mechanics study, and technical evaluation. It is **not certified for physical safety-critical machinery, high-voltage industrial automation, or direct production deployment**. We make no commercial promises or operational warranties. We warmly welcome community feedback, pull requests, and suggestions to help us refine and improve!  
> 📬 *Community Contact & Feedback*: [`contact@sortmark.com`](mailto:contact@sortmark.com)

### 🇨🇳 简体中文
> ⚠️ **评估原型免责声明（仅用于技术验证与教育交流，不建议直接用于生产工控）**:  
> 本开源项目属于处于持续迭代完善中的实验性技术演示与评估原型，按“现状（AS IS）”提供。**仅供机构原理教学、算法仿真验证与离线学习参考，未经工业安全与关键任务控制认证，不建议也不承诺直接应用于物理实体机电设备或工业生产控制**。本团队不作任何商业承诺或可用性担保。热忱欢迎广大开发者、机器人与语言学爱好者提出宝贵的改进建议与 Issue 反馈！  
> 📬 *交流与反馈渠道*: [`contact@sortmark.com`](mailto:contact@sortmark.com)

### 🇯🇵 日本語
> ⚠️ **評価用プロトタイプに関する免責事項（教育・研究評価用・重要制御への投入非推奨）**:  
> 本オープンソースプロジェクトは、現在も継続的な改良を行っている実験的な教育・シミュレーション用プレビューです。機構原理の学習、アルゴリズムの動作検証、概念実証を目的として現状有姿（AS IS）で公開されており、**物理的な実機機械の保安制御や産業生産現場への直接投入は推奨しておらず、一切の商用保証を行いません**。機能向上や品質改善に向けたコミュニティからのご意見・改善提案・Issue報告を心より歓迎いたします！  
> 📬 *フィードバック窓口*: [`contact@sortmark.com`](mailto:contact@sortmark.com)

## 📄 License
Released under the [MIT License](LICENSE).
