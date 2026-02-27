# Interactive Hack

> A community-driven hub for LLM evaluation, learning, and building.

**Interactive Hack** is an open Interactive Benchmark platform where the community contributes high-quality datasets and puzzle challenges to evaluate the capabilities of today's leading large language models. We host arena competitions, whiteboard sessions, and a weekly newsletter — all aimed at pushing the frontier of AI benchmarking together.

---

## 🌐 Live Site

[https://thuyoung.github.io/interactive-hack](https://thuyoung.github.io/interactive-hack)

---

## 📄 Pages

| Page | Description |
|------|-------------|
| [`index.html`](index.html) | Homepage — Bento grid overview of all platform sections |
| [`puzzles.html`](puzzles.html) | Interactive Puzzles — Community benchmark arena |
| [`leaderboard.html`](leaderboard.html) | Leaderboard — Arena rankings powered by Bradley-Terry model |
| [`whiteboard.html`](whiteboard.html) | LLM Whiteboard Sessions — Deep-dive technical lectures |
| [`newsletter.html`](newsletter.html) | InteractiveAGI Mesh Newsletter — Weekly AI research dispatch |

---

## ✨ Features

### 🧩 Interactive Puzzles
The core of the platform. Community members contribute diverse datasets across reasoning, coding, math, knowledge, and more. Each submission is automatically benchmarked against all supported LLMs, with results published to the public leaderboard.

- Community-contributed dataset submissions
- Multi-category puzzle support (Reasoning, Coding, Math, Knowledge, Language, Multimodal)
- Real-time scoring and leaderboard updates

### 🏆 Leaderboard
Arena-style rankings of the world's leading LLMs, computed using the **Bradley-Terry model** from millions of pairwise community comparisons.

- ELO/Arena Score with 95% confidence intervals
- Trend indicators and win-rate tracking
- Filter by category, organization, and license
- Blind evaluation to eliminate brand bias

### 📋 LLM Whiteboard Sessions
Regular deep-dive technical sessions covering key concepts in modern LLMs — from RLHF and scaling laws to MoE architectures and benchmark design.

- Live sessions with free registration
- Recorded sessions available in the archive

### ✉️ InteractiveAGI Mesh Newsletter
Weekly dispatches covering LLM research highlights, benchmark results, community puzzle spotlights, and arena event announcements.

---

## 🎨 Design

The site is built with plain HTML + CSS — no frameworks, no build tools. Inspired by OpenAI's clean, dark-mode visual language.

- **Font**: Inter (Google Fonts)
- **Color scheme**: Dark (`#050505`) + Green accent (`#10a37f`)
- **Layout**: Bento grid homepage, responsive across all screen sizes
- **Style**: Frosted-glass nav, radial glows, subtle grid backgrounds, animated stat bars

---

## 🚀 Getting Started

Clone the repo and open `index.html` directly in your browser — no server required.

```bash
git clone https://github.com/ThuYoung/interactive-hack.git
cd interactive-hack
open index.html   # macOS
# or: start index.html  (Windows)
# or: xdg-open index.html  (Linux)
```

---

## 🗺️ Roadmap

- [ ] Backend integration for real dataset submissions
- [ ] Live LLM benchmarking pipeline
- [ ] User authentication and contributor profiles
- [ ] Real-time leaderboard updates via API
- [ ] Community forum / discussion threads
- [ ] More arena categories (Multimodal, Agents, Long-context)

---

## 🤝 Contributing

We welcome contributions from the community! Ways to get involved:

1. **Submit a puzzle dataset** — head to the [Puzzles page](puzzles.html) and follow the submission guide
2. **Report issues** — open a GitHub Issue for bugs or design feedback
3. **Suggest features** — open a Discussion with your ideas
4. **Spread the word** — share the platform with your research group or team

---

## 📬 Contact

- **Newsletter**: [InteractiveAGI Mesh](newsletter.html)
- **GitHub**: [@ThuYoung](https://github.com/ThuYoung)

---

<p align="center">
  Built with ❤️ by the Interactive Hack community · © 2026 InteractiveHack
</p>
