# Sales Data Analysis using MySQL & Pandas

This project connects to a MySQL database containing sales records, runs an aggregated query to calculate the total quantity sold and total revenue for each product, 
loads the results into a Pandas DataFrame, and visualizes data using a simple bar chart. The SQL query groups data by product and calculates both `total_qty` and `revenue` (`SUM(quantity * price)`). 
Using Pandas, the query output is read directly from the MySQL connection and printed in tabular format. 
Finally, a bar chart is generated with products on the x-axis and revenue on the y-axis to provide a clear visual comparison of sales performance across different cities.

## Requirements
- Python 3.x
- Pandas
- Matplotlib
- mysql-connector-python (or any MySQL Python driver)
