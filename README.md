

![](PostgresQL.png)



Data modeling using PostgresDatabase star schema made ETL pipeline with Python.

This is the very first task entry for your own Data Engineering Nanodegree.  This project is determined by putting into practice the following theories:



- Data modeling with Postgres
- Database star schema created
- ETL pipeline using Python

**Introduction**

A startup called Sparkify wishes to test the data they have been collecting on tunes and user activity on their music streaming program.  The analytics group is very interested in knowing what tunes users are listening.

The purpose is to make a Postgres Database Schema and ETL pipeline to maximize tune play evaluation queries.

**Project Description**

In this project, We must model data with Postgres and construct and ETL pipeline with Python.  On the database side, We must define fact and dimension tables for a Star Schema for a particular focus.  On the other hand, ETL pipeline could transfer data from documents located in two local directories into these tables in Postgres with Python and SQL

**Schema for Song Play Analysis**

**Fact Table**

**songplays** records in log data associated with song plays

**Dimension Tables**

**users** in the app

**songs** in music database

**artists** in music database

**time:** timestamps of records in songplays broken down into specific units

**Project Design**

Database Design is optimized as using a new variety of tables and performing particular connect; we can get the most information and do analysis
ETL Design can be simplified to read JSON documents and parse accordingly to keep the tables into specific columns and appropriate formatting

**Database Script**

Writing python create_tables.py" command in terminal, it is easier to create and recreate tables

**Run ETL**

to run ETL process use command python elt.py

**Jupyter Notebook**

ETL.ipynb, a Jupyter laptop is provided for verifying each command and data also then using those statements and copying into etl.py and running it into a terminal with"python etl.py" and then conducting test.ipynb to see if data has been loaded in all the tables.



#### Project structure Files used on the project:

1. **sql_queries.py** contains all your sql queries

2. **create_tables.py** drops and creates tables. You run this file to reset your tables before each time you run your ETL scripts.

3. **test.ipynb** displays the firstrows of each table to let you check your database.

4. **etl.ipynb** reads and processes a single file from song_data and log_data and loads the data into your tables.

5. **etl.py** reads and processes files from song_data and log_data and loads them into your tables.

6. **README.md** current file

   





