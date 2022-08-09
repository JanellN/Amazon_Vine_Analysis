# Amazon_Vine_Analysis

![images](https://user-images.githubusercontent.com/103154070/183733026-60dc9caa-a0b3-472d-824f-6f4e34dd10f0.png)

## Overview 

Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Results 
<img width="513" alt="review totals " src="https://user-images.githubusercontent.com/103154070/183733057-f776cee9-f296-40f5-b14c-4c5c30bbafaa.png">

- There were a total of 1,080 Vine reviews and 49,659 non-vine reviews 

- There were 454 5-Star vine reviews; There were 23,034 non-vine 5-star reviews

- 42.04% of the total vine reviews were 5-Star reviews; 46.34% of the total non-vine reviews were 5-star reviews 

## Summary 
From the results it is notices that the percentage of 5 star reviews for Vine and Non-Vine reviewers are very close; with a 4.40 percentage difference.  This tells us that the paid reviewers were pretty much in line with the non paid reviewers for these producgts, concluding that there does not appear to be a bias on the reviews provided by vine reviewers,  To create a more accruate analysis, it would be hlepful to conduct the analysis on more categories and compare results.
