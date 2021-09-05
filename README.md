# Amazon_Vine_Analysis


## 1.	Overview of the analysis: Explain the purpose of this analysis.
  -	The purpose of this analysis is to select one dataset that contains reviews of specific product and perform the ETL process to transform the data, connect to an AWS RDS instance and load th transformed data into pgAdmin. Additionally, using PySpark, Pandas and SQL to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## 2.	Results: Using bulleted lists and images of DataFrames as support, address the following questions:
o	How many Vine reviews and non-Vine reviews were there?
  - There are 94 vine reviews and 40471 non-Vine reviews
   ![image](https://user-images.githubusercontent.com/83877498/132139633-84056a0a-9d27-4bbc-8516-94db5865735f.png)
   
   ![image](https://user-images.githubusercontent.com/83877498/132139637-09512044-24b6-4cd5-8d75-91e7ff3d61b1.png)

 o	How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There are 48 Vine reviews with 5 stars and 15663 non-Vine reviews with 5 stars.
  ![image](https://user-images.githubusercontent.com/83877498/132139657-03def35c-0d04-49b3-8dfe-f84dc952e01a.png)
 
 o	What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  Percentage of Vine reviews with 5 stars is 0.30551842658010314
  Percentage Non-Vine reviews with 5 stars is 99.6944815734199
  
  ![image](https://user-images.githubusercontent.com/83877498/132139680-6b82b370-495d-4515-b0bf-becf856d7634.png)

## 3.	Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

  - Based on the results of my analysis, despite being paid to write reviews, the percentage of Vine reviews that have 5 star ratings are only 30.6%.  This means that Vine reviews tend to be more critical of products and services, which also could mean that Vine reviewers are giving more in-depth analysis of such products and services.
  - One thing that would be useful is if we compared the % of people that find Vine reviews helpful to the % of people that find Nonvine reviews helpful.


 
 

