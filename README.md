# RPG Data Engineering with Kafka, Flask, and Hadoop

- This repo contains files associated with my culminating project from the Fundamentals of Data Engineering course in the MIDS program at UC Berkeley. 

- The setup for this scenario is that I am a data scientist at a game development company in charge of processing and storing records of user actions. My company's latest mobile game has two events I'm interested in tracking: `buy a sword` & `join guild`. Each has metadata characterstic of such events (i.e., sword type, guild name, etc)

- I'll showcase how we can pull in event data with Kafka from the Flask API webserver running our mobile gaming app, use Spark to filter these events and land them in a Hadoop Distributed File System (HDFS), then use Hive and Presto to query the returned data and perform analysis on it. 

- The core of this repository and the instructions used to perform data processing are contained within Project_3.ipynb. The notebook primarily focuses on the filtering done with Spark, but there are also notes on how data is generated and how it moves through our data pipeline into HDFS and into a queryable table. The end of the notebook has some simple examples of analysis we can do with the data with Presto and Pandas. 






