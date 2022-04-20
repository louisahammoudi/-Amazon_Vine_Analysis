# Amazon_Vine_Analysis

## Overview of the analysis: 
 This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.
## Results: 
* How many Vine reviews and non-Vine reviews were there?
The global number of reviews is about 65 547, but a small number of then is paid, around 0.953 for 613 reviews. The large majority is unpaid for 64 934 reviews.
## Total number of reviews![Total number of reviews](https://user-images.githubusercontent.com/89410157/145908199-61c5798e-e81c-4bfb-9276-832f4692e222.png)

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
The number of 5 starts is around 46.915% for 30 752 reviews.
## Number of Five Stars reviews ![Number of Five Stars reviews](https://user-images.githubusercontent.com/89410157/145913706-4c47c7c7-b9ce-43f9-bd84-4c3bdc97bcc7.png)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Out of the 613 paid reviews 222 are 5 starts for 36.215%, and regarding the 64 934 unpaid reviews 52.983% are 5 starts for 34 404 reviews.

## Percentage of 5 stars ![Percentage of 5 stars](https://user-images.githubusercontent.com/89410157/145913992-4b394a49-0792-4b08-bc55-acaaf0864e66.png)

## Summary: 
Comparing the percentage of reviews that were 5 stars from both Amazon Vine members and not Amazon Vine members, it can be concluded that there is no positivity bias for reviews of Office Products in the Vine program. The percentage of five-star reviews from both groups are nearly the same, rounded to 44%. A similar analysis could be conducted to compare the one-star or low reviews from both Vine and non-Vine members to further support this conclusion.

