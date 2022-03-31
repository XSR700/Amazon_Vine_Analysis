# Amazon_Vine_Analysis

## Overview of the analysis:

In this project I analyzed Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

I had access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I picked one of these datasets and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used Pandas to determine if there is any bias toward favorable reviews from Vine members in my dataset. Then, I wrrote a summary of the analysis to submit to the SellBy stakeholders.
