# 1_GamesRecommendation:
Analysis of 76,000+ Steam Games + Recommendation System

For the PDF presentation of this project, see: https://aedanyue.files.wordpress.com/2023/08/steamgames.pdf

# Motivation:
As a video game fan, I wanted to understand the kinds of games that might sell well (to improve profits for a company). This data can then be used to 1) predict successful games and 2) recommend potentially fun games to users.

I completed exploratory data analysis, a multiple linear regression (ordinary least squares), and random forest regression models to identify factors predictive of video game success:

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

# Recommender System
This data was used to build a recommender system based on the rating data. The user-generated tag text was vectorized, and the cosine similarity was computed. 





