
# NoSQL Databases - Quiz


## Introduction

In this lesson, you'll answer some common open-ended interview questions about NoSQL databases.


## Question 1

What is the difference between a NoSQL and a SQL database?  Which is better?

Write your answer below this line: 
_________________________________________________________________________________________________________________

NoSQL is better for handling data that doesn't fit the 'regular' or consistent structure in say size or type that is necessary for SQL which is a relational database. For example if you have a column for messages but some entries are 5 messages, and some entries are only 1 message, it's hard to work with this in SQL.






## Question 2

Describe a situation where a NoSQL database might be a better choice than a relational database, and explain your reasoning.

Write your answer below this line: 
_________________________________________________________________________________________________________________See above answer





## Question 3

How does MongoDB work? How is it different from a relational database?

Write your answer below this line: 
_________________________________________________________________________________________________________________

MongoDB uses document stores which are key-value pairs. Documents can be arbitrarily long and the documents don't have to use the same keys. This is different from a relational database where entries have to use the same keys (i.e. columns/column names).







## Question 4

What is fault tolerance, and what does it have to do with Resilient Distributed Datasets?

Write your answer below this line: 
_________________________________________________________________________________________________________________
Fault tolerance is the ability to withstand a disruption of service if a server goes down, i.e. minimizing loss of data. Similar to a R.A.I.D. array system that's used for computer hard drives, fault tolerance for databases uses redundant sets of data spread across multiple servers so that if one server goes down while we're running a query (or before) we don't miss out on data.





## Question 5

What is MapReduce? How is it related to Hadoop?

Write your answer below this line: 
_________________________________________________________________________________________________________________

MapReduce is a way of optimizing/speeding up a query/ making it more efficient by splitting the query up across multiple servers so that each server is running the same query over a smaller subset of data, (this is the mapping part) then aggregating all the results together (the reduce part). Hadoop is a platform that supports an RDD (resilient distributed dataset) such as MapReduce. Spark is built on top of Hadoop and allows users a cleaner, faster way of dealing with distributed datasets. 


## Summary


In this lesson, we reviewed some common NoSQL interview questions. 
