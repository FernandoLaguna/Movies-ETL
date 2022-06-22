
# Movies ETL

## Overview of the project
Ceate an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. Create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Process:

1. Write a function that reads in the three data files and creates three separate DataFrames. (ETL_function_test.ipynb)
2. Using Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data to merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates (ETL_clean_wiki_movies.ipynb).
3. Extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. (ETL_clean_kaggle_data.ipynb).
4. Add the movies_df DataFrame and MovieLens rating CSV data to a SQL database (ETL_create_database.ipynb)

![Image](/Images/resize.jfif)


## Summary:

This code automates the cleaning and sanitizing of the databases to be able to be included in SQL

