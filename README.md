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

    In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

    - The summary states whether or not there is bias, and the results support this (2 pt)
    - An additional analysis is recommended to support the statement (2 pt)

