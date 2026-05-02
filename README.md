# 🏏 IPL 2022 — Complete Data Analysis & EDA

> **74 matches. 10 teams. 1 champion.** Every ball, every wicket, every run — analyzed.

---

## 📌 Project Overview

This project is a complete **Exploratory Data Analysis (EDA)** of the **IPL 2022 season** using Python. It uncovers patterns, trends, and insights from every match played in the tournament — from toss decisions to highest individual scores, from venue analysis to stage-wise performance.

Built as a **Data Science Capstone Project** to demonstrate real-world data analysis skills using Python's core data stack.

---

## 📊 Key Insights Found

- 🎯 **Toss Impact** — Toss winners converted to match wins only ~48.57% of the time in group stage — barely above chance
- 🏆 **Gujarat Titans** dominated IPL 2022 with the highest win percentage
- 🏟️ **Eden Gardens, Kolkata** produced the highest average first innings scores
- 🎳 **Fielding first** was the preferred toss decision — teams trusted chasing over defending
- 💥 **Highest individual score** of the season came from Quinton de Kock (**140**)
- 📈 **First innings teams that won** scored on average **~20 more runs** than those who lost

---

## 🔍 Questions Answered (20 EDA Questions)

### 🎲 Toss Analysis
- Did winning the toss help win the match?
- Bat or field — which toss decision won more matches?
- Which team won the most tosses in 2022?

### 🏏 Team Performance
- Which team won the most matches?
- Which team lost the most?
- Win percentage for each team

### 📋 Match Result Analysis
- How many matches were won batting first vs chasing?
- Biggest winning margin by runs (Top 5)
- Biggest winning margin by wickets (Top 5)

### 📈 Innings Score Analysis
- Average, highest & lowest first innings scores
- Which venue produces the highest average first innings score?
- Does a high first innings score guarantee a win?
- Score distribution — first innings vs second innings

### 🥇 Individual Awards
- Who won Player of the Match most times?
- Who was the top scorer most frequently?
- Highest individual score in the tournament
- Who was the best bowler most frequently?

### 🏟️ Stage Analysis
- Match count across Group, Playoff, and Final
- Did toss matter more in knockout games?
- Which stage had higher average first innings scores?

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| pandas | Data manipulation & analysis |
| NumPy | Numerical operations |
| Matplotlib | Base visualizations |
| Seaborn | Statistical charts |
| Jupyter Notebook | Development environment |

---

## 📁 Project Structure

```
IPL-2022-EDA/
│
├── ipl2022_Capstone.ipynb   # Main analysis notebook
├── IPL_2022.csv             # Dataset
└── README.md                # Project documentation
```

---

## 🚀 How to Run Locally

**1. Clone the repo**
```bash
git clone https://github.com/codewithvikas96-ui/IPL-2022-EDA.git
cd IPL-2022-EDA
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**3. Launch notebook**
```bash
jupyter notebook ipl2022_Capstone.ipynb
```

---

## 📂 Dataset

The dataset contains **match-level data** for all 74 IPL 2022 matches with the following columns:

`match_id` · `date` · `venue` · `team1` · `team2` · `stage` · `toss_winner` · `toss_decision` · `first_ings_score` · `first_ings_wkts` · `second_ings_score` · `second_ings_wkts` · `match_winner` · `won_by` · `margin` · `player_of_the_match` · `top_scorer` · `highscore` · `best_bowling` · `best_bowling_figure`

---

## 🗺️ Analysis Roadmap

```
Data Loading & Cleaning
        ↓
Exploratory Data Analysis (20 Questions)
        ↓
Visualizations (Bar, Pie, Histogram, Boxplot)
        ↓
Insights & Interpretation
        ↓
[Next Phase] → Streamlit Interactive Dashboard
```

---

## 🔮 What's Next

- [ ] Interactive dashboard using **Streamlit**
- [ ] Team & player filter dropdowns
- [ ] Live IPL data integration via API
- [ ] Multi-year comparison (2020–2024)

---

## 👤 Author

**Vikas**

💼 [LinkedIn](https://www.linkedin.com/in/vikas-vishwakarma-62959a387/) · 🐙 [GitHub](https://github.com/codewithvikas96-ui)

---

## ⭐ Support

If you found this project useful, **drop a ⭐ on the repo** — it helps a lot!

---

*Built with 🏏 and Python*
