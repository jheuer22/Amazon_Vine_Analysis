# Amazon_Vine_Analysis

# Overview of the analysis:
In this project we analyzed Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. In this analysis we used Amazon Web Services (AWS) to access and perform ETL (Extract, Transform, Load) and create usable subests of the original data on Kitchen applicances purchased through the Vine program. We then used one of these smaller, cleaned datasets to determine whether the reviews from the Vine participants had a relatively higher percentage of 5 star reviews than the those from non-Vine participants who purchased the items. 

# Results: 
After the ETL process was completed with PySpark on AWS, I used Pandas to read in the Vine_Table dataset csv. 

### How many Vine reviews and non-Vine reviews were there?

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


# Summary:
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

