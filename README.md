# Amazon_Vine_Analysis
Use of SQL and PySpark to analyze Amazon reviews of pet products

# Overview:
The purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members in the Amazon Reviews of US Pet Products dataset for Amazon Vine.

# Results: Using bulleted lists and images of DataFrames as support,
### Vine Reviews
![Paid Results](https://github.com/marhanlang/Amazon_Vine_Analysis/blob/main/Paidresults.png)
### Non-Vine Reviews
![Unpaid Results](https://github.com/marhanlang/Amazon_Vine_Analysis/blob/main/Unpaidresults.png)
- How many Vine reviews and non-Vine reviews were there?
  - There were 170 Vine reviews.
  - There were 37,840 non-Vine reviews.
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There were 65 Vine reviews that were 5 stars.
  - There were 20,612 non-Vine reviews tht were 5 stars.
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 38.24 percent of Vine reviews were 5 stars.
  - 54.47 percent of non-Vine reviews were 5 stars.

# Summary: 
There is likely a positivity bias for reviews in the Vine program. Despite the delivered analysis showing a larger percentage of 5 star reviews among non-Vine reviews, running additional analyses show that there is a much smaller percentage of negative reviews amongst Vine reviews than non-Vine reviews. 

One additional analysis of the dataset that supports the existence of a positivity bias involves reworking the code used to find number and percent of 5-star reviews for the paid and unpaid reviews dataframes to find number and percent of 1-star reviews. This analysis must be included to show the full spectrum of positivity bias in the dataset. Not all positivity bias presents as an increase in 5-star reviews and can instead present as a lack of negative reviews. The image below shows that one star reviews are far more common among non-Vine reviews and supports the theory that Vine-reviews are subject to at least a minimal positivity bias. 

![One-Star Results](https://github.com/marhanlang/Amazon_Vine_Analysis/blob/main/oneStarResults.png)
