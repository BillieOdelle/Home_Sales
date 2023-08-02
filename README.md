# Home_Sales
Module 22 

Using SparkSQL to determine key metrics about home sales data. 

We used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

We used this dataset to answer the following questions:

1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

In addition; we established the run time it took to run the data that was

1. Non cached
2. Cached and 
3. partitioningby 'date built' on a formatted parquet version of the homes sales data.

There was about a .01 to .03 second difference for each refresh.

To use this code you would need to copy it into a decent machine learning system.  For this activity we used Community Databricks.

You will need to create your own account (Community Databricks is free to use)