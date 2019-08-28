# ETL-Project-Movies-DB-
This repository contains the deliverable for the ETL Project on Movies Dataset


Project Title: ETL on Movies Data

Data Source: 
1.	Kaggle: (https://www.kaggle.com/rounakbanik/the-movies-dataset#ratings_small.csv)
2.	Movie Lens: (https://grouplens.org/datasets/movielens/latest/)

Description:	
•	This dataset describes 5-star rating on movies. It contains 27753444 ratings and 1108997 tag applications across 58098 movies. These data were created by 283228 users between January 09, 1995 and September 26, 2018. This dataset was generated on September 26, 2018.
•	Using the data, we plan to extract, transform and load the database into a sqlite database using jupyter notebook, pandas, sqlalchemy and other python libraries as required. 
•	This database can then be used to query for any movie based on rating, genre, keywords, IMDB movie id, Movielens ID, TheMovieDB ID.

Project Tasks:
1.	Extraction of the different datasets into pandas DataFrame.
2.	Transform the column ‘Title’ to generate a new column ‘Release Year’.
3.	Transform the column ‘imdbid’ to generate the IMDB link for each movie.
4.	Create different tables for various parameters.
5.	Join all the tables using the ‘movie_id’ as the PRIMARY KEY.
6.	Create database in SQL.
7.	Load the table data that is generated into the Database.

