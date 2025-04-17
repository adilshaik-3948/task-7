## Task_7

#  Sales Data Analysis with SQLite & Python

This project demonstrates how to use SQLite with Python to perform simple data analysis and generate visualizations using pandas and matplotlib.

##  Objective

Load sales data from a SQLite database
Run SQL queries to get:
Total quantity sold per product
Total revenue per product
Display results using print() and a basic bar chart


##  Dataset

The dataset is stored in a SQLite database file called sales_data.db, which contains a single table: sales.

### Sample Table Schema:
sql
CREATE TABLE sales (
    product TEXT,
    quantity INTEGER,
    price REAL
);
##  Tools Used

Python (with sqlite3, pandas, matplotlib )
SQLite (built-in with Python)
Jupyter Notebook (.ipynb)

## How It Works

1.Create and connect to the database
2.Insert sample sales data
3.Run SQL query to compute total quantity and revenue
4.Load query results into a pandas DataFrame
5.Print the DataFrame
6.Plot a bar chart of revenue by product using matplotlib


