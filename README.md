
# IPL Data Analysis Project

## Overview
This project analyzes Indian Premier League (IPL) data using Python and several data analysis and visualization libraries such as `pandas`, `matplotlib`, and `seaborn`. The dataset includes match information from different seasons and captures a variety of attributes like match results, player performances, venues, and other key metrics.

The primary goal of this project is to explore patterns in the data, such as determining which players have won the most "Player of the Match" awards, understanding team performances when batting first or second, and examining the correlation between toss wins and match wins.

## Dataset
The dataset used for this project is `ipl_data.csv`. It contains 756 records (matches) and 18 columns:
- `id`: Match identifier
- `season`: IPL season year
- `city`: City where the match was played
- `date`: Date of the match
- `team1`, `team2`: Teams participating in the match
- `toss_winner`: Team that won the toss
- `toss_decision`: Decision made by the toss winner (bat/field)
- `result`: Match result (normal, tie, no result)
- `dl_applied`: Whether Duckworth-Lewis method was applied
- `winner`: Team that won the match
- `win_by_runs`: Number of runs by which the team won (if applicable)
- `win_by_wickets`: Number of wickets by which the team won (if applicable)
- `player_of_match`: Player who won the "Player of the Match" award
- `venue`: Venue where the match was played
- `umpire1`, `umpire2`, `umpire3`: Umpires officiating the match

## Requirements
To run this project, you need the following Python packages installed:
- pandas
- matplotlib
- seaborn

You can install the dependencies by running:

```bash
pip install pandas matplotlib seaborn
```

## Key Analyses
### 1. Most "Player of the Match" Awards
We explored which players have won the most "Player of the Match" awards across seasons. Chris Gayle leads the list with 21 awards, followed by AB de Villiers with 20.

### 2. Toss and Match Wins
The number of times a team won both the toss and the match was calculated. It was found that teams won 393 matches after winning the toss.

### 3. Wins by Batting First vs. Second
We differentiated the matches where teams won by batting first or second and visualized the data using bar plots and histograms.

- **Teams Winning by Runs (Batting First)**:
  Mumbai Indians have won the most matches batting first, with 57 wins.
  
- **Teams Winning by Wickets (Batting Second)**:
  Kolkata Knight Riders have won the most matches chasing, with 56 wins.

### 4. Match Distribution by Season and City
We examined the number of matches played each season and the number of matches played in different cities. Mumbai hosted the most matches (101), followed by Kolkata (77).

## Visualizations
Several plots were created to illustrate key insights:
- **Bar plots** for top players with the most "Player of the Match" awards.
- **Histograms** for the distribution of wins by runs and wickets.
- **Pie chart** for wins by different teams when batting first.
- **Bar plots** for the top teams winning after batting first and second.

## How to Use
1. Clone this repository.
2. Load the dataset (`ipl_data.csv`) into a pandas DataFrame.
3. Execute the analysis scripts to generate insights and visualizations.

## Conclusion
This analysis provides an in-depth look at team performances, player achievements, and trends across IPL seasons. The visualizations offer insights into key aspects like toss impact, batting order effectiveness, and match locations.
