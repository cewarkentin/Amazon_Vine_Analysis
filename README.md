# Amazon_Vine_Analysis

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

Looking at data for items labeled as "musical instruments" sold on Amazon, we determined if there was any bias toward favorable reviews from Vine members within dataset.

## Results

Below are the results comparing item reviews based on whether or not the reviews were completed by Amazon Vine members.

![paid_summary](https://github.com/cewarkentin/Amazon_Vine_Analysis/blob/main/paid_summary.png)
![unpaid_summary](https://github.com/cewarkentin/Amazon_Vine_Analysis/blob/main/unpaid_summary.png)

- For items labeled as "musical instruments" sold on Amazon, there were 60 reviews from Amazon Vine members and 14,477 reviews from non-Vine members.
- From the reviews by Amazon Vine members, 34 reviews were 5-star reviews. From the reviews by non-Vine members, 8,212 reviews were 5-star reviews.
- 56.67% of Amazon Vine members gave 5-star reviews for the items labeled as "musical instruments" sold on Amazon. 56.72% of non-Vine members gave 5-star reviews for the items labeled as "musical instruments" sold on Amazon. 

## Summary

There is not any positivity bias for reviews from members of the Amazon Vine program-- for the selected data, 56.67% of reviews from Vine members gave 5-stars, which is close to the 56.72% 5-star reviews from non-Vine members.

It would be interesting to compare the Vine reviews versus non-Vine reviews for each star level to see if the average star scores for the products illustrate any bias (i.e. Amazon Vine members are more likely to give reviews with a higher overall average score compared to non-Vine members).
