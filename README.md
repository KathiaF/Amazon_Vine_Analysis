# Amazon_Vine_Analysis
Challenge 16

## Project Overview
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. And since SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review, the company's shareholders have an interest in knowing the result of the analysis of beauty product reviews.

## Resources
Data Source: amazon_reviews_us_Beauty_v1_00
- Google Colab Notebooks, Python 3.9.0, PySpark
- ProsgreSQL, PGAdmin
- Amazon Web Services (AWS)

## Results
### Deliverable 1: Perform ETL on Amazon Product Reviews

- customers_table

| Google Colab Notebooks | PgAdmin |
| --- | --- |
| <img src="/Resources/img1.png"> | <img src="/Resources/img2.png"> | 

- products_table

| Google Colab Notebooks | PgAdmin |
| --- | --- |
| <img src="/Resources/img3.png"> | <img src="/Resources/img4.png"> | 

- review_id_table

| Google Colab Notebooks | PgAdmin |
| --- | --- |
| <img src="/Resources/img5.png"> | <img src="/Resources/img6.png"> | 

- vine_table 

| Google Colab Notebooks | PgAdmin |
| --- | --- |
| <img src="/Resources/img7.png"> | <img src="/Resources/img8.png"> | 


### Deliverable 2 & 3: Determine Bias of Vine Reviews

- How many Vine reviews and non-Vine reviews were there? 74,760
  - Vine reviews: 647
  - non-Vine reviews: 74,113
  
- Number of Vine 5-star reviews: 229
- Number of Non-Vine 5-star reviews: 43,217

- What percentage of Vine reviews were 5 stars? 35.39%
- What percentage of non-Vine reviews were 5 stars? 58.31%

### Summary
Out of a total of 74,760 reviews in the beauty dataset 99.13% were non Vine members and only 645 were paid reviews. It can also be seen that the reviews of the of the Vine members are not biased, since the percentage that gives 5 stars to the products is only 35.39%, which shows us that they are more critical in their reviews.

To support this conclusion, it is recommended to perform this analysis on another dataset and look at the distribution of all star rating reviews, to find out if the Vine members tend to write neutral or bad reviews.



