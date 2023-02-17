# Module 17 Challenge: Amazon_Vine_Analysis

## Overview of the analysis:
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.  The purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members in your dataset. We will be using a dataset of Amazon reviews for tools.  We will use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.  Finally we will use PySpark to analyze the pattern of five-star reviews to determine if there is any obvious bias toward favorable reviews from Vine(paid) members over Non-Vine(unpaid) members.


## Results:

- Total # of Reviews Analyzed: 285 Vine Reviews(Fig 3.) and 31,545 Non-Vine Reviews(Fig 4.)

- Total # of 5-Star Reviews:  163 Vine Reviews(Fig 3.) and 14,614 Non-Vine Reviews(Fig 4.)

- Percentage of Reviews that were 5-Star:  57.19% 0f Vine Reviews(Fig 3.) and 46.33% of Non-Vine Reviews(Fig 4.)


#### Fig 1. Vine Reviews DataFrame
![image](https://user-images.githubusercontent.com/114360511/217747461-479069a9-39ee-42c1-9842-934e2b576319.png)

#### Fig 2. Non-Vine Reviews DataFrame
![image](https://user-images.githubusercontent.com/114360511/217747724-e652a1ec-6c50-4978-9506-0a2dc2dbc859.png)

#### Fig 3. Vine Reviews Analysis
![image](https://user-images.githubusercontent.com/114360511/217747782-207f4ed1-9224-464c-8989-7cd816a2f5cb.png)

#### Fig 4. Non-Vine Reviews Analysis
![image](https://user-images.githubusercontent.com/114360511/217747869-8719f8fd-e293-4a50-ace2-d9bf0e2aa484.png)


## Summary: 
In summary, there does appear to be a positivity bias for reviews in the Vine program, as only ~57% of Vine reviews were 5-star rated, while only ~46% of Non-Vine reviews were 5-star rated.  The 11% difference between shows that when paid with free tools to review, Vine reviewers provide more 5-star reviews.  The only caution on this is the enormous imbalance in number of reviews analyzed, which means other small differences could account for large percentage swings.

An additional analysis on the tool review dataset that might lend support to the above summary conclusion would be to analyze the percentages of all star counts (1-5), to see if the trend continues for ratings of 4 stars and possibly reverse on the lower star counts (1-3).  Our original dataset provided the star count detail, not just 5-star or "other".



