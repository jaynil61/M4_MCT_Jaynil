# IPL Exploratory Data Analysis(EDA) Project

## Project Overview
This project involves performing **Exploratory Data Analysis (EDA)** on Indian Premier League (IPL) data using popular Python libraries such as **NumPy**, **Pandas**, **Matplotlib**, and **Seaborn**. The goal is to understand the dataset, clean it, and derive insights by visualizing various aspects of the game, such as runs scored in different phases of an innings, dismissal patterns, team performances, and more.

## Dataset
The project uses two datasets:

1. **deliveries.csv** - Contains ball-by-ball data for each IPL match.
   - Key Columns: \`match_id\`, \`inning\`, \`batting_team\`, \`bowling_team\`, \`over\`, \`ball\`, \`batsman\`, \`non_striker\`, \`bowler\`, \`is_super_over\`, \`wide_runs\`, \`bye_runs\`, \`legbye_runs\`, \`noball_runs\`, \`penalty_runs\`, \`batsman_runs\`, \`extra_runs\`, \`total_runs\`, \`player_dismissed\`, \`dismissal_kind\`, \`fielder\`.
   
2. **matches.csv** - Contains match-level data for IPL.
   - Key Columns: \`id\`, \`season\`, \`city\`, \`date\`, \`team1\`, \`team2\`, \`toss_winner\`, \`toss_decision\`, \`result\`, \`dl_applied\`, \`winner\`, \`win_by_runs\`, \`win_by_wickets\`, \`player_of_match\`, \`venue\`, \`umpire1\`, \`umpire2\`.

## Exploratory Data Analysis

### 1. Data Cleaning
- Check for missing values and handle them (e.g., imputation, dropping rows/columns).
- Explore data types and ensure their correctness.
- Identify and handle any outliers or anomalies.

### 2. Data Understanding
- Describe the dataset: number of rows, columns, and data types.
- Summarize the central tendency (mean, median) and dispersion (standard deviation) for numerical features.
- Explore categorical features' distribution.

### 3. Data Exploration and Visualization
- **Numerical Features**: Create histograms for distribution.
- **Categorical Features**: Use bar/pie charts to understand category frequency.
- **Comparisons**: Boxplots for distributions across categories.
- **Relationships**: Scatter plots and correlation matrices.
- **Advanced Visualizations**: Pairplots and heatmaps using Seaborn.

## Analysis Questions
1. Distribution of total runs across different overs.
2. Relationship between \`batsman_runs\` and \`dismissal_kind\`.
3. Average number of total runs per over by different \`batting_team\`.
4. Frequency and distribution of \`extra_runs\` conceded by \`bowling_team\`.
5. Relationship between \`batsman_runs\` and balls faced.
6. Distribution of \`dismissal_kind\` across different \`bowling_team\`.
7. Relationship between \`over\` and wickets (\`player_dismissed\`) taken.
8. Performance of bowlers by economy rate against different \`batting_team\`.
9. Relationship between \`dismissal_kind\` and the fielder involved.
10. Bowling strike rate comparison of bowlers across seasons.
11. Runs scored by batsmen across different batting positions.
12. Relationship between batsmen and bowlers in dismissal frequency.
13. Runs scored by pairs of \`batsman\` and \`non_striker\`.
14. Strike rate of individual batsmen against different \`bowling_team\`.
15. Boundary frequency analysis for batsmen.
16. Average total runs per match across seasons.
17. Trends in \`dismissal_kind\` across seasons.
18. Impact of innings (first or second) on total runs scored.
19. Relationship between \`match_id\` and wide deliveries (\`wide_runs\`).
20. Distribution of \`noball_runs\` across seasons.

## Insights and Conclusions
Key findings and patterns observed during the analysis:

--> Mumbai city has hosted the maximum number of matches across all the seasons followed by Bangalore and Kolkata. <br>
--> The run-rate of an inning is highest during the Death-overs(16-20). <br>
--> Suresh Raina, Virat Kohli and Gautam Gambhir are the top-3 run-scorers. <br>
--> There is a positive linear relationship between batsman's runs and the number of balls faced. <br>
--> Caught(getting catch-out) is the most common way of dismissal and more than 50% players in each team get out that way.<br>
--> Getting bowled is the second most common way of dismissal for players in all the teams followd by run-out and LBW(Leg Before Wicket).<br>
--> Kochi Tuskers Kerala is the team where maximum number of players have got run-out and bowled-out. <br>
--> Death overs(16 to 20) are the time when bowlers tend to be more successful in taking wickets. Specially the last three overs have registered the maximum number of wickets. <br>
--> In the context of the initial phase of an inning, the last two overs of the powerplay(5 and 6) show a great chance of taking wickets. Hence, the captain should try to bring their best bowler in this overs. <br>
--> MS Dhoni has been dismissed maximum times by Prgyan Ojha. Rohit Sharma has struggled against the bowlers Ashish Nehra, Vinay Kumar, Axar Patel and Sunil Naraine. Virat Kohli has been dismissed maximum times by Bhuvneshvar Kumar followed by Sandeep Sharma. <br>
--> Chris gayle and Virat kohli have maximum runs(1600) in partnerships followed by David Warner and Shikhar Dhavan(1400 runs).<br>
--> HV Patel has the strike-rate of almost 250 against Rajasthan Royals. <br>
--> Average of the total runs scored per ball was lowest in season of 2009. Howerver, it has shown immense growth in the seasons after 2014. <br> 
--> Getting catch-out has been the most common way of dismissal in all the seasons, followed by getting bowled and run-out. However, there have not been any noticeable shifts in how batsmen are getting out over time. <br>
--> The scores of the first-innings tend to be higher compared to the second-innings. <br>
--> There have been some matches where the number of wide deliveries were more than 23. <br>
--> The no-ball runs were maximum in the season of 2011. However they have been reduced continuously after that season. 

