# FoldOrRaise.ai — 翻牌前 GTO 极限算力罗盘 🃏🚀

> **帮助独立玩家变现手牌价值的翻牌前敏捷决策工具**

🌐 **语言切换**: [English](./README.md) | 简体中文

[![GitHub license](https://img.shields.io/github/license/huangq-dev/fold-or-raise?style=flat-square&color=emerald)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/huangq-dev/fold-or-raise?style=flat-square&color=cyan)](https://github.com/huangq-dev/fold-or-raise/stargazers)
[![Live Demo](https://img.shields.io/badge/Live-Demo-00ff88?style=flat-square)](https://huangq-dev.github.io/fold-or-raise/)

---

## 🌐 在线体验

🚀 **点击即玩**：[https://huangq-dev.github.io/fold-or-raise/](https://huangq-dev.github.io/fold-or-raise/)
*(100% 纯前端运行，无服务器，物理级隐私安全，完美适配 PC 与手机端)*

---

## 🎯 项目核心定位与适用场景 (MVP 阶段)

本项目前期采用 **敏捷进化 (Agile Evolution)** 模式开发。当前 1.0 (Proof of Concept) 版本严格卡死在德州扑克实战中最典型的**极简硬核场景**：

*   **筹码深度 (Stack Depth)**：限定在 **10BB - 25BB** 的短筹码 (Short Stack) 锦标赛中后期场景。此时无翻牌后复杂博弈空间，决策模型收敛为纯粹的 **Push or Fold (全下或弃牌)**。
*   **局势状态 (Action)**：默认模拟前面位置玩家全部弃牌 (**Unopened Pot**)，由当前玩家面临开局决策。
*   **维度联动**：支持 **3种筹码深度** (10BB/15BB/25BB) 与 **3个核心位置** (UTG前位、CO中位、BTN后位) 的实时策略矩阵与胜率动效联动。

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

- [x] **Phase 1: 概念验证 (POC)** — 跑通 13x13 矩阵渲染、双语切换、筹码与位置控制栏、以及 Mock 动态权重策略切换。（当前阶段）
- [ ] **Phase 2: Java 算力工厂接入** — 编写 Java 多线程离线模拟脚本，通过百亿次蒙特卡洛 (Monte Carlo) 模拟生成高维策略矩阵 JSON 秘籍。
- [ ] **Phase 3: 实时动态算力池** — 引入 Java WebFlux 异步架构，支持动态输入场上玩家人数与任意两张手牌的实时胜率流式响应。

---

## 🛡️ 法律免责声明

本项目仅为一个**纯线下的 poker 数学训练与策略演练工具**。系统内部不具备任何多玩家联机对局功能，亦不具备任何法定货币或虚拟货币的博弈结算/筹码下注功能。100% 合法合规，仅供技术交流与数学理论研究使用。

---

## 👨‍💻 开发者

*   **Quentin** (GitHub: [@huangq-dev](https://github.com/huangq-dev))
*   如果你觉得这个极限算力罗盘帮你保住了筹码，欢迎点个 ⭐ **Star** 支持一下！
