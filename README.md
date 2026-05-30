# ⚽ UCL Final 25-26 — Arsenal vs PSG Prediction Model

A data science project that predicts the UEFA Champions League Final 2025-26 between Arsenal and PSG using statistical modelling, Monte Carlo simulation and a 32-metric weighted scoring system.

---

## 🏆 Final Prediction

| | Result |
|---|---|
| **Winner** | 🔴 Arsenal |
| **Scoreline** | Arsenal 1 - 0 PSG |
| **Win Probability** | Arsenal 48.8% · Draw 30.9% · PSG 20.3% |
| **Weighted Score** | Arsenal 38 pts vs PSG 19 pts |

---

## 🛠️ Tech Stack

- **Language:** Python 3.13
- **Environment:** Jupyter Notebook
- **Libraries:** Pandas · NumPy · Matplotlib · XGBoost · Scikit-learn

---

## 📂 Datasets

| Dataset | Rows | Description |
|---|---|---|
| `epl.csv` | 370 | Arsenal EPL 25-26 match stats |
| `league 1.csv` | 305 | PSG Ligue 1 25-26 match stats |
| `champions_league_matches.csv` | 151 | UCL 25-26 match stats |
| `players_data-2025_2026.csv` | 2,779 | Player stats (102 features) |

---

## 📊 Models & Techniques

- **Poisson Distribution** — models random goal scoring per game
- **Dixon-Coles Correction** — adjusts low-score probabilities
- **Monte Carlo Simulation** — 10,000 match simulations
- **Weighted Scoring System** — 32-feature comparison engine
- **Attack/Defense Rating** — normalized vs league average
- **Blended Rating** — UCL 70% + League 30% weighting
- **Elo Rating System** — overall team strength estimation

---

## 📈 Metrics Used (32 Total)

**Attacking** — Goals/game, Shots on target, Goals per shot, UCL goals, 2nd half goals, Finishing quality

**Defensive** — Goals conceded, Clean sheet rate, Defensive strength, GK save %, GK dominance index

**Tactical** — Possession %, Corners, Fouls drawn, Bottle rate, Possession→Goal efficiency

**Discipline** — Yellow cards, Red cards, Fouls committed, Offsides

**Form & Quality** — Win rate, UCL win rate, Squad +/-90, PPM, Elo rating, Player creativity

---

## 📉 Visualizations (9 Charts)

1. Final win probability donut
2. Simulation vs final probability
3. Weighted score total
4. Top 10 most likely scorelines
5. Metric wins pie chart
6. Key stats radar chart
7. UCL stats head-to-head
8. Player quality index
9. All 32 metrics weighted edge chart

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/mfuntasir08/UCL-FINAL-25-26-PREDICTION-MODEL.git

# Open Jupyter Notebook
jupyter notebook ucl_final.ipynb

# Run All cells from top to bottom
```

> Make sure datasets are inside the `Data/` folder before running.

---

## 👤 Author

**Muntasir Islam Fahim**
Built with Python, data and a strong opinion about Liverpool.
