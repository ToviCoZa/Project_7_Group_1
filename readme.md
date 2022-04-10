
![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Project | Module 3

## Introduction

The goal of this project is to practise in supervised learning using Netflix data. We need to create the model for the rating prediction. 
Each group will need to research and implement the defined supervised machine learning methods.

## About the Dataset

A dataset of 8451 rows and 14 columns containing characteristics of movies on Netflix from IMDB, such as genre, director, rating, and so on.
Some columns have numeric types but most of the columns have object types because the cells in them contain a list of values. There is a total of 8508 NaN values.

## Data Cleaning 

We started by dropping the columns that we thought were not relevant for our models.
Then we converted the ‘rating’, ‘vote’ and ‘runtime’ columns types to numeric.
Dropped a few outliers, made the ‘kind’ column more uniform.
We decided to keep only the first country of each cell in the corresponding column, same for the ‘genre’ column.
We kept only the 10 most occurring values in the ‘country’ column.
And finally we scaled the runtime column.

## Models 

We had to use the following models :

-RidgeClassifier

-SVC

-CategoricalNB

-ExtraTreesClassifier