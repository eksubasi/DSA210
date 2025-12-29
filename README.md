# nba-salaries-and-ratings

### Project Overview

This project seeks to analyze the performance metrics and annual salaries of NBA players to determine who is underpaid or overpaid. It focuses on key statistical factors such as points, rebounds, assists, turnovers, and playtime, to then compare it with their salaries. By modeling how performance translates into pay, this project aims to reveal which players provide the best value for their cost and whether NBA salaries accurately reflect on-court impact.

---

### Objectives

The main objective of this project is to analyze how player ratings influence the salary distribution of NBA players across different teams and positions. By using public data from NBA's recent seasons, it aims to:

- Find the correlation between a player's statistical ratings (points, rebounds, assists, turnovers and playtime) and their annual salary.
- Examine whether low-paid players perform better or contribure more relative to their cost.
- Develop regression models showcase the relationship between player stats and their slary levels (low, mid and high salary).
- Provide insights for teams and analysts on how to evaluate player value and identify potential underpaid or overpaid players.

---

### Motivation

Basketball is a big passion of mine, and I find watching it so exciting. My favorite is especially NBA, given its star players and breathtaking matches. I used to play basketball, and wanted to become a NBA star to become rich and popular like them. However now I often wonder: Do these stars truly earn their salaries? Or do lesser-known players deliver more value for their cost? This project aims find a correlation between their costs and ratings to uncover who's worth their contract.

---

### Data Sources

*Basketball Reference* - provides detailed player statistics for the selected seasons namely the ones mentioned in objectives, and also includes other specific metrics.

*Kaggle* - offers the official player contracts and their annual salaries for each year along with team spending and salary cap details.

---

### Analysis Plan

- Data Collection: Gather the player statistics. Clean and merge the datasets using player names and seasons. Handle the missing data for consistent format.
- Data Analysis: Visualize the distribution of salaries and find a correlation between their performance and cost respectively.
- Modeling: Build regression models to predict player salaries based on performance statistics. Evaluate results using R² and RMSE metrics.

---

### Expected Outcomes

- Finding the relationship between performance and salary, and understanding if they are actually related or not.
- Identifying the underpaid and overpaid players.
- Creating a regression model capable of predicting a player's salary by their performance in the respective season.
- Getting insights on salary fairness, and proving that there are players who perform significantly better but paid less.

---

### Tools & Technologies

Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

### References

- Player and team statistics database - Basketball Reference
- NBA players contract and salary data - Spotrac
- Combined datasets for each - Kaggle
