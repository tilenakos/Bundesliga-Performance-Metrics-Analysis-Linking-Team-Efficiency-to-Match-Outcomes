# Bundesliga-Performance-Metrics-Analysis-Linking-Team-Efficiency-to-Match-Outcomes

This project analyzes team performance across the last 3 Bundesliga seasons. Using Python and R, I developed a Pythagorean Win Percentage model 
to identify team over/under-performance and applied Simple Linear Regression to evaluate the true impact of corner-kick volume on total goal production.


Language: Python (Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib/Seaborn)

Methodologies: Simple Linear Regression, Pythagorean Expectation Modeling, Residual Analysis

**Pythagorean Expectation (True Team Quality)**

First, we compute the Pythagorean winning percentage with the formula:

pyth_pct = TotalGoalsScored * 2 / (TotalGoalsScored * 2 + TotalGoalsConceded * 2)


And we present the plot of the actual winning percentage along with the Pythagorean winning percentage.
Through this plot, we can see which teams overperformed and which ones underperformed 

##### here we put the plot
<img width="849" height="859" alt="download" src="https://github.com/user-attachments/assets/83bfe8c6-447e-4f3d-b1ab-33f75039a1b7" />


Identified that Freiburg over-performed their expected metrics by almost 5% in last 3 years, indicating high regression risk for the following season.
While, it is clearly visible that all Top 6 teams over-performed last 3 seasons.

**Corner Volume vs. Goal Production (Linear Regression)**

I analyzed whether a higher volume of earned corners correlates with overall attacking efficiency.

Analyzing the regression results we start from R-squared, which has the value 0.82. 
This shows us that the is a strong correlation between corners won by a team and goals scored, since the value is really close to 1.

Moving forward, we have to check the value of p-value, which is <0.001.
This value shows us that the independent variable of our regression (the goals) 
is statistically significant.

The conclusion we can have after looking at the regression results, is that for every 1 corner won by a team,
the total number of goals scored in the game increases by 0.4139.

If we translate this result the other way, means that in approximately every 2.5 corners won in each game by the teams, 1 more goal is scored.
This shows us that in Bundesliga there is an extremely high connection between corners won and goals scored by the teams compared to other 
championships around Europe. And furthermore, this shows us that Bundesliga teams pay a lot of attention in set pieces, 
as they produce a big number of their goals from them.



















