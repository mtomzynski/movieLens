# movieLens
Analysis of movielens.org dataset

## Table of contents
* [General Information](#general-information)
* [Goal of the Project](goal-of-the-project)
* [Technology](#technology)
* [Analysis](#analysis)
  * [Python](#python)
  * [Apache Spark RDD](#apache-spark-rdd)
  * [Apache Spark DataFrame and SQL] (#apache-spark-dataframe-and-sql)
  * [PowerBI Report (to be done)](#powerbi-report)

## General Information
Source of the dataset: https://grouplens.org/datasets/movielens/25m/

Description: "MovieLens 25M movie ratings. Stable benchmark dataset. 25 million ratings and one million tag applications applied to 62,000 movies by 162,000 users. Includes tag genome data with 15 million relevance scores across 1,129 tags. Released 12/2019"


## Goal of the Project
The project has an educational purpose. The goal is to analyze the movieLens dataset using Python storing data on AWS S3.
I would like to go the entire path from preparing work environment through transforming dataset and analyzing it. Each step is described below in the [Analysis](#analysis) section.

Apart from technology aspect, there are multiple theses which has been visualized and described.

## Technology
Creating the project there were used:
* Python 3
* Amazon Web Services
* Apache Spark
* Jupyter Notebook

## Analysis
There is list of 15 analytical questions I would like to answer using different technologies. They were splitted into 3 groups and described in separate Jupyter Notebooks.


### Python
1. Data clean-up
2. List of distinct genres of movies
3. Standard deviation of rate for each movie
4. Correlation between number of rates and average rate
5. Correlation between average rate and year

See detailed result in [folder Python](https://github.com/mtomzynski/movieLens/tree/master/Apache%20Spark%20Python).

### Apache Spark RDD
1. Average rate for each movie
2. Top 10s roulette
* 10 oldest rated movie
* 10 newest rated movie
* 10 most rated movie
* 10 least rated movie

See detailed result in [folder Apache Spark RDD](https://github.com/mtomzynski/movieLens/tree/master/Apache%20Spark%20RDD).

### Apache Spark DataFrame and SQL
1. Top 10 movies (only those with more than 50 rates)
2. Number of rates for each movie
3. How many movies were assign to specific genre?
4. Number of movies for each year

See detailed result in [folder Apache Spark SQL](http://github.com/mtomzynski).
