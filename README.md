# SQL_scripting
This project leverages a dataset of Famous Paintings & Museums to explore various analytical questions using SQL queries.

📂 Project Overview
load_csv_files.py: A script to load CSV data into a PostgreSQL database.
Questions.txt: A list of SQL problems to solve using the dataset.
Solutions.txt: The SQL queries that solve the listed problems.
SQL Paintings Case Study - Questions.pdf: A PDF version of the problem statements.
🛠 Setup Guide
1. Database Setup
Install PostgreSQL and create a database called painting.
Update the conn_string in load_csv_files.py with your database credentials.
2. Load the Data
Place your dataset CSV files in the specified directory.
Run load_csv_files.py to import the data into your PostgreSQL database.
3. Run Queries
Use the SQL queries in Solutions.txt to analyze and gain insights from the data.
📊 SQL Problems Solved
✔ Find paintings that aren't displayed in any museum.
✔ Identify museums with no paintings.
✔ Compare asking price vs. regular price of paintings.
✔ Analyze the most and least popular painting styles.
✔ Identify museums open every day.
✔ Detect and remove duplicate records.
...and much more!

🔧 Key SQL Skills Used
This project covers various SQL techniques including:

JOINs, GROUP BY, WINDOW functions
RANK and aggregation functions
Modifying queries to uncover different business insights.
