# Udacity-Projects: SF Crime Statistics with Spark Streaming
Project Overview:-
In this project, you will be provided with a real-world dataset, extracted from Kaggle, on San Francisco crime incidents, and you will provide statistical analyses of the data using Apache Spark Structured Streaming. You will draw on the skills and knowledge you've learned in this course to create a Kafka server to produce data, and ingest data through Spark Structured Streaming.

1. How did changing values on the SparkSession property parameters affect the throughput and latency of the data?
  The higher number we get on processedRowsPerSecond, we could process more rows in second, which means higher throughput.

2. What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal?

 Properties improving the performance have more importances according to my understanding which are below.
  spark.sql.shuffle.partitions
  spark.default.parallelism

I have to explore more on other properties and can update the list accordingly
