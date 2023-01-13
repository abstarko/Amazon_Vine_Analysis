# Amazon_Vine_Analysis

## Project Overview 

Using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then using SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. This was all done from using the Major Appliances dataset from Amazon.

## Results
When looking at the results of the Major Appliances I was able to see the following from review types.

Helpful: 4,992 total reviews - 1,981 5 Star Reviews at 39.68%
Paid Vine: 35 total reviews - 18 5 Star Reviews at 51.43%
Unpaid Non-Paid: 4,957 total reviews - 1,963 5 Star Reviews at 39.60%

## Summary
Looking at the percentages it would seem like there is a bias towards Paid Vine, but it is almost impossible to really determine that considering there is such a small number of total reviews. If we were to get the mean percentages we might have a better idea of a more accurate bias with this dataset. 
