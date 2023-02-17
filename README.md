# Module 17 Challenge: Amazon_Vine_Analysis

## Overview of the analysis:
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.  The purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members in your dataset. We will be using a dataset of Amazon reviews for tools.  We will use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.  Finally we will use PySpark to analyze the pattern of five-star reviews to determine if there is any obvious bias toward favorable reviews from Vine(paid) members over Non-Vine(unpaid) members.


## Results:

    Using bulleted lists and images of DataFrames as support, address the following questions:

        - How many Vine reviews and non-Vine reviews were there?
        - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
        - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews  
             were 5 stars?

    There is a bulleted list that addresses the three questions for unpaid and paid program reviews (7 pt)

#### Vine Reviews DataFrame
![image](https://user-images.githubusercontent.com/114360511/217747461-479069a9-39ee-42c1-9842-934e2b576319.png)

#### Non-Vine Reviews DataFrame
![image](https://user-images.githubusercontent.com/114360511/217747724-e652a1ec-6c50-4978-9506-0a2dc2dbc859.png)

#### Vine Reviews Analysis
![image](https://user-images.githubusercontent.com/114360511/217747782-207f4ed1-9224-464c-8989-7cd816a2f5cb.png)

#### Non-Vine Reviews Analysis
![image](https://user-images.githubusercontent.com/114360511/217747869-8719f8fd-e293-4a50-ace2-d9bf0e2aa484.png)


## Summary: 

    In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

    - The summary states whether or not there is bias, and the results support this (2 pt)
    - An additional analysis is recommended to support the statement (2 pt)

