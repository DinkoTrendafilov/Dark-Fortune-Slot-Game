# 🌙 DARK FORTUNE

> **40 Lines · Spin Counter Fund · Wheel Bonus · Pick-Em Bonus · RTP 96%**

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
| **Paylines** | 40 (Low Correlation) |
| **Symbols** | 30 Unique |
| **RTP** | ~96% |
| **Bet Range** | 1 – 2,000 Credits |
| **Bonus 1** | Pick-Em (4-match & 5-match) |
| **Bonus 2** | Wheel Bonus (Spin Counter Fund) |

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
| **Trigger** | Every 100 spins (fund accumulates) |
| **Attempts** | 5 |
| **Win Rate** | ~63.21% |
| **Win Multiplier** | Fund × 1 |

**How it works:**
- Every spin adds to the spin counter
- At 100 spins, Wheel Bonus triggers automatically
- Win the Wheel → claim the accumulated fund
- Lose the Wheel → fund carries over to next cycle

---

## 🚀 Monte Carlo Simulation (10,000,000 Spins)

### Simulation Results

| Metric | Value |
|--------|-------|
| Total Spins | 10,000,000 |
| Total Bet | 400,000,000 |
| Total Won | 384,524,628 |
| **RTP** | **96.13%** |
| Zero-Win Spins | 1.05% |
| Max Single Win | 34,362 credits |

### Volatility Metrics

| Metric | Value |
|--------|-------|
| Standard Deviation (σ) | 100.74 |
| Arithmetic Mean (μ) | 38.45 |
| Volatility Index (σ/μ) | 261.98% |

### Win Distribution Percentiles

| Percentile | Value |
|------------|-------|
| 1st | 0.00× |
| 5th | 3.00× |
| 10th | 4.00× |
| 25th | 8.00× |
| 50th | 12.00× |
| 75th | 22.00× |
| 90th | 100.00× |
| 95th | 209.10× |
| 99th | 283.00× |

---

## 💀 Bankroll Survival Analysis

**Starting Balance**: 5,000 Credits  
**Bet Per Spin**: 40 Credits  
**Sessions**: 1,000

| Spins | Survival Rate | Bust Rate | Avg Balance |
|-------|---------------|-----------|-------------|
| 500 | 37.80% | 62.20% | 711 |
| 1,000 | 1.40% | 98.60% | 64 |
| 2,500 | 0.10% | 99.90% | 32 |
| 5,000 | 0.00% | 100.00% | 25 |
| 10,000 | 0.00% | 100.00% | 25 |
| 25,000 | 0.00% | 100.00% | 24 |

---

## 📊 Bonus Statistics (10M Spins)

### 4-Match Bonus (52,735 triggers)

| Group | Count | Percentage | Expected |
|-------|-------|------------|----------|
| G1 | 37,746 | 71.58% | 71.54% |
| G2 | 12,897 | 24.46% | 24.62% |
| G3 | 2,092 | 3.97% | 3.85% |

### 5-Match Bonus (232 triggers)

| Group | Count | Percentage | Expected |
|-------|-------|------------|----------|
| G1 | 167 | 71.98% | 71.54% |
| G2 | 54 | 23.28% | 24.62% |
| G3 | 11 | 4.74% | 3.85% |

### Pick-Em Correct Distribution (all bonuses)

| Correct | Count | % of Bonuses | Theoretical |
|---------|-------|--------------|-------------|
| 0 | 2,107 | 3.98% | 3.85% |
| 1 | 13,018 | 24.58% | 24.62% |
| 2 | 22,788 | 43.02% | 43.08% |
| 3 | 12,951 | 24.45% | 24.62% |
| 4 | 2,103 | 3.97% | 3.85% |

---

## 🎡 Wheel Bonus Statistics

| Metric | Value |
|--------|-------|
| **Trigger** | Every 100 spins |
| **Fund Accumulation** | 0.3× per 1-match |

---

## 📈 5-Match Validation

| Metric | Value |
|--------|-------|
| **Theoretical (ANY line)** | 1 in 20,250 |
| **Actual (Monte Carlo)** | 1 in 19,724 |
| **Ratio (Theor/Actual)** | 1.0267× ✅ |
| **95% Credible Interval** | [18,079 – 21,516] |
| **Theoretical within CI?** | ✅ **YES** |

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
├── index.html              # Playable HTML5 game (40 lines)
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

1. **RTP**: 96.13% (Mathematically verified within 0.13% of target) ✅
2. **Volatility**: 261.98% — low volatility, consistent wins
3. **Hit Rate**: 98.95% — almost every spin produces a win 🎯
4. **Pick-Em Distribution**: Matches theoretical hypergeometric distribution ✅
5. **5-Match Validation**: Within 95% Credible Interval ✅
6. **Wheel Bonus**: Every 100 spins → predictable and engaging

---

## 📝 License

MIT License — feel free to use for learning and portfolio purposes.

---

## 👨‍💻 Author

**Dinko Trendafilov** — [GitHub](https://github.com/DinkoTrendafilov)

---

**⭐ If you like this project, give it a star!**
