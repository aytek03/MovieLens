In this assignment, there are 3 questions.
Jupyter notebook is used.

These files are;

1. First_question.ipynb

2. Second_question.ipynb
3. Second_question2.ipynb
4. Second_question3.ipynb
5. Second_question4.ipynb
6. Second_question5.ipynb

### 1. First_question.ipynb ###

We use movielens-small.db and read this database.

We extract movielens-small.db and obtain and save four .csv files.
These files are movies, links, tags and ratings.

In this code, we solve the first part.

### 2. Second_question.ipynb ###

In this code, we solve this task:

Provide an implicit feature by using any of the data from the given database.

I designed implicit feedback.

### 2. Second_question2-5.ipynb ###

-Train two individual recommender models, one by using rating (from ratings table) 
and the other one by using your designed implicit feedback.-

In this code, we try to several recommender models using rating rable.

Second_question2 -->>>> Alternating Least Squares

Second_question3 -->>>> Bayesian Personalized Ranking

Second_question4 -->>>> Logistic Matrix Factorization

Second_question5 -->>>> kNN Nearest Neighbors

###Present comparison between two models, by using essential metrics###

All of designed recommender models' results are different.

I compare kNN model between my implicit feedback model.

In Knn model, recommended movies are 296, 2959, 457, 2571, 6874, 260, 47, 1089, 2858, 593
while in implicit feedback model, recommended movies are 706 and 8552 movieID.

In Knn model, we use cosine metric.
