*Tags: Databricks, data engineering, python, SparkSQL*<br>
**Description:**
- Engineered data pipelines for fire calls in Databricks environment: from raw data stored on an AWS S3 and PostgreSQL JDBC to become machine learning models saved on the cloud and ready to be used on new data.
- Created a database and its tables on Hadoop Distributed File System (HDFS), using techniques such as parallel reads, predicate push down, file formats and schemas support to accelerate data loading speed. 
- Improved programs performance on a cluster of nodes by analyzing Spark UI and performing partition, cache, and broadcast settings.
- Tools used: *databricks, dbutils, AWS S3, sparkSQL, python, pyspark, numpy, pandas, sklearn, mlflow*

[**Notebooks:**](https://cmn0705.github.io/Fire_Calls_Data_Pipeline/#01.File%20system.html)

01.File system

02.Mount a remote storage

03.Creating database and tables from files

04.Creating unmanaged table

05.Read from JDBC PostgreSQL database

06.Query database

07.Speed up

08.Write table to a file

09.Download a file from Databricks storage

10.Predict fire calls time delay

11.Predict fire call groups