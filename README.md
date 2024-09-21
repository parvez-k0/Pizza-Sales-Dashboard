# Pizza Sales Report Analysis

## Situation

This is a dynamic dashboard that provides insights on top and bottom performing pizzas by revenue, quantity, and total order.

- The dashboard helps business owners make data-driven decisions and take appropriate actions.
- Filters are available to view specific pizza categories.
- The project also includes steps to import data into MS SQL Server, create a database, and write SQL queries.
- A report is created from the SQL Server queries to support the Power BI reports.

## Task

Find the top five best-selling pizzas by revenue and quantity

- Use revenue, quantity, and total orders as measures to identify the best-selling pizzas
- Focus on the top five pizzas and offer discounts to attract more customers
- Also find the bottom five worst-selling pizzas to identify underperforming options
- Consider removing those options and make market decisions
- Use MS Office Excel 2019, MS SQL Server 19.0

## Action

Importing CSV data into MS SQL Server

- Open SQL Server Management Studio and connect to the server
- Create a new database for Pizza sales
- Import the CSV file into the database
- Modify the data types of columns if necessary

Create a document for each SQL query and save the results.

- Query 1: Find total revenue
- Query 2: Determine average order value
- Query 3: Calculate total quantity of pizzas sold

Total orders placed are 21,350 and average pizzas per order is 2.32.

- To find the total orders placed, we take the distinct count of the order ID column.
- To calculate average pizzas per order, we divide the total number of pizzas sold by the total number of orders.

Calculate the total sales percentage of Pizza category

- Group the data by Pizza category and calculate the sum of total_price as numerator
- Divide the numerator by the total sales value and multiply by 100 to get the percentage


## Result

Insights about sales performance and busiest days

- The orders are highest on Fridays, Saturdays, and Thursdays.
- In terms of months, the highest orders are in July, January, and March.
- There is a trend of lower orders during winter seasons.

Top five best sellers by revenue and quantity are calculated using a filter panel and a bar chart

- Apply filter to show only top five sellers
- Use revenue to sort and display the data
- Use total pizza sold to sort and display the data

## Reflection

This project taught me the importance of using data visualization tools to communicate complex information in a clear and concise manner. It also highlighted the importance of collaboration and teamwork in achieving project goals. In the future, I would focus on incorporating more real-time data sources and improving the dashboard's usability.
