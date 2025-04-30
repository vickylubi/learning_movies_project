# learning_movies_project

## Movie Data EDA Project

### Overview
This project performs Exploratory Data Analysis (EDA) on a movie dataset to uncover insights into:


1. Strong and weak correlations between movie features (like budget, gross, rating, votes, etc.)
2.Top-performing companies by gross earnings, budget investment, and overall profit
3.Data cleaning and transformation techniques for preparing real-world data
4.The main goal is to practice and demonstrate EDA skills using Python libraries such as pandas, numpy, seaborn, and matplotlib.



### Dataset
Source: movies.csv / https://www.kaggle.com/datasets/danielgrijalvas/movies

Size: Approx. 2,300 rows with multiple features like budget, gross, votes, rating, company, etc.

Preprocessing Steps:

Dropped rows with missing data

Converted budget, gross, and votes to numeric types

Cleaned up released year and removed redundant year column



### Tools & Libraries

Python 3

pandas

numpy

seaborn

matplotlib


### Main Explorations

Missing Value Analysis

Data Type Conversion

Date Cleaning and Formatting

Correlation Analysis:

Pearson correlation heatmaps

Encoding categorical variables to find hidden correlations

Company Performance:

Grouped gross and budget by company

Calculated profit per company (gross - budget)

Identified top 10 profit-making and loss-making companies

Visualized company rankings using bar plots


