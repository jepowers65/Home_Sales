# Home_Sales - Big Data Challenge

#### In this challenge I used my knowledge of SparkSQL to determine key metrics about home sales data. I use Spark to create temporary views, partion the data, cache and uncache the temporary tables, and verify that the table was cached, and uncached.

## Methods

- Upload the starter files and rename as Home_Sales_ipynb
- Import the necessary PySpark SQL Functions
- Create temporary tables called home sales

* Then I answered the following questions using the data:

  - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

  - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

  - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

  - What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

* Cache your temporary table home_sales.

* Check if your temporary table is cached.

* Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* Partition by the "date_built" field on the formatted parquet home sales data.

* Create a temporary table for the parquet data.

* Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* Uncache the home_sales temporary table.

* Verify that the home_sales temporary table is uncached using PySpark.
