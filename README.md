# FoldOrRaise.ai — Preflop GTO Compass 🃏🚀

> **Hyper-Fast Preflop GTO Compass — An agile decision utility for independent players to realize hand equity.**

🌐 **Language / 语言切换**: [English (Default)](#-foldorraiseai--preflop-gto-compass-) | [中文版本 (#)](#-foldorraiseai--翻牌前-gto-极限算力罗盘-)

[![GitHub license](https://img.shields.io/github/license/huangq-dev/fold-or-raise?style=flat-square&color=emerald)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/huangq-dev/fold-or-raise?style=flat-square&color=cyan)](https://github.com/huangq-dev/fold-or-raise/stargazers)
[![Live Demo](https://img.shields.io/badge/Live-Demo-00ff88?style=flat-square)](https://huangq-dev.github.io/fold-or-raise/)

---

## 🌐 Live Demo

🚀 **Play Now**: [https://huangq-dev.github.io/fold-or-raise/](https://huangq-dev.github.io/fold-or-raise/)[cite: 2]
*(100% Client-Side. No Servers. Zero Tracking. Provably Private. Perfect for PC & Mobile.)*

---

## 🎯 Core Positioning & Use Cases (MVP Stage)

This project follows an **Agile Evolution (MVP)** protocol. The current 1.0 (Proof of Concept) version is strictly scoped to a specific, hard-core Texas Hold'em scenario:

*   **Stack Depth**: Calibrated for **10BB - 25BB** short-stack tournament scenarios where post-flop playability converges into a pure **Push or Fold** mathematical model[cite: 1].
*   **Action Context**: Simulates an **Unopened Pot** where all prior positions have folded, forcing an opening decision on the current player[cite: 1].
*   **Dimensional Multi-linking**: Supports dynamic matrix updates and equity value counting triggered by **3 Stack Levels** (10BB/15BB/25BB) and **3 Key Positions** (UTG, CO, BTN)[cite: 1].

---

## 🛠️ Tech Stack & Design Highlights

### Cyberpunk UI Aesthetics (Vue 3 Single File)
*   **Zero-Compile Build**: Powered by Vue 3 (Global Prod) + Tailwind CSS runtime. No Webpack/Vite build overhead; instant page loads.
*   **Matrix Dashboard**: A 13x13 grid rendering custom CSS neon glows, custom SVG background grids, and `JetBrains Mono`极客 fonts.
*   **Fluid Animations**: Custom cubic-ease dampening functions driving responsive count-up animations for hand equity.
*   **Self-Contained i18n**: Pure JS path-parser enabling seamless, dependency-free toggling between English (EN) and Chinese (ZH).

---

## 🗺️ Engineering Roadmap

We reject over-engineered hype, adhering strictly to **Tool-based Rationalism** and gradual evolution:

- [x] **Phase 1: Proof of Concept (POC)** — Deliver 13x13 grid rendering, dual-language toggling, and interactive multi-variable mock matrices. (Current)
- [ ] **Phase 2: Java Calculation Factory** — Build an offline multi-threaded Java engine to pre-compute hyper-accurate strategy matrices via billions of Monte Carlo simulations.
- [ ] **Phase 3: Real-time Reactive Pipeline** — Implement a Java WebFlux async backend to stream instant equity data based on live player counts and raw card inputs.

---

## 🛡️ Legal Disclaimer

This utility is strictly an **offline mathematical training and strategy validation tool**. It features NO multiplayer functions and NO real-money/crypto wagering capabilities. 100% legal, compliant, and intended solely for scientific and research purposes.

---

## 👨‍💻 Developer / Author

*   **Quentin** (GitHub: [@huangq-dev](https://github.com/huangq-dev))
*   If this compass saved your stack, drop a ⭐ **Star** to support the journey!

---
---

# 🃏🚀 FoldOrRaise.ai — 翻牌前 GTO 极限算力罗盘

> **帮助独立玩家变现手牌价值的翻牌前敏捷决策工具**

🌐 **Language / 语言切换**: [English (顶部)](#foldorraiseai--preflop-gto-compass-) | [中文版本 (当前)](#-foldorraiseai--翻牌前-gto-极限算力罗盘-)

---

## 🌐 在线体验

🚀 **点击即玩**：[https://huangq-dev.github.io/fold-or-raise/](https://huangq-dev.github.io/fold-or-raise/)[cite: 2]
*(100% 纯前端运行，无服务器，物理级隐私安全，完美适配 PC 与手机端)*

---

## 🎯 项目核心定位与适用场景 (MVP 阶段)

本项目前期采用 **敏捷进化 (Agile Evolution)** 模式开发。当前 1.0 (Proof of Concept) 版本严格卡死在德州扑克实战中最典型的**极简硬核场景**：

*   **筹码深度 (Stack Depth)**：限定在 **10BB - 25BB** 的短筹码 (Short Stack) 锦标赛中后期场景。此时无翻牌后复杂博弈空间，决策模型收敛为纯粹的 **Push or Fold (全下或弃牌)**[cite: 1]。
*   **局势状态 (Action)**：默认模拟前面位置玩家全部弃牌 (**Unopened Pot**)，由当前玩家面临开局决策[cite: 1]。
*   **维度联动**：支持 **3种筹码深度** (10BB/15BB/25BB) 与 **3个核心位置** (UTG前位、CO中位、BTN后位) 的实时策略矩阵与胜率动效联动[cite: 1]。

---

## 🛠️ 技术栈与设计亮点

### 前端极客美学 (Vue 3 单文件架构)
*   **零编译依赖**：基于 Vue 3 (Global Prod) + Tailwind CSS 运行时，无 Webpack/Vite 构建负担，单文件秒开。
*   **赛博朋克 UI**：采用霓虹暗黑科技风 (CSS Neon Glows + SVG Grid), 配合 `JetBrains Mono` 极客字体与响应式网格 (13x13 德州手牌矩阵)。
*   **丝滑交互动画**：自研轻量级立方渐入阻尼函数，实现点击手牌时胜率动态跑表滚动。
*   **全内聚国际化**：纯原生 JS 路径解析器，零依赖实现中英双语 (EN/ZH) 动态无缝切换。

---

## 🗺️ 进化路线图 (Roadmap)

我们坚持**工具理性**与**渐进式演进**：

- [x] **Phase 1: 概念验证 (POC)** — 跑通 13x13 矩阵渲染、双语切换、筹码与位置控制栏、以及 Mock 动态权重策略切换。[cite: 1]（当前阶段）
- [ ] **Phase 2: Java 算力工厂接入** — 编写 Java 多线程离线模拟脚本，通过百亿次蒙特卡洛 (Monte Carlo) 模拟生成高维策略矩阵 JSON 秘籍。
- [ ] **Phase 3: 实时动态算力池** — 引入 Java WebFlux 异步架构，支持动态输入场上玩家人数与任意两张手牌的实时胜率流式响应。

---

## 🛡️ 法律免责声明

本项目仅为一个**纯线下的 poker 数学训练与策略演练工具**。系统内部不具备任何多玩家联机对局功能，亦不具备任何法定货币或虚拟货币的博弈结算/筹码下注功能。100% 合法合规，仅供技术交流与数学理论研究使用。

---

## 👨‍💻 开发者

*   **Quentin** (GitHub: [@huangq-dev](https://github.com/huangq-dev))
*   如果你觉得这个极限算力罗盘帮你保住了筹码，欢迎点个 ⭐ **Star** 支持一下！
