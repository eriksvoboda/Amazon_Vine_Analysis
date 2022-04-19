# Amazon Vine Analysis

## Purpose

The purpose of this project is to chose one dataset from the Amazon Vine program and use PySpark to perform the ETL process. Then using either SQL or PySpark determine if there is any bias toward favorable reviews from the Vine memebers in the dataset. 

## Results

### How many Vine reviews and non-Vine reviews were there?
- There are 94 Vine reviews and 40471 non-Vine reviews.

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- There are 48 5 star Vine reviews and 15663 non-Vine 5 star reviews.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 51.06% of Vine reviews were 5 star reviews. 38.70% of non-Vine reviews were 5 star reviews.vine  

![](/vine_non_vine_reviews.png)

## Summary

Since half of the Vine reviews are 5 star reviews, there is reason to say there is positivity bias in the Vine program. In order to gather more data with the same dataset we could not filter the data for reviews with 20 or more votes. By using all of the reviews available we could see if the perccentage of 5 star reivews increases or decreases to confirm if there is positivity bias amoung the whole dataset. 
