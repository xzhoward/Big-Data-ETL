# Big-Data-ETL

# Background

In this assignment, you will put your ETL skills to the test. Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. They are quite large and can exceed the capacity of local machines. One dataset alone contains over 1.5 million rows; with over 40 datasets, data analysis can be very demanding on the average local computer. Your first goal will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.

This Challenge contains two parts. Part 1 is required. Part 2 is optional but highly recommended to strengthen your new skills.

Part 1: Extract two Amazon customer review datasets, transform each dataset into four DataFrames, and load the DataFrames into an RDS instance.

Part 2: Extract two Amazon customer review datasets and use either SQL or PySpark to analyze whether reviews from Amazon's Vine program are trustworthy.

# Data Processing
1. Calculate totals
2. Calculate the rating component
3. Calculate the star rating component
4. Calculate the star rating composition for products with both rating types
5. Calculate the composition of votes for two types of reviews

# Conclusion
For the selected datasets, based on the number of reviews performed by Vine customers and the results listed in the findings, there were no significant differences indicating that Amazon's Vine program reviews were not reliable, but we must always treat it as part of being human. conditions for having implicit biases and this can be included when expressing opinions about a product.
