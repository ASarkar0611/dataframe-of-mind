# __TVShow Data  Cleaning and Segmentation__
Data Cleaning and segmentation using Pandas library in Python.

This repository contains four  files - unclean CSV file, clean Excel file and the Python notebooks. To emphasize, the sole purpose of the code is to have clean data which can be further taken forward. This means that there will be lot of missing values which can be updated as per intention and end goal if anyone decides to further use the cleaned dataset. Maximum of four directors and actors were considered for this purpose.

__Kaggle Dataset:__ https://www.kaggle.com/datasets/bharatnatrayn/movies-dataset-for-feature-extracion-prediction/data                                                                           
__Kaggle Code URL:__ https://www.kaggle.com/code/arunitasarkar/moviedatasetcleaning

__Columns Details:__

MOVIES - The movie names are given under the column                                
YEAR - The year of movie or tv shows telecast for audience                           
GENRE - The dataset contain many genres most valuable for recommendation system     
RATING - The audience thought about movie or tv show given             
ONE-LINE - The short description about movie or tv show for audiences first impression                                                                
STARS - The casting of art is define under this columns which makes talk between audience                                                   
VOTES - The audience express their view under the columns its useful to identify impact make by art                                                    
RUNTIME - The duration for runing time of art                              
GROSS - It gives the total amount earned in worldwide                          

__File Details:__

Unclean File - movies.csv                                                                                                                   
Clean File - output.xls                                                                                              
Python Notebook - MovieDatasetCleaning.ipynb, Movie Segmentation.ipynb                                                                                                  

__Steps Performed to Clean the Dataset:__

1. Import required packages.
2. Read the CSV file.
3. Use shape() function to get the number of rows and columns of a dataset.
4. Show the column names of the dataframe.
5. Drop the duplicate records using drop_duplicates() function.
6. Format each of the columns which felt necessary to clean. Formatting included removing unneccessary characters, handling NULL values, stripping white spaces or other characters and converting the datatypes of the column.
7. Unwanted columns are dropped using drop().
8. Sort the dataset by Rating and Gross amount in descending order.
9. Segmentation performed using K-means with silhoette score, Calinski-Harabasz score and Davies-Bouldin score.
