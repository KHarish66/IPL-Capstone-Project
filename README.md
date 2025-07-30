# IPL 2022 Capstone Project

This project analyzes the **Indian Premier League (IPL) 2022** season using match-level data. The goal is to derive meaningful insights into match outcomes, player performances, team dynamics, and strategic trends based on the dataset.

## 📊 Project Objective

- Explore IPL 2022 data to understand key performance indicators.
- Analyze teams’ and players’ performance throughout the season.
- Derive insights on toss decisions, winning patterns, individual player contributions, and venue statistics.
- Provide visualizations to support data-driven conclusions.

---

## 📁 Dataset Overview

The dataset contains details of **74 matches** played in the IPL 2022 season with **20 columns**. Each row corresponds to a unique match.

### Key Columns

- `date`, `venue`, `stage`
- `team1`, `team2`, `toss_winner`, `toss_decision`
- `first_ings_score`, `second_ings_score`
- `match_winner`, `won_by`, `margin`
- `player_of_the_match`, `top_scorer`, `highscore`
- `best_bowling`, `best_bowling_figure`

---

## 🛠️ Technologies Used

- **Python** (pandas, numpy, seaborn, matplotlib)
- **Jupyter Notebook** for data analysis and visualization

---

## 🔍 Key Insights & Analysis

### 1. **Team Performance**
- Gujarat Titans won the most matches (12).
- Chennai Super Kings registered the highest winning margin by runs (91 runs).

### 2. **Toss Analysis**
- Most teams opted to field first after winning the toss.
- 48.65% of matches were won by the team that won the toss.

### 3. **Victory Patterns**
- Analysis of how teams win: by **runs** or **wickets**.

### 4. **Top Performers**
- **Player of the Match Awards**: Kuldeep Yadav won the most (4).
- **Top Scorer**: Jos Buttler with a cumulative 651 runs.
- **Highest Individual Score**: Quinton de Kock (140 runs).
- **Best Bowling Figures**: Jasprit Bumrah with 5 wickets for 10 runs.

### 5. **Venue Analysis**
- Wankhede Stadium, Mumbai hosted the most matches (21).
- Followed by DY Patil (20) and Brabourne (16).

---

## 📌 Custom Questions Answered

- Who won with the highest margin? → *Chennai Super Kings* (91 runs)
- Highest individual score? → *Quinton de Kock* (140)
- Best bowling figures? → *Jasprit Bumrah* (5/10)

---

## 📦 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/IPL-2022-Analysis.git
   cd IPL-2022-Analysis
