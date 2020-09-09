# Movie-Recommendation-System
Creating a Movie recommendation system which provides list of similar movies by analysing ratings provided by the user.
Importing libraries necessary for the movie recommendation system and dataset is uploaded.
Movie_Id_Titles dataset contains 1682 rows and 2 columns.
I checked numerical statistics for the dataset and the dataset does not contain any null values.
Ratings dataset is loaded which contains 100003 rows and 4 columns.
Timestamp column is dropped since it is not necessary for further analysis.
Ratings dataset is checked and it does not contain any null values and numerical statistics is obtained for the dataset.
Two datasets are merged together by using item_id as common column.
Getting the mean and count column and visualising for the mean is done by plotting a histogram.
Nearly 10 movies were rated 5 stars were rated only once.This seems like only one person has given 5 star rating to those movies Many people around 115 has given 3 stars to most of the movies.
Visualising the count using a histogram and it shows that only few movies around 50 were rated many number of ratings. 
Listed highly rated and low rated movies and user_id_ratings_matrix is created.
User Ratings for the movie StarWars and Titanic is obtained.
Correlation is exhibited between titanic and all other movies and joining the count column from ratings dataset and null values are removed. 
I sorted based on correlation and top 5 movies which are highly correlated to titanic movie is found.
Then correlation is found for starwars movies and all other movies and null values are removed and count column is joined with correlation.
Top 5 movies which are highly correlated with the starwars movies is found.
I Created correlation matrix between all the movies using pearson's coefficient.
User Ratings csv file is loaded and Checking movies provided by user with respect to the movie list for similar ones is found.
List of movies which are similar to 'Liar Liar','Starwars' and 'Titanic' is found.
Based on the user rating for several movies given in the Movies_Id_Titles dataset we can get list of similar movies based on Pearson's Coeffient.


 
 
