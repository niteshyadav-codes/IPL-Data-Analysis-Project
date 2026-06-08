# 🏏 IPL Data Analysis Project

<div align="center">

![IPL Banner](https://img.shields.io/badge/IPL-Data%20Analysis-orange?style=for-the-badge&logo=cricket&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**A comprehensive exploratory data analysis of the Indian Premier League (IPL) using Python and Pandas.**

[View Project →](https://github.com/niteshyadav-codes/IPL-Data-Analysis-Project) &nbsp;•&nbsp; [Connect on LinkedIn →](https://www.linkedin.com/in/nitesh-yadav-27404137a/)

</div>

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Datasets Used](#-datasets-used)
- [Key Analyses Performed](#-key-analyses-performed)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [How to Run](#-how-to-run)
- [Insights & Findings](#-insights--findings)
- [Author](#-author)

---

## 📖 About the Project

The Indian Premier League (IPL) is one of the biggest cricket tournaments in the world, generating a massive amount of match and ball-by-ball data. This project dives deep into that data to uncover trends, patterns, and interesting facts about IPL seasons using **Python's Pandas library**.

Whether it's the best batsmen, deadliest bowlers, powerplay statistics, or toss impact on match outcomes — this project answers it all through data!

---

## 📂 Datasets Used

This project uses **two CSV datasets**:

### 1. `matches.csv`
Contains match-level information for all IPL seasons.

| Column | Description |
|--------|-------------|
| `id` | Unique match ID |
| `season` | IPL season year |
| `city` | City where match was played |
| `date` | Date of the match |
| `team1` | First team |
| `team2` | Second team |
| `toss_winner` | Team that won the toss |
| `toss_decision` | Bat or field decision |
| `result` | Match result type |
| `winner` | Match winning team |
| `win_by_runs` | Margin of victory (runs) |
| `win_by_wickets` | Margin of victory (wickets) |
| `player_of_match` | Best performer of the match |
| `venue` | Stadium name |
| `umpire1`, `umpire2` | Match umpires |

### 2. `deliveries.csv`
Contains ball-by-ball data for every delivery bowled across all IPL seasons.

| Column | Description |
|--------|-------------|
| `match_id` | Match reference ID |
| `inning` | Inning number |
| `batting_team` | Team batting |
| `bowling_team` | Team bowling |
| `over` | Over number |
| `ball` | Ball number |
| `batsman` | Batsman on strike |
| `non_striker` | Non-striking batsman |
| `bowler` | Bowler |
| `batsman_runs` | Runs scored by batsman |
| `extra_runs` | Extra runs |
| `total_runs` | Total runs on that delivery |
| `player_dismissed` | Dismissed player (if any) |
| `dismissal_kind` | How player got out |
| `fielder` | Fielder involved (if any) |

---

## 🔍 Key Analyses Performed

### 🏆 Match-Level Analysis (matches.csv)
- **Season-wise match count** — How many matches were played each year?
- **Most successful teams** — Which teams have won the most matches?
- **Toss impact analysis** — Does winning the toss influence match outcome?
- **Toss decision trends** — Do teams prefer batting or fielding after winning the toss?
- **Top venues** — Which stadiums have hosted the most IPL matches?
- **Biggest wins by runs & wickets** — Most dominant victories in IPL history
- **Player of the Match leaders** — Who has won the most Man of the Match awards?
- **City-wise match distribution** — Which cities host the most games?

### 🏏 Batting Analysis (deliveries.csv)
- **Top run-scorers** — All-time IPL run leaders
- **Highest individual scores** — Best innings by a batsman
- **Boundary analysis** — Most fours and sixes hit by batsmen
- **Strike rate analysis** — Best strike rates among regular batsmen
- **Powerplay specialists** — Best performers in the first 6 overs
- **Death overs analysis** — Best finishers (overs 16–20)
- **Dot ball percentage** — Batsmen most tied down by bowlers

### 🎳 Bowling Analysis (deliveries.csv)
- **Top wicket-takers** — Most wickets in IPL history
- **Best economy rates** — Most economical bowlers
- **Most dot balls bowled** — Best pressure-building bowlers
- **Extras analysis** — Teams and bowlers conceding most extras
- **Dismissal types** — Most common ways batsmen get out (caught, bowled, LBW, etc.)
- **Powerplay vs death bowling** — Who performs best in each phase?

### 📊 Team Performance Analysis
- **Season-wise team win analysis** — Track team performance over seasons
- **Head-to-head comparisons** — Win record between specific team pairs
- **Home vs Away performance** — Do teams perform better at home?
- **Run rate analysis** — Average run rates across teams and phases

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.x** | Core programming language |
| **Pandas** | Data loading, manipulation & analysis |
| **Jupyter Notebook** | Interactive analysis environment |

> 📌 **Note:** This project uses **only Pandas** for all data analysis — no external visualization or ML libraries.

---

## 📁 Project Structure

```
IPL-Data-Analysis-Project/
│
├── datasets/
│   ├── matches.csv          # Match-level IPL data
│   └── deliveries.csv       # Ball-by-ball IPL data
│
├── IPL_Data_Analysis.ipynb  # Main Jupyter Notebook with all analysis
│
└── README.md                # Project documentation
```

---

## ▶️ How to Run

### Prerequisites

Make sure you have Python and Pandas installed:

```bash
pip install pandas jupyter
```

### Steps

1. **Clone the repository**
```bash
git clone https://github.com/niteshyadav-codes/IPL-Data-Analysis-Project.git
```

2. **Navigate into the project folder**
```bash
cd IPL-Data-Analysis-Project
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook
```

4. **Open the notebook**

Open `IPL_Data_Analysis.ipynb` in your browser and run all cells.

---

## 💡 Insights & Findings

Here are some interesting findings uncovered during the analysis:

- **Mumbai Indians** have been the most successful franchise in IPL history by number of wins.
- **Winning the toss** and choosing to **field first** has become the dominant strategy across recent seasons.
- **Wankhede Stadium, Mumbai** and **Eden Gardens, Kolkata** are among the most frequently used IPL venues.
- The **powerplay (overs 1–6)** and **death overs (16–20)** have the highest average run rates, making specialist players for these phases extremely valuable.
- **Chris Gayle** and **AB de Villiers** consistently appear among the top run-scorers and six-hitters.
- Most dismissals in IPL happen via **caught** — making fielding and catching incredibly important.

---

## 👨‍💻 Author

**Nitesh Yadav**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nitesh-yadav-27404137a/)
[![GitHub](https://img.shields.io/badge/GitHub-niteshyadav--codes-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/niteshyadav-codes/IPL-Data-Analysis-Project)

---

<div align="center">

⭐ **Agar aapko yeh project pasand aaya toh repo ko Star zaroor karein!** ⭐

Made with ❤️ and 🏏 by [niteshyadav-codes](https://github.com/niteshyadav-codes)

</div>
