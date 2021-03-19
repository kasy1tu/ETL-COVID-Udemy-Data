# ETL-COVID-Udemy-Data

In this analysis, I extracted COVID and Udemy Course CSV datasets from Kaggle and used Pandas to read the two files. I only extracted the columns that I needed and created a copy for the next steps. Using SQL, I created my two tables and added the associated columns (unrelational as my dataset did not have unique keys). Then I established a connection between SQL and my datasets, and loaded my data into pgAdmin. 

To recreate the process, import pandas and sqlalchemy and read the csv files "us_counties_covid.csv" and "udemy_courses.csv". Then log into pgAdmin and input the 'Load into pgAdmin' code in the query, and establish a connection in Jupyter Notebook - input your password in the {insert PW} section. 

Then, run the last three lines of code to retrieve table names and load the two CSV files into pgAdmin. 

With more research and time, I hope to learn more about education/learning services usage in relation to COVID levels. 
