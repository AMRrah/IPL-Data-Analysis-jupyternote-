# IPL-Data-Analysis-jupyternote-

 **IPL Data Analysis 2008-2024**  [IPL Analysis](https://github.com/AMRrah/IPL-Data-Analysis-jupyternote-/blob/main/IPLanalysis01.ipynb) 
 # Overview 
 This project is a Ipl data analyzing of the Indian Premier League (IPL) 2008-2024 season. It provides actionable insights into team performance, player statistics like total matches, balls faced by the players, total runs and total of player dismissed from the matches and more that will be displayed in the form of tables, list, bar chart and pie chart with the help of advanced data visualization techniques to present clear and meaningful results.
<hr>

 # Dataset
 ## This Project uses IPL(2008-2024) Matches Dataset
   This dataset provides summary-level information about each IPL match.-[Dataset](https://github.com/AMRrah/IPL-Data-Analysis-jupyternote-/blob/main/matches.csv)
 ### Columns:   
 1. **match_id**       : Unique identifier for each match.
 2. **season**         : Year of the IPL season.
 3. **date**           : The date the match was played.
 4. **team1**          : Name of the first team.
 5. **team2**          : Name of the second team.
 6. **venue**          : The stadium where the match was played.
 7. **toss_winner**    : Team that won the toss.
 8. **toss_decision**  : Decision made by the toss winner (bat or field).
 9. **winner**         : The team that won the match.
10. **result**         : Type of result (e.g., win by runs, wickets, or a tie).
11. **player_of_match**: Best-performing player in the match.
12. **umpires**        : Names of the umpires officiating the match.  

### Use Cases:
 - Analyzing match outcomes, toss decisions, and team performances.
 - Studying trends in IPL seasons over the years.

## This project uses another dataset IPL(2008-2024) Deliveries Dataset
   This dataset provides ball-by-ball details of each IPL match.-[Dataset](https://github.com/AMRrah/IPL-Data-Analysis-jupyternote-/blob/main/deliveries.csv)

### Columns:
 1. **match_id**        : Identifier linking to the matches dataset.
 2. **inning**          : The inning number (1 or 2).
 3. **batting_team**    : Name of the batting team.
 4. **bowling_team**    : Name of the bowling team.
 5. **over**            : Over number (1 to 20).
 6. **ball**            : Ball number within the over (1 to 6).
 7. **batter**          : Name of the batsman facing the ball.
 8. **non_striker**     : Name of the batsman at the non-striker’s end.
 9. **bowler**          : Name of the bowler delivering the ball.
10. **batsman_runs**    : Runs scored by the batsman off the delivery.
11. **extra_runs**      : Runs due to extras (wide, no-ball, etc.).
12. **total_runs**      : Total runs scored on the ball (batsman + extras).
13. **dismissal_kind**  : Type of dismissal, if any (e.g., bowled, caught).
14. **player_dismissed**: Name of the dismissed player (if any).

### Use Cases:
 - Ball-by-ball performance analysis of players and teams.
 - Studying batsman and bowler stats.
 - Calculating strike rates, economy rates, and player contributions.

<hr>



# System Requirements

### Hardware:
   - **Processor**: Intel(R) Pentium(R) CPU  N3700  @ 1.60GHz   1.60 GHz
   - **RAM**      : 8.00 GB (7.85 GB usable)
   - **Storage**  : 120 GB (118 GB usable)

### Software:
   - **Operating System**:Windows 10 Pro
   - **Tools**           : Jupyter NoteBook.
   - **Additional**      : Microsoft Excel for data preparation.

<hr>

# How to Use

1. Download the **.ipynb file** and **dataset file** from this repository.
2. create a folder and store the **.ipynb file** and **dataset file** in the folder.
3. Open the folder in **vs.code(visual studio code)** to run the data.(can use in the jupyter NoteBook also)

   <hr>

# Conclusion

This project was created as part of a Data Analysis course to Analysis **IPL Dataset** using **Jupyter NoteBook** with the help of **Dataset**.
