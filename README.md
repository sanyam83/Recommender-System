# Recommender-System using Collaborative Filtering and Content Based

Dataset from Kaggle(MovieLens 20M rating Dataset) - https://www.kaggle.com/grouplens/movielens-20m-dataset 

## Collaborative Filtering 
Computed Pivot Matrix with UserId as columns and Movies as Rows.

Then used Nearest Neighbour algorithm to find neighbours using cosine distance.

Result: 

![Image](https://github.com/sanyam83/Recommender-System/blob/master/Capture.PNG?raw=true)

Resulted movies are of similar thriller directors(Martin Scorsese, Christopher Nolan , Quentin tarantino, etc.)

## Content Based
Using TFIDF Vectorizer and cosine similarity to compute recommendations

Result:

![Image](https://github.com/sanyam83/Recommender-System/blob/master/Capture12.PNG?raw=true)

Resulted movies are of similar genere and by same director(Matin Scorsese) and actor(Leonardo Dicaprio)[Most of them]
