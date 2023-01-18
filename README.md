# Amazon_Vine_Analysis

## Overview
### Purpose
The purpose of this project is to examine Vine, the paid review program by Amazon and determine if the paid reviews promote bias. We seek to answer the following questions:
1. How many Vine reviews and non-Vine reviews were there?
2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
To accomplish this task we used a combination of pgAdmin & Amazon RDS to collect the data; then a google colab notebook was used to perform the analysis on the data.

## Results

#### 1. How many Vine reviews and non-Vine reviews were there?
In this dataset there were a total of 47 Vine Reviews and 8362 non-Vine reviews.

#### 2. How many Vine reviews were 5-stars? How many non-Vine reviews were 5-stars?
Of the 47 Vine reviews 15 were 5-star reviews & of the 8362 non-Vine reviews 4332 were 5-star reviews.

#### 3. What percentage of Vine reviews were 5-stars? What percentage of non-Vine reviews were 5-stars?
For this dataset 31.91% of Vine reviews were 5-star and 51.81% of non-Vine reviews were 5-star reviews.

![image](https://user-images.githubusercontent.com/70111980/213300225-c61fe06d-581e-4785-8aeb-28da2ed2dbce.png)


## Summary
From the dataset we can see that the paid Vine reviews were not skewed to indicate a positive bias. This is interesting, though it is important to note that we only looked at one data set. If the same analysis were performed across multiple data sets would our results still stand? Ideally we would find a dataset with a higher proportion of Vine participants as our data set had a small population of Vine participants. It is likely that we could expect some data sets to display positive bias for some paid reviews. 
