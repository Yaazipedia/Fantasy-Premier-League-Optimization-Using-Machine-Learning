# Fantasy Premier League Optimization Using Machine Learning
## Overview
This repository contains the code, datasets, and documentation for our project "Optimizing Fantasy Premier League Strategies: A Machine Learning Approach." The goal of this project is to leverage advanced machine learning techniques to assist Fantasy Premier League (FPL) managers in making strategic decisions, including captaincy selection, fixture difficulty analysis, and team optimization.
## Objectives
Captaincy Selection: Predict the best-performing players to maximize points as captain and vice-captain.
Dynamic Fixture Difficulty Ratings (FDR): Calculate real-time fixture difficulties using machine learning models.
Team Optimization: Provide actionable recommendations to build an optimal team within budget constraints.
## Features
1. Captaincy Prediction Model: Uses a Random Forest Regressor to predict weekly player performance.
2. Fixture Difficulty Model: Implements XGBoost to dynamically rate fixture difficulties based on historical and current data.
3. Data Insights: Visualizations and analyses to explore key trends in player and team performances.
## Methodology
1. Machine Learning Models:
Random Forest Regressor for captaincy prediction.
XGBoost for dynamic fixture difficulty ratings.
2. Feature Engineering:
Metrics like rolling averages, streak-based features, and aggregated player statistics.
3. Evaluation Metrics:
Custom accuracy metrics tailored to FPL performance needs.
## Dependencies
To run the project, you need the following Python libraries:
* pandas
* numpy
* scikit-learn
* xgboost
* matplotlib
* seaborn
* jupyter
## Results
1. Captaincy Model: Achieved a mean accuracy of 77.42% over 31 gameweeks.
2. Fixture Difficulty Model: Provided dynamic FDR values reflecting real-world performance trends.

<img width="261" alt="image" src="https://github.com/user-attachments/assets/c7574ee1-dd76-46aa-94ed-049ce8ed2602" />

## References
Fantasy Premier League Data Source (https://github.com/vaastav/Fantasy-Premier-League/tree/master/data)
Winning with Data in FPL (https://medium.com/@nedara_98396/winning-with-data-my-approach-to-fantasy-premier-league-6c5dd4b84f55#:~:text=Final%20Thoughts:,the%20top%20of%20the%20table)
