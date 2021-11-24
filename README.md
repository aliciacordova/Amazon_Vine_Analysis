# Amazon_Vine_Analysis

## Overview

We have been asked to analyzed Amazon reviews written by members of the paid Amazon Vine program. We will need to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 

After some analysis on Amazon Vine program we need to determines if there is a bias toward favorable reviews from Vine members.

## DELIVERABLE #1 Perform ETL on Amazon Product Reviews

-Google Colab Notebook:

![M16df_reviews_vine](https://user-images.githubusercontent.com/87447639/143277639-34af1b13-5974-41a3-8157-8d29b6d2f1a9.PNG)


![M16df_customers_and_products](https://user-images.githubusercontent.com/87447639/143277642-7627c197-dc4f-4f35-aa6d-c8fdfd864550.PNG)

- PgAdmin: 

![M16Vine_table](https://user-images.githubusercontent.com/87447639/143277626-a93ebcc5-b782-46e5-a121-bf91869a9556.PNG)

![M16Review_id_table](https://user-images.githubusercontent.com/87447639/143277629-3308c6b6-593d-4de2-8a77-79fe82cf6d84.PNG)

![M16Products_table](https://user-images.githubusercontent.com/87447639/143277632-f1e2378e-2f32-4609-b381-a6869d72d07c.PNG)

![M16Customers_table](https://user-images.githubusercontent.com/87447639/143277635-75a94af7-1adb-48e9-878b-e37ac1a9c228.PNG)


## DELIVERABLE #2 Determine Bias of Vine Reviews

## Results

- Paid: 

![M16Paid_Vine](https://user-images.githubusercontent.com/87447639/143276942-57a4792d-029b-45ed-83ac-f1c8ce484f7a.PNG)

- Unpaid:

![M16Unpaid_Vine](https://user-images.githubusercontent.com/87447639/143276924-32c43c4f-1808-4114-b2f6-4755b40189f3.PNG)

### How many Vine reviews and non-Vine reviews were there?

- There were over 94 Paid reviews.

- There were over 40471 Unpaid reviews. 

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- There were over 48 Vine reviews with 5 stars.

- There were over 15663 non-Vine reviews with 5 stars.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- There were over 51%  Vine reviews with 5 stars.

- There were over 39% non-Vine reviews with 5 stars.

## Summary

In the analysis of the Vine program, we can see that 51% of the 5-star reviews were Paid reviews from Vine program, compared to 39% of the non-Vine unpaid reviews. So we can conclude that there is a positive bias for Paid reviews on the Vine program.

Other suggestions for analysis would be to determine the statistical distribution of the data to undestand and take others conclusion from the data. 
