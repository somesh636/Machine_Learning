# SENTIMENT_ANALYSIS 

* This Project is about Sentiment analysis using Machine Learning.
* I have build a predictor for that can distinguish between positive
  and negative reviews.
* It Uses 50,000 reviews from Internet Movie Database (IMDb) to predict 
  and distinguish between positive and negative reviews for the movies.
* The positive reviews is one in which the user has given more 
  than 6 stars to the movie.
* The negative reviews is one in which the user has given less
  than 6 stars to the movie.
* I have used Pipeline to combine ifidfVectorizer and LogisticRegression estimators 
  together and feed it to GridSearchCV for searching the best hyper-parameters
* used Out of core learning method for training data in batches 

# Results
* Using the Best GridSearch Estimators achieved as score of 89.9% for Test accuracy   

# Dataset Link 
* http://ai.stanford.edu/~amaas/data/sentiment/

