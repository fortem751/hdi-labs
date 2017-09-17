# HDInsight Labs

The following labs are currently available, before attempting any of the labs be sure you have followed the instructions in Lab Setup. When you are done with the labs, be sure to follow the instructions under Cleanup to delete your lab environment and avoid uneeded costs.

## Setup
[Lab Setup](Setup/Environment-Setup.md): Follow the steps in this section to setup your environment to complete the labs.

## Labs
[Lab 1](Labs/Lab01/Lab01.md): In the lab you will learn how to use Spark SQL (and PySpark) to batch process a 10GB text file dataset, quickly explore its content, identify issues with the data, clean and format the data and load it into a Hive table to support downstream analytics performed in the other labs.

[Lab 3](Labs/Lab03/Lab03.md): AdventureWorks would like to add a snazzy product recommendations feature to their website and email marketing campaigns that, for every user in their system, can recommend the top 10 products they might be interested in purchasing. Adventureworks has provided you with the tables for users, products and weblogs that contains all of the data you need. In this lab, you will train a recommendation model using Spark's built-in collaborative filtering alogrithm - Alternating Least Squares (ALS). Then you will use the model to pre-compute the user to product recommendation for every user and save this in a table. Then you will query from this table to quickly get the 10 product recommendations for a given user.

## Cleanup
[Lab Cleanup](Setup/Environment-Cleanup.md): When you are done with the labs be sure to follow these instructions to cleanup your Azure subscription and avoid unnecessary costs.
