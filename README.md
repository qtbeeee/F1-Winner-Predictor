# Pole to Podium: Predicting Formula 1 Race Winners (2018–2024)

## Project Overview
Formula 1 is a sport defined by marginal gains and high-stakes decision-making. This project focuses on predicting the winner of a Grand Prix by analyzing the intersection of mechanical performance, driver skill, and historical trends. 

Utilizing a dataset of 14 interconnected CSV files covering the 2018–2024 seasons, We developed a predictive pipeline that outperforms traditional linear baselines by capturing the dynamic complexities of racing.

## The Data Challenge
The raw data required extensive cleaning and consolidation. The final dataset integrates:
* **Race Results & Standings:** Historical performance for drivers and constructors.
* **Qualifying Data:** Grid positions, which are the strongest predictors of race success.
* **Lap-by-Lap Metrics:** Pit stop timings and lap consistency.
* **Environmental Factors:** Circuit characteristics and specialization.

## Feature Engineering
To move beyond basic statistics, the following engineered features were critical to the model's success:
* **Teammate Relative Performance:** Isolating driver skill by comparing pace against their direct teammate in identical machinery.
* **Constructor Momentum:** Rolling averages of team standings to account for mid-season upgrades.
* **Track Expert Score:** Quantifying a driver’s historical dominance at specific circuits (e.g., Hamilton at Silverstone or Verstappen at Spa).
* **The Winner's Paradox:** Addressed the inherent class imbalance (1 winner vs. 19 losers) using weighted objective functions in XGBoost.

## Machine Learning 
* **Baseline Logistic Regression:** In order to set a benchmark, we used logistic regression as a baseline to race predictions
* **XGBoost:** The baseline model is evaluated against this, with gradient boosting outperforming the baseline.

## Detailed Technical Write-up: https://medium.com/@qutub649/cs-334-final-project-predicting-the-winner-of-a-formula-1-race-2018-2024-using-machine-learning-872c9a904a6a

## Acknowledgments
* **Muhammad Shahbaz Aziz Khan**
* **Mehreen Iqbal**
* **Jazim Ali**
* **Qutab Muhammad**
* **Anas Asim Sheikh**


