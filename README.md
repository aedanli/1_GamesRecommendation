# 1_GamesRecommendation:
Analysis of 76,000+ Steam Games + Recommendation System

For the PDF presentation of this project, see: https://aedanyue.files.wordpress.com/2023/08/steamgames.pdf

# Motivation:
As a video game fan, I wanted to understand the kinds of games that might sell well (to improve profits for a company). This data can then be used to 1) predict successful games and 2) recommend potentially fun games to users.

Dataset: https://www.kaggle.com/datasets/fronkongames/steam-games-dataset

Data on 76,000+ games were scraped from Steam, August 8, 2023.

I preprocessed the data, completed exploratory data analysis, and then fit a multiple linear regression (ordinary least squares) as well as a random forest regression model to identify factors predictive of video game success:

# Summary:
1. Massive Multiplayer games are most popular, but likely requires a high budget to make.
2. For smaller developers, action and adventure games are most likely to be successful.
3. Developers should add a multiplayer or co-op option to increase sales.
4. November is the best month to release a game.
5. A small proportion of games made by developers and publishers become highly successful

This analysis identified key areas of future investigation, given limitations in the current dataset:
1. Positive ratings have a complex relationship with sales. Need to better understand this factor.
2. With additional user data, we can build more targeted recommendations by genre.
3. Our models account for only ~30% of the variance. Need to understand the factors associated
with the game itself that contributes to success: What makes a game good?

# Game Recommender System
This data was then used to build a recommender system based on positive ratings and sales. To find the similarity between games, the user-generated tag text was vectorized, and cosine similarity was computed. 







