## Project Goals:
- Gain practical experience with a NoSQL system data management system and communicate what we learned.
- Utilize MongoDB (Azure Cosmos DB) as the main data storage solution and query the same MongoDB database using PySpark, within Databricks.
- Establish connectivity using the MongoDB-PySpark connector to facilitate seamless integration between MongoDB and PySpark.
- Directly query data from MongoDB, using PyMongo, and conduct performance testing of the queries executed in both Spark and PyMongo.

## Dataset Description:
For this project, we decided to use the AirBnB dataset, which can be found here: http://insideairbnb.com/get-the-data.html.
We selected 4 cities: Los Angeles, CA, Portland, OR, Salem, OR, and San Diego, CA. Each city has 4 files: listings.csv, calendar.csv, reviews.csv, and neighborhoods.csv.

## Dataset Specific Questions:
1) Display list of stays in Portland, OR with details: name, neighbourhood, room type, how many guests it accommodates, property type and amenities, per night’s cost and is available for the next two days in descending order of rating.
2) Are there any neighbourhoods in any of the cities that don’t have any listings? (Executed both on PySpark and PyMongo)
3) For “Entire home/apt” type listings in Portland provide it’s availability estimate for each month of Spring and Winter this year.
4) For each city, how many reviews are received for December of each year?
5) Retrieve host-related information and calculate the percentage of five-star listings for each host, based on the total number of listings. Provides insights into host performance and the proportion of highly rated listings they have.
