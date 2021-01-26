# notebook_ia-course
Artificial Intelligence course, keras, tensorflow, pytorch and more. (NOTEBOOK)

Context
Motivated by Gregory Smith's web scrape of VGChartz Video Games Sales, this data set simply extends the number of variables with another web scrape from Metacritic. Unfortunately, there are missing observations as Metacritic only covers a subset of the platforms. Also, a game may not have all the observations of the additional variables discussed below. Complete cases are ~ 6,900

Content
Alongside the fields: Name, Platform, YearofRelease, Genre, Publisher, NASales, EUSales, JPSales, OtherSales, Global_Sales, we have:-

Critic_score - Aggregate score compiled by Metacritic staff
Criticcount - The number of critics used in coming up with the Criticscore
User_score - Score by Metacritic's subscribers
Usercount - Number of users who gave the userscore
Developer - Party responsible for creating the game
Rating - The ESRB ratings

Dataset from kaggle: https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings
Dataset from frankjony17: https://drive.google.com/file/d/1hX7yoZZvMO3XEHLQvieACuZG8OZQM5nQ/view?usp=sharing