# Movies ETL

## Resources
- Python 3.8.5, 64 bits
- Conda 4.10.1
- Jupyter Notebook 6.3.0
- PostGreSQL 13
- PgAdmin 4
- Data Source: Wikipedia, Kaggle and MovieLens (sources found in "Resources" Folder)

## Overview:

The Amazing Prime company needs an automated pipeline that takes in new data, performs appropriate transformations, and loads the data into existing tables. This project will be refactoring code from Wikipedia movies, Kaggle data and MovieLens rating data. The data integration will be done by adding the data to a PostgreSQL database.

## Process: 

There are 4 steps to this project. 
### First Step: Write an ETL Function to Read Three Data Files

This ETL function reads the data from Wikipedia's JSON file, Kaggle's metadata and the MovieLens csv to create 3 independent dataframes. 

### Second Step: Extract and Transform the Wikipedia Data

Here, we then clean the Wikipedia data by removing TV shows and duplicative data. 

### Third Step: Extract and Transform the Kaggle data

This step also cleans the Kaggle and rating data. After cleaning the data it is formatted and grouped. Kaggle data and rating data are both hrouped and then merged with the previously cleaned Wikipedia data. 

### Fourth Step: Create the Movie Database and import it in SQL

All data is loaded into PostGreSQL and made into a **Movie Database**

## Summary

The project shows how an ETL is perfromed with transforming and cleaning data from multiple sources. This clean data can now be merged to create data tables for information on a plethora of movies. These tables can be used for acquiring data from the movies or can be used as a basis for further analysis. 
