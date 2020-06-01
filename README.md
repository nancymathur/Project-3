# Project-3
Project 3 – Machine Learning – IMDB Scores & Movie Awards

Our group is tasked to use data analytics and machine learning to accurately predict a movie’s score on IMDB, and to predict if that movie is likely to receive an award. We looked at variables such as the film’s star actor, writer, director, budget, gross revenue, and genre to create the models for our study. This information would be useful for a Hollywood production company to be able to create a winning formula and mitigate the risks involved with a new film.

We sourced our data from IMDB for movies that were released from 1986 – 2016 and found data for the Oscars and Golden Globes. Using Pandas, we merged these data sets to include a count of nominations and awards won for each film. Using this new data set, our group used Tableau to visualize relationships between the variables and Scikit-Learn models to determine which variables have the largest impact on determining the IMDB movie score, or potential to win an award.

We found that the star actor’s average score, director’s average score, writer’s average score, and the amount of user reviews on IMDB were the variables with the highest correlation to the IMDB score received. One caveat we found was that because there are not a lot of writers in our data set that are credited for more than one film that the average writer score carries a lot of weight when using this variable to predict the movie score.

To predict whether a film has the potential to win an award is going to largely be determined by the gross revenue, amount of IMDB user reviews, the overall IMDB movie score, and the writer average score.

Based off our models, we can confidently say that it is reasonable to try to predict a movie’s IMDB score based off the persons making the movie. Then once we know the IMDB score, we can predict if the film has the potential to win either an Oscar or Golden Globe award.

Tableau workbook: https://public.tableau.com/profile/robert.mclauchlan#!/vizhome/MovieUpdated/FilmCompanyRevBudget
