# E-commerce Sales Analysis using SQL and Python

## Description :

This project analyzes e-commerce sales data using SQL and Python. Data from six CSV files was imported into MySQL, and queries were written to explore customer behavior, product performance, and sales trends. Python was used for executing SQL queries, data processing, and creating visualizations. The project covers basic to advanced analysis, including revenue trends, customer retention, and category-wise sales insights, helping uncover data-driven business decisions.

## Objective:

The primary objective of this project is to analyze sales performance, customer behavior, and product trends in an e-commerce platform using SQL for data querying and Python for data manipulation and visualization. The goal is to extract actionable insights that can drive better business decisions related to marketing, inventory, and customer retention.


## Process:

1. **Data Importation:**

   * Created a Python script to import multiple `.csv` files into a MySQL database.
   * Six key tables (e.g., customers, orders, order\_items, products, payments, sellers) were imported.

2. **Library Setup:**

   * Imported essential Python libraries: `pandas`, `matplotlib`, and `seaborn` for data manipulation and visualization.

3. **SQL Integration:**

   * Connected MySQL to Python using `mysql.connector`.
   * Executed queries directly from Python to retrieve and analyze the data.

4. **Query Execution:**

   * Wrote and executed a variety of SQL queries ranging from basic aggregations to advanced analytics.
   * Data was fetched using Python and further processed if needed.

5. **Data Analysis & Visualization:**

   * Transformed SQL query results into DataFrames using `pandas`.
   * Created visualizations (bar charts, line plots, etc.) using `matplotlib` and `seaborn` where appropriate.


## Key Insights:

## Basic Queries:

* Identified unique customer cities and state-wise distribution.
* Found a total number of orders in 2017 and the categories generating the most sales.
* Determined that a small percentage of customers paid in installments.

## Intermediate Queries:

* Monthly order trends for 2018 revealed peak sales months.
* Average products per order varied significantly across cities.
* Product categories showed unequal revenue contributions — top categories were clear revenue drivers.
* The correlation between price and number of purchases was found to be weak (approx. -0.11), indicating **price does not strongly affect purchase frequency**.
* Seller-wise revenue ranking helped identify top-performing sellers.

## Advanced Queries:

* Moving averages helped observe order value trends per customer over time.
* Cumulative monthly sales provided year-wise growth visibility.
* Year-over-year growth rates were calculated to measure business performance.
* Customer retention rates highlighted gaps in long-term engagement.
* Top spenders per year were identified for potential loyalty targeting.

## Conclusion:

This project successfully demonstrates how SQL and Python can be combined to carry out a comprehensive analysis of an e-commerce platform. Using real-world transactional data, we answered both business and analytical questions ranging from simple counts to customer retention and revenue contribution.

The insights generated provide a foundation for data-driven decision-making in areas such as:

* Product pricing and inventory planning,
* Sales strategy optimization,
* Customer segmentation and retention.

Overall, this project showcases the power of data analytics in understanding business performance and unlocking growth opportunities through structured query processing and effective data visualization.

