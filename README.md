# Movies-ETL

## Overview of Project

### Purpose
A company named Amazing Prime has a dataset which they would like to keep up-to-date on a daily basis.  An employee (Britta) has requested my assistance to to create an automated pipeline that will Extract, Transform and Load (ETL) the data into exising PostgreSQL tables.  The existing code has been refactored to to take arguements of the three (3) file names that include Wikipedia data, Kaggle metadata and the MovieLens rating data.  The standard data analysis principles were used which includes; (1) Determine the number of rows and columns; (2) Data types used; and (3) Is the data readable?


## Resources

- Jupyter Notebook
- PostgreSQL (A Relational Database Management System)
- pgAdmin (Interface to interact with PostgreSQL)
  
 ## Results
 
 To produce some valuable data from this messy ETL process, I had to create four new Jupyter Notebook files.  These files include;
 1. ETL_function_test.ipynb (Function read all data files)
 2. ETL_clean_wiki_movies.ipynb (Code to Extract and Transform Wikipedia data)
 3. ETL_clean_kaggle_data.ipynb (Code to Extract and Transform Kaggle data)
 4. ETL_create_database.ipynb (Refactored code to load the extracted and transformed data into a PostgreSQL database)
 
 The ETL process produced the "movies" and "ratings" tables in the "movie_data" database.
 
__Movies:__

![Total Number of Movies Imported](https://github.com/SheaButta/Movies-ETL/blob/main/Resources/movies_query.png)

__Ratings:__

![Total Number of Ratings Imported](https://github.com/SheaButta/Movies-ETL/blob/main/Resources/ratings_query.png)

 
 ## Summary
 
 The transformation effort of this ETL process proved to be extremely difficult and messy; however, I was able to produce data that will prove to valuable to Amazing Prime.
 
 
 
 
 
