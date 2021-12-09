# Determining Bias of Vine Reviews

## Overview of the analysis:
Using PySpark and Pandas, we determined if there is any bias towards reviews that were written as part of the Vine program. For this analysis, we determined if having a paid Vine review makes any difference in the percentage of 5-star reviews.

## Results: 
[Results can be found here](./Resources/Results.png)

* How many Vine reviews and non-Vine reviews were there?
    * 341931 Total Reviews
    * 10415 Paid Reviews
    * 331516 Unpaid Reviews
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    * 3381 Paid Five Star Reviews
    * 150566 Unpaid Five Star Reviews
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    * 32.5% of paid reviews were five stars
    * 45.1% of unpaid reviews were five stars

## Summary:
Overall, there were more unpaid five star reviews than there were paid reviews. Even still, less than half of the reviews were five stars. here were 13% more five star reviews by unpaid reviews than there were paid ones. This may show that the paid reviewers were actually more critical of the software they were reviewing than those who were not paid. 