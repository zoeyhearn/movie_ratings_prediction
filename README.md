# movie_ratings_prediction
Data Science Working Student

Assignment
=====================================

MovieRatings_model.ipynb is a Jupyter notebook which predicts the average rating of a movie using features taken from publicly available IMDB Datasets.

The model uses a binary decision tree, where nodes are split on both continuous and categorical variables. Hyper parameters include tree depth, min number of data points per leaf, and splitting criteria. It as presented in a notebook with documented functions.

Additionally, there is a model which uses multiple trees to output an averaged prediction. This includes the additional hyper parameter ‘number of trees’.

Additional documents are taken directly from IMDB Dataset and include: ’title.ratings.tsv’, 'title.basics.tsv’, 'title.akas.tsv' and 'title.crew.tsv’.

Results: The predictive ability of this model is measured by averaging the distance of the predicted rating from the target rating. This measure was compared to the average difference of the mean rating from the target rating. The model shows a 14% decrease, with an average distance of .88 from the target rating. The forrest approach shows a 13% decrease compared to the average difference of the mean rating from the target rating.
