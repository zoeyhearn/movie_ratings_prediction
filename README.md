# movie_ratings_prediction
Data Science Working Student

Assignment
=====================================

MovieRatings_model.ipynb is a Jupyter notebook which predicts the average rating of a movie using features taken from publicly available IMDB Datasets.

The model uses a binary decision tree, where nodes are split on both continuous and categorical variables. Hyper parameters include tree depth, min number of data points per leaf, and splitting criteria. 

Additionally, there is a model which uses multiple trees to output an averaged prediction. This includes the additional hyper parameter number of estimators.

Additional documents can be downloaded from IMDB Datasets:  https://datasets.imdbws.com/
Datasets used: title.ratings.tsv, title.basics.tsv, title.akas.tsv and title.crew.tsv

