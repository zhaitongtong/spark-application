Spark learning practice.

Technologies: Apache Spark, Spark SQL, Spark Streaming

Application: 
1. Log Analyzer
  - Reads in new log files from a directory and inputs those new files into Spark Streaming
  - Compute stats on the logs
  - Write the calculated stats to an html file
2. Twitter Streaming Language Classifier
  - Collect a dataset of Tweets and write them out to files using Spark Streaming
  - Examine the dataset of Tweets using Spark SQL
  - Train a model by applying the k-means algorithm using Spark MLLib 
  - Filter a live stream of Tweets for those that match the specified cluster
3. Weather TimeSeries
