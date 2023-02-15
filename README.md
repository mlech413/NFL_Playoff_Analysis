## NFL_Playoff_Analysis

# Premise: In the NFL, can statistics predict Super Bowl winners?

## Data

# Three types of csv files, containing NFL historical data from 2003 - 2022 (20 years) as follows:

* nfl_statistics_team_offense_by_season.csv: 25 different offensive statistical categories for every team, by season.
* nfl_statistics_team_defense_by_season.csv: 25 different defensive statistical categories for every team, by season.
* nfl_playoff_results_by_season.csv: all individual playoff game results for the same 20 year period.

# Data is merged and produces 50 different statistical categories per season, along with the results of 225 playoff games for those teams.

## Tools & Technologies Used
EXCEL FOR ALTERNATE CHARTING
JUPYTER NOTEBOOK:
* PANDAS FOR DATA ANALYSIS
* NUMPY FOR MATHEMATICAL FUNCTION
* SCIPY FOR LINEAR REGRESSION ANALYSIS
* STATMODELS.API FOR REGRESSION MODELS
* SEABORN FOR DATA VISUALIZATION

## Strategy

# To reach a conclusion, we delivered the answers to four related key questions:
1. Are Super Bowl winners statistically superior to the other playoff and non-playoff teams?
Answer: No. Analyzing 4 major areas of offense with Excel pivot tables and bar charts , the winning team did not consistently outperform the averages of the other teams. 3 types of teams were compares: Super Bowl winners, other playoff teams, and teams that did not qualify for the playoffs. The four major offensive categories showed a sporadic and unclear difference in the rankings for those teams. No definitive pattern is exhibited by the winning team.

2. Are there statistical similarities between Super Bowl winners?
Answer: No. Across 50 statistical categories, bar charts and Co-efficient of Variations (CV) were compared year-to-year for the Super Bowl winners. The few that demonstrated a low CV (i.e. were similar) were also very close to the league average (with only a 1.3% and 0.3% diffewrence). Most other categories varied substantially.

3. Is there a relationship between offense and defense?
Answer: No. Super Bowl winning teams were analyzed for their offensive and defensive rankings. Using a scatter plot, we saw very little correlation between the 20 winners and their strength in either direction. Linear regression analysis showed a weak relationship. Our linear regression model indicated with a low R-Squared value of 0.119 and a very low Adjusted R-Squared of 0.016 that a sample size of 20 winners is too weak, so a larger sample size along with additional variables would also likely be needed to determine correlations. A statistical correlation heat map showed a negative correlation of -0.27, further making the point.

4. Do any statistics predict a future Super Bowl winner vs. the other playoff losers?
Answer: No. We analyzed the maximum round each team achieved in the playoffs, and tested their correlation to their seasonal rankings. To do this, we experimented with multiple types of scatter plots, eventually settling on bubble plots in which multiple identical plots are larger. Those plots as well as the low R-values did not identify any useful relationships. A second type of analysis looked at the average rankings per round, which showed a number of very strong R-value correlations, but drilling down into the individual data showed this was a product of using overall averages, and was not a predictor of the Super Bowl Winner.

## Conclusion:

Unfortunately, based on the 50 categories of statistics used here, statistics cannot predict Super Bowl winners in the NFL.

## Results

A PowerPoint presentation "NFL Playoff Analysis", supported by the associated Jupyter notebook "NFL_Eval" and Excel spreadsheet "NFL_Summary_Statistics_Winner-vs-Others".