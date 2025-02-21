# scotties-toh-champion
Predicting the winner of the 2025 Women's Canadian Curling Championship 

The Scotties Tournament of Hearts is the annual Canadian women’s curling championship sanctioned by Curling Canada since the 1950s. The winning team represents Canada at the women’s world curling championship and returns to the following year’s Scotties as “Team Canada”. The format was originally a round-robin of 12 teams, but in 2021, a new 18-team format was introduced. Teams are separated into two pools of nine and play a round-robin within their pool—the top three teams in each pool advance to a second and third round to determine the champion. 

The dataset complies with performance data and historical rankings from two sources: 
https://en.wikipedia.org/wiki/Scotties_Tournament_of_Hearts

https://www.curling.ca/team-canada/canadian-team-ranking-system/historical-ctrs-results/

The data includes information on team rankings, points earned, shot percentage, event results, and other performance metrics. However, it only extends back to 2003 due to the lack of publicly available records. The dataset can be used for historical analysis, trend identification, and performance forecasting in Canadian women’s curling.

This model was first developed in February 2024 to predict the champion of the 2024 Scotties Tournament of Hearts and was reformatted in February 2025 to predict the 2025 winner. 

NOTE: The data collected only includes information from the round-robins and not the playoff games. Because of the change in number of games played, the averages of the statistics are used as the model features instead of the round-robin totals. The feature champion_share can be interpreted as the medal place (1st, 2nd, 3rd, 4th). A champion_share of 1.0 is equivalent to the champion, a share of 0.75 as the tournament runner up, a share of 0.50 as third place, and 0.25 as fourth place.
