NBA Player Data from 2003 to 2022
Our dataset: https://github.com/andrewjingalls/chapman/blob/main/NBA_PLAYER_DATA.csv

Andrew Ingalls
Shane Leimel
Will Keegan

CPSC 392

Variables:
Player: Player name
Pos: Position
Age: Age at the time of playing
GP: Games played
MP: Average minutes played per game
FG: Average field goals made per game
FGA: Average field goals attempted per game
FG%: Average field goal percentage per game
3P: Average three-pointers made per game
3PA: Average three-pointers attempted per game
3P%: Average three-pointer percentage per game
FT: Average free-throws made per game
FTA: Average free-throws attempted per game
FT%: Average free-throw percentage per game
ORB: Average offensive rebounds per game
DRB: Average defensive rebounds per game
TRB: Average total rebounds per game
AST: Average assists per game
STL: Average steals per game
BLK: Average blocks per game
TO: Average turnovers per game
PTS: Average points scored per game
Year: Year played
Team: The team played on 
W/L%: Average win/loss percentage


Questions: 

When considering position, games played, and average points scored per game, what clusters emerge and what can we learn from the clusters?
Do certain teams average a higher free throw percentage over the 20-year span of the dataset?
What team has the largest variance in average points per game?
How does the mean squared error change when making a linear regression model comparing a player's position to their field goal and free throw percentage? 
Over the past 20 years, has there been an upward trend in overall 3-point performance?
How does a player’s average minutes played correlate with their overall contribution to team victories?
What factors contribute to a player consistently participating in a high number of games per season?
Which players exhibit the most consistent performance across multiple seasons in terms of points scored per game?
Can we identify any patterns or trends in the playing styles of top-performing players over the years?
How does player position correlate with their average points scored per game?
Are there specific positions that contribute more to team wins, as indicated by the win/loss percentage?
Is there a significant correlation between a player’s age and their average minutes played per game?
When creating a hierarchical clustering model with all the continuous variables, what clusters emerge, and how many clusters produce the highest silhouette score?
Which predictor has the greatest effect on average minutes played per game?
When predicting minutes played per game, which predictors out of position, points scored per game, average turnovers per game, and average total rebounds per game produce the lowest variance?
