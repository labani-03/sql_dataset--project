# sql_dataset--project

Here's a simple summary and implementation plan to get basic sales summary from a tiny SQLite database using Python:


Project Summary: Basic Sales Summary with SQLite and Python

Objective:

Use SQL within Python to:

Get total quantity sold and total revenue for each product.

Display results using:

Print statements

A basic bar chart (using matplotlib)


Tools Required:

Python (with sqlite3, pandas, and matplotlib)

SQLite (built-in with Python)

Jupyter Notebook or .py file


Dataset

A small SQLite database file named sales_data.db with one table:

Table name: sales

Columns:

- product (TEXT)
  
- quantity (INTEGER)
  
- price (REAL)
  
- sale_date (TEXT)


Output

Text summary of total quantity and revenue per product.

A bar chart visualizing revenue by product.



