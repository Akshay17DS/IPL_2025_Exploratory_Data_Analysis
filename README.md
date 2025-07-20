# IPL 2025 Dataset – Exploratory Data Analysis

## Project Overview:
This project explores match and player-level data from the 2025 season of the Indian Premier League (IPL), one of the world’s most watched cricket tournaments. Using exploratory data analysis (EDA) techniques, we uncover key performance trends, team strategies, and player contributions using ball-by-ball and match-level data.

---

## Dataset Details:

### 🏏 Match-Level Data (`matches.csv`):
- `match_id`: Unique match identifier
- `team1`, `team2`: Participating teams
- `toss_winner`, `toss_decision`
- `match_winner`
- `player_of_the_match`
- `stage`: League, Playoffs, Final
- Scores, wickets, and top individual performance indicators

### 🎯 Delivery-Level Data (`deliveries.csv`):
- `match_no`, `over`, `bowler`, `striker`
- `runs_of_bat`, `extras`, `wicket_type`
- Details of every delivery in the tournament

---

## Objectives:
- Identify top performers in batting and bowling
- Understand team consistency through win percentages
- Evaluate toss decisions and their influence on match outcomes
- Explore stage-wise and economy-based bowling performance
- Visualize patterns in Player of the Match awards and roles

---

## 🔍 EDA

1. 🔝 Top 10 Run Scorers – IPL 2025
To identify standout batting performances, we calculated total runs scored by each player.


Observation:

Sai Sudharsan topped the chart with 759 runs, showing exceptional consistency throughout the season.

Suryakumar Yadav and Kohli also crossed the 650-run mark, indicating strong top-order contributions.

2. 🎯 Top 10 Wicket Takers – IPL 2025
This chart highlights the most successful bowlers based on total wickets taken.


Observation:

Prasidh Krishna led with 25 wickets, followed closely by Noor Ahmad.

Both pacers and spinners feature in the top 10, showing diverse bowling success.

3. 🧠 Toss Impact on Match Result
We analyzed how often teams that won the toss also won the match.


Observation:

Toss winners won the match ~57% of the time, showing a slight strategic advantage.

However, the toss wasn’t a dominant deciding factor.

4. 🏆 Win Percentage by Team
Team-wise win rates were calculated for the 2025 season.


Observation:

PBKS had the highest win percentage at 65%.

RCB and GT also performed strongly, while CSK and RR had lower win rates.

5. 🥇 Player of the Match Awards by Role
We categorized match awards by player roles.


Observation:

Batsmen dominated the awards, reflecting their impact on game outcomes.

Bowlers and all-rounders contributed but were less frequently recognized.

6. 🔥 Stage-wise Team Wins (League, Playoffs, Final)
A breakdown of wins across tournament stages per team.


Observation:

PBKS was dominant in league matches.

RCB was the only team to win the final, while most teams failed to make an impact beyond the league stage.

7. 🧾 Toss Decision vs Win Percentage
We checked how the toss decision (bat or bowl) affected win outcomes.


Observation:

Teams opting to bat first had a significantly higher win rate (~69%) than those who chose to bowl (~54%).

Bat-first strategy proved more effective during IPL 2025.

8. 🎯 Most Economical Bowlers (Min 10 Overs)
We analyzed economy rates to highlight bowlers who conceded the least.


Observation:

Anshul Kamboj was the most economical, conceding under 8 runs/over.

Tight bowling did not always correlate with high wicket counts, but helped contain opponents effectively.

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib, Seaborn for plotting
- Jupyter Notebook / Google Colab
- Git for version control

---

🧠 Final Summary & Insights

This IPL 2025 Exploratory Data Analysis revealed several key patterns and performance trends:

- Sai Sudharsan, Suryakumar Yadav, and Virat Kohli led the batting charts, emphasizing the value of strong top-order contributions.

- Prasidh Krishna and Noor Ahmad dominated the bowling attack, while economical bowlers like Anshul Kamboj and Arshdeep Singh maintained tight control despite fewer wickets.

- PBKS emerged as the most consistent team during the league stage, while RCB stood out for clinching victory in the final.

- Toss decisions played a moderate role, with batting first offering a tactical edge in win probability.

- Player of the Match awards were mostly secured by batsmen, highlighting their match-winning influence.

- The transition from league stage to playoffs saw many teams struggle, suggesting pressure handling is a key differentiator.

This analysis not only spotlighted individual brilliance but also uncovered strategic trends like toss impact and performance consistency across stages — making it valuable for teams, fans, and analysts alike.


## 👤 Author

- **Name:** D Akshaykumar  
- 📧 d.akshaykumar17@gmail.com  
- 🔗 [LinkedIn](https://linkedin.com)  
- 🔗 [GitHub](https://github.com/Akshay17DS)

---