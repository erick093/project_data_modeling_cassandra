# Data Engineering - Data Modeling with Apache Cassandra

## Contents

  * [Introduction](#introduction)
  * [Data Model](#data-model)
  * [ETL](#etl)
  * [Execution](#execution)
  * [Acknowledgements](#acknowledgements)
  * [License](#license)
  * [Author](#author)

## Introduction
This project is a data engineering project for the [Data Engineering](https://www.udacity.com) nanodegree at Udacity.

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.
## Data Model
The database of the Sparkify app is a Cassandra database. The database will be modeled according to the queries that the team needs to perform.
The teams need to perform three queries:

  * **Query 1:** List the artist, song title and song's length in the music app history that was heard during  sessionId = 338, and itemInSession  = 4.
  * **Query 2:** List the name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182.
  * **Query 3:** List every user name (first and last) in the music app history who listened to the song 'All Hands Against His Own'.
  
## ETL

For the ETL process, the data from the event_data folder will be transformed into a csv file. 
The transformation will be done by the following steps:

  * **Step 1:** Read the JSON files from the event_data folder.
  * **Step 2:** Transform the JSON data into a CSV file.
  * **Step 3:** Write the CSV file to the output folder.
  
## Execution
The project folder contains a jupyter notebook that will be used to execute the ETL process
and the queries.
## Acknowledgements
This a project of the [Data Engineering](https://www.udacity.com/course/data-engineer-nanodegree--nd027) udacity course.


## License
This project is licensed under the MIT License.

## Author

[Erick Escobar](https://www.linkedin.com/in/erick-escobar-892b20103/)

