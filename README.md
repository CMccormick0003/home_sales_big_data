# home_sales_big_data

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Before You Begin
Create a new repository for this project called, Home_Sales. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Push your changes to GitHub.

Files
Download the following files to help you get started:

Module 22 Challenge filesLinks to an external site.

Instructions
Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

Import the necessary PySpark SQL functions for this assignment.

Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

Create a temporary table called home_sales.

Answer the following questions using SparkSQL:

### What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
$ 299661.01

### What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
![image](https://github.com/CMccormick0003/home_sales_big_data/assets/120672518/47561212-16ed-4bd9-9a84-8691f27379b3)

### What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
![image](https://github.com/CMccormick0003/home_sales_big_data/assets/120672518/21ca698a-48d9-4e21-aeba-66799df9f3ac)

### What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
![image](https://github.com/CMccormick0003/home_sales_big_data/assets/120672518/9bcea424-2451-4e2e-9485-db0da08a8f30)

Cache your temporary table home_sales.

Check if your temporary table is cached.

Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Partition by the "date_built" field on the formatted parquet home sales data.

Create a temporary table for the parquet data.

Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncache the home_sales temporary table.

Verify that the home_sales temporary table is uncached using PySpark.

Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.
