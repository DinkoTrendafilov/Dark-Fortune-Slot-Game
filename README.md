# 🌙 DARK FORTUNE

> **40 Lines · Fund & Jackpot System · Wheel Bonus · Pick-Em Bonus · Full Screen Bonus · RTP 96%**

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
| **Bonus 3** | Jackpot System (1/10,000 chance) |
| **Bonus 4** | Full Screen Bonus (10,000,000× per line) |

---

## 📊 RTP Breakdown

### Combinatorial Analysis (30⁵ = 24,300,000 combinations)

| Match | Probability | Payout | RTP |
|-------|-------------|--------|-----|
| 1 | 70.37% | 0.4× (0.3 Fund + 0.1 Jackpot) | 28.15% |
| 2 | 28.57% | 1.3× | 37.14% |
| 3 | 1.04% | 21× | 21.80% |
| 4 | 0.018% | Pick-Em (270–2,236×) | 7.69% |
| 5 | 0.0001% | Pick-Em (6,290–52,000×) | 1.23% |
| **TOTAL** | **100%** | | **96.02%** |

---

## 🎯 Pick-Em Bonus

### Hypergeometric Distribution (N=16, K=8, n=4)

| Group | Correct | Probability | 4-Match | 5-Match |
|-------|---------|-------------|---------|---------|
| G1 | 0–2 | 71.54% | **270×** | **6,290×** |
| G2 | 3 | 24.62% | **611×** | **14,219×** |
| G3 | 4 | 3.85% | **2,236×** | **52,000×** |

### Expected Value

- **4-Match**: 430× ✅
- **5-Match**: 10,000× ✅

---

## 🎡 Wheel Bonus

| Metric | Value |
|--------|-------|
| **Trigger** | Every 100 empty lines (1-matches) |
| **Attempts** | 5 |
| **Win Rate** | ~67.2% (20% per attempt) |
| **Win Multiplier** | Fund × 1 |

**How it works:**
- Every spin adds to the spin counter if a line has 1-match
- At 100 empty lines, Wheel Bonus triggers automatically
- Win the Wheel → claim the accumulated fund
- Lose the Wheel → 4 more attempts (5 total)

---

## 🏆 Jackpot System

| Metric | Value |
|--------|-------|
| **Accumulation** | 0.10× per line from 1-matches |
| **Hit Chance** | 1/10,000 per spin |
| **Payout** | Entire accumulated jackpot |

---

## 🌟 Full Screen Bonus

| Metric | Value |
|--------|-------|
| **Trigger** | All 20 cells show the same symbol |
| **Payout** | 10,000,000× per line |
| **Probability** | Extremely rare (30/30^20) |
| **Simulated Hits** | 0 in 10,000,000 spins |

---

## 🚀 Monte Carlo Simulation (10,000,000 Spins)

### Simulation Results

| Metric | Value |
|--------|-------|
| Total Spins | 10,000,000 |
| Total Bet | 10,000,000 |
| Total Won | 9,599,591 |
| **RTP** | **95.9959%** |
| Zero-Win Spins | 0.84% |
| Max Single Win | 52,000 credits |

### Volatility Metrics

| Metric | Value |
|--------|-------|
| Standard Deviation (σ) | 10.33 |
| Arithmetic Mean (μ) | 0.96 |
| Volatility Index (σ/μ) | 1075.90% |

### Win Distribution Percentiles

| Percentile | Value (× Bet) |
|------------|---------------|
| 1st | 0.03× |
| 5th | 0.10× |
| 10th | 0.16× |
| 25th | 0.26× |
| 50th | 0.46× |
| 75th | 1.08× |
| 90th | 1.97× |
| 95th | 2.65× |
| 99th | 4.41× |

---

## 💀 Bankroll Survival Analysis

**Starting Balance**: 100 Credits  
**Bet Per Spin**: 1 Credit (0.025 per line)  
**Sessions**: 1,000

| Spins | Survival Rate | Bust Rate | Avg Balance |
|-------|---------------|-----------|-------------|
| 100 | 100.00% | 0.00% | 90 |
| 300 | 100.00% | 0.00% | 69 |
| 500 | 83.30% | 16.70% | 45 |
| 1,000 | 23.70% | 76.30% | 21 |
| 2,500 | 3.70% | 96.30% | 8 |
| 5,000 | 0.80% | 99.20% | 3 |
| 25,000 | 0.10% | 99.90% | 1 |

---

## 📊 Bonus Statistics (10M Spins)

### 4-Match Bonus (52,905 spins with at least one 4-match)

**Total 4-Match LINES:** 71,591

| Group | Percentage | Expected |
|-------|------------|----------|
| G1 | ~71.54% | 71.54% |
| G2 | ~24.62% | 24.62% |
| G3 | ~3.85% | 3.85% |

### 5-Match Bonus (467 spins with at least one 5-match)

**Total 5-Match LINES:** 483

| Group | Percentage | Expected |
|-------|------------|----------|
| G1 | ~71.54% | 71.54% |
| G2 | ~24.62% | 24.62% |
| G3 | ~3.85% | 3.85% |

### Comparison with Theory

| Metric | Theoretical | Simulated | Difference |
|--------|-------------|-----------|------------|
| 4-Match Lines | 71,604.9 | 71,591 | -0.02% |
| 5-Match Lines | 493.8 | 483 | -2.19% |

---

## 🎡 Wheel Bonus Statistics

| Metric | Value |
|--------|-------|
| **Total Wins** | 1,649,567 |
| **Win Rate** | ~67.2% |

---

## 🏆 Jackpot Statistics

| Metric | Value |
|--------|-------|
| **Total Jackpots** | 966 |
| **Frequency** | 1 in 10,352 spins |
| **Average Gap** | 10,358 spins |
| **Max Gap** | 69,200 spins |
| **Early (<5,000 spins)** | 37.7% |
| **On time (5k-15k)** | 37.0% |
| **Late (>15,000 spins)** | 25.3% |

---

## 📈 5-Match Validation

| Metric | Value |
|--------|-------|
| **Theoretical (ANY line)** | 1 in 20,250 |
| **Actual (Monte Carlo)** | 1 in 20,704 |
| **Difference** | -2.19% ✅ |
| **Theoretical within 95% CI?** | ✅ **YES** |

---

## 🌟 Full Screen Bonus Analysis

| Metric | Value |
|--------|-------|
| **Theoretical Probability** | 30 / 30^20 |
| **Simulated Hits** | 0 in 10,000,000 spins |
| **Expected Frequency** | Extremely rare |
| **Payout** | 10,000,000× per line |

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


---

## 🚀 How to Run

### Play the Game
1. Open `Dark_Fortune_4_Bonuses.html` in your browser
2. Select bet and press SPIN
3. Or play online: **[https://dinkotrendafilov.github.io/Dark-Fortune-Slot-Game/](https://dinkotrendafilov.github.io/Dark-Fortune-Slot-Game/)**

### Run the Analysis
```bash
pip install numpy scipy matplotlib

