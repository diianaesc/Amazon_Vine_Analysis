# Amazon_Vine_Analysis

## Overview of the analysis: 

The Amazon Vine program is a service that allows publishers to receive reviews for their books, when companies pay a small fee to Amazon and provide products to Vine members, these members are then required to publish a review.

In this project a dataset of book reviews written by members of the paid Amazon Vine program will be analyzed to determine if there is any bias toward favorable reviews from Vine members 

## Results:

- How many Vine reviews and non-Vine reviews were there?
  - zero vine reviews vs 403,778 non-vine reviews 
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - zero reviews were vine reviews with 5 stars vs 242,868 were non-vine reviews with 5 stars
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 60% of non-vine reviews were 5 stars

<img width="992" alt="Screen Shot 2022-08-21 at 10 39 59 PM" src="https://user-images.githubusercontent.com/104380112/185831048-3d3f6fa1-939a-4702-9904-a56c0edd624d.png">


## Summary: 

The dataset only includes reviews with more than 20 votes and if they were at least 50% helpful. These narrowed down our results and excluded all vine reviews, which could suggest that paid reviews do not add much value to other readers. Therefore, there is no evidence to determine if there is any bias toward favorable reviews from Vine members.

For future analysis, the filters for total votes and helpful votes could be adjusted to include a larger number of reviews.
Also, we can compare the length of words between vine and non-vine reviews to determine who included more detail information and if this is correlated with total votes. 
