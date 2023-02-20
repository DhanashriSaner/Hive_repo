# Hive_repo

<h3>What is Apache Hive?</h3>
Apache Hive is an open source data warehouse software for reading, writing and managing large data set files that are stored directly in either the Apache Hadoop Distributed File System (HDFS) or other data storage systems such as Apache HBase.<br>
Hive enables SQL developers to write Hive Query Language (HQL) statements that are similar to standard SQL statements for data query and analysis.<br>
It is designed to make MapReduce programming easier because we don’t have to know and write lengthy Java code. Instead, we can write queries more simply in HQL, and Hive can then create the map and reduce the functions.<br>
Hive is better suited for data warehousing tasks such as extract/transform/load (ETL), reporting and data analysis and includes tools that enable easy access to data via SQL.
<h3> Hive Architecture </h3>
<img align="center" alt="Architecture" width = 700 src="https://media.geeksforgeeks.org/wp-content/uploads/Untitled-drawing-4-3.png">










<h3>Questions</h3>
1) While installing Hive, which database is used by hive to maintain it's metadata?<br>
Ans: Apache Derby
<br>
2) What are limitations of Derby database with Hive?<br>
Ans: Only one Hive session could be open at a time.
<br>
If we try to start the second session it produces an error when it attempts to open a connection to the metastore.
