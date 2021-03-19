# ETL-COVID-Udemy-Data

In this analysis, I extracted COVID and Udemy Course CSV datasets from Kaggle and used Pandas to read the two files. I only extracted the columns that I needed and created a copy for the next steps. Using SQL, I created my two tables and added the associated columns (unrelational as my dataset did not have unique keys). Then I established a connection between SQL and my datasets, and loaded my data into pgAdmin. 

To recreate the process, import pandas and sqlalchemy and read the csv files "us_counties_covid.csv" and "udemy_courses.csv". Then log into pgAdmin and input the 'Load into pgAdmin' code in the query, and establish a connection in Jupyter Notebook - input your password in the {insert PW} section. Then, run the last three lines of code to retrieve table names and load the two CSV files into pgAdmin. 

With the datasets, I hope to explore the educational platform usages in relations to COVID statistics such as number of COVID cases. In addition, it'd be interesting to research which courses (Business Finance, Web Development, etc.) are most popular during the pandemic which can be analyzed using the subject and number of subscribers data in Udemy. If time allows, I'd also like to research how current events affect people's learning trends (e.g. election, economic activities, etc.)
