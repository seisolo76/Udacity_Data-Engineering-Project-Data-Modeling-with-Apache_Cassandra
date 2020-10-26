# Project: Data Modeling with Cassandra

##### by Kelly Joseph 5-27-2020

## Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

## Project Description
In this project, I have applied what I learned on data modeling with Apache Cassandra and built an ETL pipeline using python within a Jupyter worksheet. To complete this project, I needed to model the data by creating tables in Apache Cassandra to run queries. I created ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

## Datasets
The only dataset in this project is event_data. It contains a directory of CSV files partitioned by date. Here are are the file paths in the dataset.
```
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```



