# EECS 731 - Introduction to Data Science
## Weekend movie trip

###### Blockbuster or art film?

1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the one of the MovieLens datasets from https://grouplens.org/datasets/movielens/
3. Load the data set into panda data frames
4. Formulate one or two ideas on how the combination of ratings and tags by users helps the data set to establish additional value using exploratory data analysis
5. Build one or more clustering models to determine similar movies to recommend using the other ratings and tags of movies by other users as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub
_______________________________________________________________________________________________________________

- The Raw data and information about datasets downloaded can be found under **_/data_**
- The processed data can be seen under **_/notebooks_**
- After initial Data cleaning steps, different features were used for feature engineering and checking correlation
- Using the features **"tag"** and **"rating"** , it was possible to find average ratings for the movies based on a particular rag that can help decide the genre of the movie
- K-means Clustering model was used to form 4 clusters
- The list of recommended movies to be displayed on the input of a movie name using the ratings and tags of movies by other users
- The required notebook with Source code and Visualizations : **_Movie.ipynb_** under **_/notebooks_**

## -----------------------------------Thank You---------------------------------------
