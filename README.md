# Movies-ETL

## Overview

Our client, Amazing Prime, is hosting a "hack-a-thon", allowing participants to create an algorithm that will predict which low budget films will become popular so they can buy them for a bargain. My purpose for this project was to create the database to be used for the hack-a-thon by performing an ETL on all movies released since 1990.

The data sources used for this dataset are a webscrap of Wikipedia for all movies released since 1990 and rating data from the MovieLens website. The following steps were conducted to produce the database.

* Construct an ETL pipeline from the raw data sources to a SQL database
* Extract data using Python
* Transform the data using Panda and Jupyter Notebook
* Parse the data using regular expressions to transform text into numnbers
* Load everything with PostgreSQL

