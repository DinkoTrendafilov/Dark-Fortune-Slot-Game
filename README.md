# 🌙 DARK FORTUNE

> **4 Lines · Fund System · Wheel Bonus · Pick-Em Bonus · RTP 96%**

[![Live Demo](https://img.shields.io/badge/🎰-Play_Now-brightgreen?style=for-the-badge&logo=githubpages)](https://dinkotrendafilov.github.io/Dark-Fortune-Slot-Game/)
[![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)](https://jupyter.org/)

---

## 🎰 Play the Game

**[👉 Click here to play Dark Fortune](https://dinkotrendafilov.github.io/Dark-Fortune-Slot-Game/)** — fully working slot machine in your browser.

---

## 🎯 Game Overview

| Feature | Description |
|---------|-------------|
| **Reels** | 5 × 4 |
| **Paylines** | 4 (Zero Correlation) |
| **Symbols** | 30 Unique |
| **RTP** | ~96% |
| **Bet Range** | 1 – 1,200 Credits |
| **Bonus 1** | Pick-Em (4-match & 5-match) |
| **Bonus 2** | Wheel Bonus (Fund System) |

---

## 📊 RTP Breakdown

### Combinatorial Analysis (30⁵ = 24,300,000 combinations)

| Match | Probability | Payout | RTP |
|-------|-------------|--------|-----|
| 1 | 70.37% | 0.3× → Fund | 21.11% |
| 2 | 28.57% | 1× | 28.57% |
| 3 | 1.04% | 38× | 39.45% |
| 4 | 0.018% | Pick-Em | 6.26% |
| 5 | 0.0001% | Pick-Em | 0.62% |
| **TOTAL** | **100%** | | **96.02%** |

---

## 🎯 Pick-Em Bonus

### Hypergeometric Distribution (N=16, K=8, n=4)

| Group | Correct | Probability | 4-Match | 5-Match |
|-------|---------|-------------|---------|---------|
| G1 | 0–2 | 71.54% | **220×** | **3,145×** |
| G2 | 3 | 24.62% | **498×** | **7,109×** |
| G3 | 4 | 3.85% | **1,820×** | **26,000×** |

### Expected Value

- **4-Match**: 350× ✅
- **5-Match**: 5,000× ✅

---

## 🎡 Wheel Bonus

| Metric | Value |
|--------|-------|
| Trigger | Fund ≥ 200 Credits |
| Attempts | 5 |
| Win Rate | ~63.21% |
| Win Multiplier | Fund × 1 |

---

## 🚀 Monte Carlo Simulation (10,000,000 Spins)

### Simulation Results

| Metric | Value |
|--------|-------|
| Total Spins | 10,000,000 |
| Total Bet | 40,000,000 |
| Total Won | 38,419,693 |
| **RTP** | **96.05%** |
| Zero-Win Spins | 24.38% |
| Max Single Win | 26,000× |

### Volatility Metrics

| Metric | Value |
|--------|-------|
| Standard Deviation (σ) | 25.67 |
| Arithmetic Mean (μ) | 3.84 |
| Volatility Index (σ/μ) | 668% |

### Win Distribution Percentiles

| Percentile | Value |
|------------|-------|
| 1st | 0.00× |
| 5th | 0.00× |
| 10th | 0.00× |
| 25th | 1.00× |
| 50th | 1.00× |
| 75th | 2.00× |
| 90th | 3.00× |
| 95th | 4.00× |
| 99th | 40.00× |

---

## 💀 Bankroll Survival Analysis

**Starting Balance**: 1,000 Credits  
**Bet Per Spin**: 4 Credits  
**Sessions**: 1,000

| Spins | Survival Rate | Bust Rate | Avg Balance |
|-------|---------------|-----------|-------------|
| 500 | 98.60% | 1.40% | 482 |
| 1,000 | 31.60% | 68.40% | 136 |
| 2,500 | 2.60% | 97.40% | 22 |
| 5,000 | 0.20% | 99.80% | 4 |
| 10,000 | 0.00% | 100.00% | 2 |
| 25,000 | 0.00% | 100.00% | 2 |

---

## 📊 Bonus Statistics (10M Spins)

### 4-Match Bonus

| Group | Count | Percentage | Expected |
|-------|-------|------------|----------|
| G1 | 5,181 | 71.69% | 71.54% |
| G2 | 1,781 | 24.64% | 24.62% |
| G3 | 265 | 3.67% | 3.85% |

### 5-Match Bonus

| Group | Count | Percentage | Expected |
|-------|-------|------------|----------|
| G1 | 17 | 54.84% | 71.54% |
| G2 | 11 | 35.48% | 24.62% |
| G3 | 3 | 9.68% | 3.85% |

### Pick-Em Correct Distribution

| Correct | Count | % of Bonuses | Theoretical |
|---------|-------|--------------|-------------|
| 0 | 301 | 4.15% | 3.85% |
| 1 | 1,806 | 24.88% | 24.62% |
| 2 | 3,091 | 42.59% | 43.08% |
| 3 | 1,792 | 24.69% | 24.62% |
| 4 | 268 | 3.69% | 3.85% |

---

## 🎡 Wheel Bonus Statistics

| Metric | Value |
|--------|-------|
| Total Triggers | 62,911 |
| Wins | 42,051 (66.84%) |
| Losses | 20,860 (33.16%) |
| Avg Fund at Trigger | 200.8 |
| Max Fund at Trigger | 211.5 |
| Avg Fund on Win | 200.8 |
| Max Fund on Win | 211.5 |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Game Engine | Vanilla JavaScript |
| UI | HTML5 + CSS3 |
| Math Analysis | Python + NumPy + SciPy |
| Visualization | Matplotlib |
| Hosting | GitHub Pages |

---

## 📂 Repository Structure

```
Dark-Fortune-Slot-Game/
├── index.html              # Playable HTML5 game
├── README.md               # This file
├── SDD_Dark_Fortune.ipynb  # Software Design Document (Jupyter)
├── dark_fortune.html       # Alternative game version
├── .gitattributes          # Git settings
└── .gitignore              # Ignored files
```

---

## 🚀 How to Run

### Play the Game
1. Open `index.html` in your browser
2. Select bet and press SPIN
3. Or play online: **[https://dinkotrendafilov.github.io/Dark-Fortune-Slot-Game/](https://dinkotrendafilov.github.io/Dark-Fortune-Slot-Game/)**

### Run the Analysis
```bash
pip install numpy scipy matplotlib
jupyter notebook SDD_Dark_Fortune.ipynb
```

---

## 📊 Key Findings

1. **RTP**: 96.05% (Mathematically verified within 0.05% of target)
2. **Volatility**: Very high (668%) — high risk, high reward
3. **Pick-Em Distribution**: Matches theoretical hypergeometric distribution
4. **Bankroll**: 98.6% survival at 500 spins, drops to 31.6% at 1,000 spins
5. **5-Match Frequency**: 1 in 202,500 (theoretical) vs 1 in 322,581 (actual)

---

## 📝 License

MIT License — feel free to use for learning and portfolio purposes.

---

## 👨‍💻 Author

**Dinko Trendafilov** — [GitHub](https://github.com/DinkoTrendafilov)

---

**⭐ If you like this project, give it a star!**
