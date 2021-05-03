# Predict IMDB movie rating

How can we tell the greatness of a movie before it is released in cinema?

## 1.Parsing data

The first part aims to parse data from the imdb and the numbers websites : casting information, directors, production companies, awards, genres, budget, gross, description, imdb_rating, etc.  
To create the movie_contents.json file :  
``python3 parser.py nb_elements``  

## 2.Data Analysis

The second part is to analyze the dataframe and observe correlation between variables. For example, are the movie awards correlated to the worlwide gross ? Does the more a movie is a liked, the more the casting is liked ? 

[Correlation Matrix]
 
Obviously, domestic and worlwide gross are highly correlated. However, the more important the production budget, the more important the gross.  
As it is shown in the notebook, the budget is not really correlated to the number of awards.  
What's funny is that the popularity of the third most famous actor is more important for the IMDB score than the popularity of the most famous score. 
Analysing top directors ,top movies and so on.

## 3.Predict the IMDB score

Machine Learning to predict the IMDB score with the meaningful variables.  
Using a MachineLearning Algorithms.

