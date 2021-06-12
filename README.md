# Amazon_Vine_Analysis

## Overview
Using  knowledge of the cloud ETL process, I created an AWS RDS database with tables in pgAdmin. I picked a dataset from the Amazon Review datasets and extract the dataset into a DataFrame. I transformed the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, uploaded the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded.

# Results
 - How many Vine reviews and non-Vine reviews were there?

According to the images there was a total number of 94 Vine reviews and 40,472 non-Vine reviews.

![image](https://user-images.githubusercontent.com/49353083/121790849-d64db980-cbb1-11eb-98bd-500d47f61aa9.png)
![image](https://user-images.githubusercontent.com/49353083/121790846-c59d4380-cbb1-11eb-8255-1900d20abe04.png)


 - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

According to the image above, there were 48 5-star paid reviews and 15,663 5-star unpaid reviews.

 - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

According to the image above, the percentage of the Vine reviews that were 5-star paid reviews is 51.06%. The percentage of the non-Vine reviews that were 5-star paid reviews is 38.7%.

## Summary

According to the data, there is positivity bias for the reviews in the Vine program. There is a higher percentage in 5-star reviews (51.06%) compared to non-Vine reviews (38.7%). Although the sample amount is significantly smaller for the paid reviews, it does show a higher rating in 5 star reviews. Another analysis that could be done is to prove this positivity bias is by comparing all the 1, 2, 3, and 4-star reviews, paid and unpaid. This can show if there higher reviews in the paid Vine reviews.
