# Descriptive Analysis Integrating PostgreSQL and Python
- Date: 1 November 2024
- Author: Subaru Shimizu

**Overview:**  
  
This work performs descriptive analyses using PostgreSQL and Python with [a sample database about DVD rentals provided by Neon, Inc](https://neon.tech/postgresql/postgresql-getting-started/postgresql-sample-database). The integration of PostgreSQL and Python allows for efficient data manipulation to address various business queries.

[JupyterNotebook](https://github.com/subaru3577/05-PostgreSQL-Python/blob/main/PostgreSQL_descriptive_analysis.ipynb) is available.


**Queries**
- Q1: What is the most common film category?
- Q2: Summarise the number of films each actor has acted in by film category.
- Q3: Search for films whose titles contain "Christmas".
- Q4: Search for films whose description contains "dog".
- Q5: Create a table of rentals that includes overdue information.
- Q6: What are the first and last rental dates in the database?
- Q7: What is the average overdue duration (days) within 60 days from 2005-06-01?
- Q8: Create a rental table ranked by actual rented durations for each rental week.
- Q9: Create a rental table showing the moving average of actual rental durations.

**Used SQL Techniques:**  
- JOIN
- Aggregations
- Sorting and Grouping
- Common Table Expressions (CTE)
- CASE
- Window Functions
- Date/time Functions
- Full-text Search
