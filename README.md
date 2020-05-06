# Board-Game-Review-Prediction
Using Linear and Non-Linear models to predict the average review a board game will receive based on characteristics such as minimum and maximum number of players, playing time, complexity, etc.
## Dataset:
Taken from: https://github.com/ThaWeatherman/scrapers/blob/master/boardgamegeek/games.csv<br>
The dataset contains 81000 instances from data scraped from Board Game Geek Website.<br>
#### Attributes include:
id                         
type                   
name                    
yearpublished                   
minplayers                      
maxplayers                      
playingtime                    
minplaytime                     
maxplaytime                     
minage                          
users_rated                     
average_rating                  
bayes_average_rating             
total_owners                   
total_traders                   
total_wanters                   
total_wishers                    
total_comments                  
total_weights                   
average_weight                   
## Models used:
Linear model: Linear Regressor<br>
Non Linear model: Random Forest Regressor<br>
## Evaluation metric
Mean Squared Error
## Conclusion
While the time for model construction was greater for Random Forest Regressor in comparison to the Linear Regressor, it gave a smaller mean squared error for the validation data. We can conclude that a non-linear model was better fit to this data and problem statement.
