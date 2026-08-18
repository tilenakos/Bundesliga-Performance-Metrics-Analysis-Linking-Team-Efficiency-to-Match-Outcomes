# Bundesliga-Performance-Metrics-Analysis-Linking-Team-Efficiency-to-Match-Outcomes

This project analyzes team performance across the last 3 Bundesliga seasons. Using Python and R, I developed a Pythagorean Win Percentage model 
to identify team over/under-performance and applied Simple Linear Regression to evaluate the true impact of corner-kick volume on total goal production.


Language: Python (Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib/Seaborn)

Methodologies: Simple Linear Regression, Pythagorean Expectation Modeling, Residual Analysis

First, we compute the Pythagorean winning percentage with the formula:

pyth_pct = TotalGoalsScored * 2 / (TotalGoalsScored * 2 + TotalGoalsConceded * 2)


And we present the plot of the actual winning percentage along with the Pythagorean winning percentage.
Through this plot, we can see which team overperformed and which ones underperformed 

