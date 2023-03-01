
<h4>Create Database in hive </h4>

```
create database hive_class_b1;
```
<h4> If we have multiple databases and wants to select a particular DB, then use the following command </h4>

```
use hive_class_b1;
```
<h4> Create Internal table in Hive</h4>

```
create table department1                                                                                                           
    > (                                                                                                                                       
    > dept_id int,                                                                                                                            
    > dept_name string,                                                                                                                       
    > manager_id int,                                                                                                                         
    > salary int)                                                                                                                             
    > row format delimited                                                                                                                    
    > fields terminated by ','; 
```

<h4> Describe table </h4>

```
describe table department1;
```
<h4> Describe formatted table</h4>

```
describe formatted department1;
```
<br>
<img align="center" alt="hive_desc_formatted" width = 600 src="https://user-images.githubusercontent.com/88526990/221818124-2ca806f5-a1c9-4ecf-99b0-3eba6a7cee44.jpg"><br>



<br>
<h2> load data from local system into hive table </h2>

<img align="center" alt="load_file_into-HDFS" width = 600 src="https://user-images.githubusercontent.com/88526990/222089185-ba9e0c2c-b146-4f20-a5f7-07c4022ffb53.jpg"><br>

**we want to insert the data of department_data.csv into hive table, for that purpose use the following command.**



```
LOAD DATA LOCAL INPATH '/home/cloudera/Desktop/data/depart_data.csv' into table department_data;
```

<h4>Display column name of hive table </h4>

```
set hive.cli.print.header = true;
```





