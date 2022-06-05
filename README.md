# Data Modeling with Postgres
## Project summary
Sparkify is a startup that wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. But they don't have an easy way to query their data.

This project creates a Postgres database schema and ETL pipeline with tables designed to optimize queries on song play analysis.

## How to run the project
The final script is the `etl.py` file and you can run it from the terminal as follow:
```
python etl.py
```
or
```
python3 etl.py
```

## Files of the project
* `create tables.py` : It's a reset script to delete and recreate the tables.
* `etl.py` : This files reads the data from files, pre-processes it and create the whole database schema and tables.
* `etl.ipynb` : The same as the previous one for trying and optimizing.
* `sql_queries.py` : Includes all the SQL Queries used over the project.
* `test.ipynb` : Initially tests the tables and database.

## database schema design and ETL pipeline
The database disign is a star schema and designed as follow:

![Database Design](/img/design.png?raw=true)