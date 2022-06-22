
# Movies ETL

## Overview of the project
Ceate an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. Create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Process:

1. Write a function that reads in the three data files and creates three separate DataFrames. (ETL_function_test.ipynb)
2. Using Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data to merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates (ETL_clean_wiki_movies.ipynb).
3. Extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. (ETL_clean_kaggle_data.ipynb).
4. Add the movies_df DataFrame and MovieLens rating CSV data to a SQL database (ETL_create_database.ipynb)

![City type comparison](/analysis/tabla1.png)
![Fare per city type](/analysis/PyBer_fare_summary.png)

## Summary:


Three business recommendations to the CEO:

1. Increase the number of drivers in rural cities
2. Review the number of drivers in urban cities (probably they are to many)
3. Review if all the urban drivers are working a complete journey (the number of driver exceed the numbers of rides)

