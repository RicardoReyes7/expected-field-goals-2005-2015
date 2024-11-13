This project was assigned in RSM384: Sports Analytics class by Professor Matthew Mitchell.

# NFL Field Goal Analysis Project
## Overview
This project analyzes NFL field goal performance using statistical methods. By applying logistic regression and various evaluation metrics, the project aims to estimate the likelihood of a successful field goal based on factors such as distance, game score difference, field surface, and time. The analysis includes evaluating each kicker's performance against model expectations to identify top performers and insights into kicker efficiency.

## Project Structure
#### Data Source: The data is sourced from a public dataset on field goals in the NFL, available at https://raw.githubusercontent.com/statsbylopez/StatsSports/master/Data/nfl_fg.csv

## Steps of Analysis:
#### Expected Goal Calculation: 
I used logistic regression to calculate the probability of a successful field goal based on distance, score difference, grass field, and game minute.
#### Evaluation of Performance: 
I calculated the points scored above average to assess kickers' consistency and performance against model expectations.
#### Identification of Top Performers: 
I analyzed kickers who exceed or underperform relative to expectations, identifying the top performers in various contexts.
#### Kicker Efficiency Analysis: 
By comparing distance with extra makes, I evaluate the efficiency of the top 5 kickers relative to all other NFL kickers.

## Results:

The logistic regression model proves that distance negatively impacts field goal success, as expected, with the odds of success decreasing for longer kicks. Field surface also plays a role, with kicks on grass showing a slightly reduced probability of success compared to turf. Surprisingly, game minute and score difference have minimal impact on success probability, suggesting these situational factors might indicate there is less pressure than commonly assumed. The model's evaluation of "extra makes" — the difference between actual and predicted successful kicks - highlights that most kickers perform close to expectations, but a few consistently outperform or underperform the model's predictions. In particular, the top five kickers yield notably higher success rates on challenging kicks, especially from longer distances, proving their exceptional skill and consistency relative to the league. This analysis provides valuable insights into player performance, helping teams understand the balance between skill, conditions, and chance in field goal success.
