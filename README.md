# FoldOrRaise.ai — Preflop GTO Compass 🃏🚀

> **Hyper-Fast Preflop GTO Compass — An agile decision utility for independent players to realize hand equity.**

🌐 **Language**: English | [简体中文](./README_zh.md)

[![GitHub license](https://img.shields.io/github/license/huangq-dev/fold-or-raise?style=flat-square&color=emerald)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/huangq-dev/fold-or-raise?style=flat-square&color=cyan)](https://github.com/huangq-dev/fold-or-raise/stargazers)
[![Live Demo](https://img.shields.io/badge/Live-Demo-00ff88?style=flat-square)](https://huangq-dev.github.io/fold-or-raise/)

---

## 🌐 Live Demo

🚀 **Play Now**: [https://huangq-dev.github.io/fold-or-raise/](https://huangq-dev.github.io/fold-or-raise/)
*(100% Client-Side. No Servers. Zero Tracking. Provably Private. Perfect for PC & Mobile.)*

---

## 🎯 Core Positioning & Use Cases (MVP Stage)

This project follows an **Agile Evolution (MVP)** protocol. The current 1.0 (Proof of Concept) version is strictly scoped to a specific, hard-core Texas Hold'em scenario:

*   **Stack Depth**: Calibrated for **10BB - 25BB** short-stack tournament scenarios where post-flop playability converges into a pure **Push or Fold** mathematical model.
*   **Action Context**: Simulates an **Unopened Pot** where all prior positions have folded, forcing an opening decision on the current player.
*   **Dimensional Multi-linking**: Supports dynamic matrix updates and equity value counting triggered by **3 Stack Levels** (10BB/15BB/25BB) and **3 Key Positions** (UTG, CO, BTN).

---

## 🛠️ Tech Stack & Design Highlights

### Cyberpunk UI Aesthetics (Vue 3 Single File)
*   **Zero-Compile Build**: Powered by Vue 3 (Global Prod) + Tailwind CSS runtime. No Webpack/Vite build overhead; instant page loads.
*   **Matrix Dashboard**: A 13x13 grid rendering custom CSS neon glows, custom SVG background grids, and `JetBrains Mono` fonts.
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
