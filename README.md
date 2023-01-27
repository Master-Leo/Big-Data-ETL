# Big-Data-ETL
 
 ## Introduction
> Implemented various ETL techniques on Amazon's shoppers product reviews. A single dataset alone contained over 1.5 million rows with various 40 meta-data links. My goal was to perform ETL processing in the cloud and upload a structured DataFrame to an RDS instance. Second goal was to utilize PySpark and SQL to perform a statistical analysis on the selected data.
 
 - This mini-project is split into two sections: 
  1. Extract two Amazon customer review datasets, transforming into 4 final DataFrames        and loading onto AWS cloud. 
  2. Extract two Amazon review datasets and use SQL and PySpark to analyze whether            reviews from Amazon's Vine program are trustworth. 
  
 ## Part 1
 Extract the Data:<br>
 - Read in each dataset with correct header and parameters
 - Calculated the shape of the dataset
 
 Transform the Data: <br>
 - Created a review_df with appropriate columns and data types
 - Created a product_df with dropped duplicates in both columns
 - Created a customer_df that grouped data on 'customer_id' by the # of times a customer reviewed a product 
 - Created a vine_df with the necessary aggregated columns
 
 Load the Data into an RDS Instance<br>
 - Exported into postgreSql server wtih the necessary tables for analyzes 
 
 ## Part 2 
 > I explored various methods to investigate whether Vine reviews were free of bias. Implemented PySpark and SQL to analyze the data
<br>
1. For analysis, I considered steps to reducing noisy data by filtering reviews by certain criteria

## Summary:



