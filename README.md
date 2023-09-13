# EDA-with-Python
Exploratory Data Analysis of my own imdb ratings using pandas, numpy, seaborn, matplotlib in python

**Introduction**

This repository contains code and documentation for the Exploratory Data Analysis (EDA) project using imdb dataset sourced from (https://www.imdb.com/)

**Objective**

Clean and enhance the dataset, perform EDA which provides information about watching/rating patterns in the IMDb ratings.

**Dataset overview**

'ratings.csv' contains 995 records of ratings given. Each record represents a unique rating (identified by IMDb id) and includes various attributes such as Title, Relase Date, Release year, Directors and more

**How to source data**

Visit https://www.imdb.com/ -> Your Ratings -> Click on the 3 vertical dots next to text 'Your Ratings'-> Select export

**Issues found in the data**
1. Missing values- there were some in the 'Directors' and 'Runtime (mins)' columns, making it necessary to fill these to maintain consistency of data
2. 'Date Rated' column had dates stored in string format; which needed conversion to datetime format so that year, month can be extracted for further analysis

**Tools used**

For the EDA project, following tools were used
1. Python for data cleaning tasks
2. Pandas was instrumental in data manipulation, cleaning and handling missing values
3. NumPy was utilized for mathematical operations and array handling during the cleaning process
4. Google Colab provides an interactive Jupyter notebook environment for code development, exploration and documentation
5. Seaborn and matplotlib for plotting the data 

**Data Cleaning Process**

The data cleaning process involved the following steps:

**Data Understanding** - The dataset was thoroughly examined to understand the structure, columns and their meanings. Having used the IMDb website since 2016 helped me get a grasp of the data quickly.

**Data Exploration** - Exploratory Data Analysis was performed to gain insights into the data, identify patterns and uncover anomalies.

**Handling missing values** - I filled the missing values in 'Directors' column with 'Not Available' and those in 'Runtime (mins)' column with the average runtime of the concerned entities which I was aware of.

**EDA**

EDA process involved following steps:

Getting the insights into the data using pandas, numpy framework

Plotting the analysis of columns to reveal their corelation, trend, comparisons

**Documentation** 

For detailed information about the EDA process, please refer to the Jupyter notebook provided in the repository
