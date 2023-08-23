# home-sales

Spark sql notebook for querying home prices in google colab.

Read in and download spark packages.

Create spark session.

Read in data from following url:
"https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv"

Create a temporary view of the data and then initate the following queries:
1. What is the average price for a four bedroom house sold in each year rounded to two decimal places?

2. What is the average price of a home for each year the home was built that have 3 bedrooms and 3 bathrooms rounded to two decimal places?

3. What is the average price of a home for each year built that have 3 bedrooms, 3 bathrooms, with two floors, and are greater than or equal to 2,000 square feet rounded to two decimal places? ** Create a run time 

Cache the table temporary tables "home_sales"

Using the cached data run query 3 again wtih run time


Partition the data by "date_built" and use parquet formatting. 
    - Read in parquet data
    - Create temporary table for parquet data
    - Run query 3 again with run time
Uncache the temp table and double check that it is no longer cached.






