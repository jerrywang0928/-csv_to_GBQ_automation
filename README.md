# csv_to_GBQ_automation
Python script that automates CSV file imports to a Google BigQuery database

By: Zhe Wang 

Aug 7, 2022
___

## Description

This script will automatically import CSV files to your GBQ database. Just place the CSV files in the same directory as the notebook and run the notebook. The notebook will automatically clean the file name and column headers, create the db table, and copy the file over to the database. The table names are the same names as the file names. However, all upper case characters are changed to lower case, spaces are converted to underscores, and all symbols are removed. 

Importing CSV files to a database is a common task needed for data science and analytics and it can be done completely with python using pandas dataframes, numpy, os library.

