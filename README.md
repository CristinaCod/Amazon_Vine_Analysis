# Amazon Vine Analysis
## Overview
### Purpose

For the purpose of this project I chose to focus on the Video Game reviews information provided by Amazon.

A snapshot of the original video game dataframe is provided below. However, please note this is not the entire dataframe and a few columns are missing from the end as they did not all fit on the screen.

![df.png](https://github.com/CristinaCod/Amazon_Vine_Analysis/blob/main/Resources/Screen%20Shot%202022-04-01%20at%202.52.18%20PM.png)

## Results
The results for Video Games Vine vs non-Vine reviews are as follows:

o	How many Vine reviews there were -- 94

![paid.png](https://github.com/CristinaCod/Amazon_Vine_Analysis/blob/main/Resources/Screen%20Shot%202022-04-01%20at%202.27.45%20PM.png)

o	How many non-Vine reviews there were -– 40,471

![unpaid.png](https://github.com/CristinaCod/Amazon_Vine_Analysis/blob/main/Resources/Screen%20Shot%202022-04-01%20at%202.28.53%20PM.png)

o	How many Vine reviews were 5 stars -- 48

![paid_count.png](https://github.com/CristinaCod/Amazon_Vine_Analysis/blob/main/Resources/Screen%20Shot%202022-04-01%20at%202.28.15%20PM.png)

o	How many non-Vine reviews were 5 stars -— 15,663

![unpaid_count.png](https://github.com/CristinaCod/Amazon_Vine_Analysis/blob/main/Resources/Screen%20Shot%202022-04-01%20at%202.29.11%20PM.png)

o	What percentage of Vine reviews were 5 stars -– 51.06%

![paid_five.png](https://github.com/CristinaCod/Amazon_Vine_Analysis/blob/main/Resources/Screen%20Shot%202022-04-01%20at%202.28.33%20PM.png)

o	What percentage of non-Vine reviews were 5 stars -- 38.7%

![unpaid_five.png](https://github.com/CristinaCod/Amazon_Vine_Analysis/blob/main/Resources/Screen%20Shot%202022-04-01%20at%202.29.29%20PM.png)

## Summary
### Findings
Based on the above findings of the queries run is appears that there is a positive bias towards the Vine program as their percentage of five-star reviews was 51.06%. Compared to the percentage of non-Vine reviews which was 38.7%. 

However, the validity of these findings could be disputed based on the fact that the count for Vine versus non-Vine reviews were vastly different. There were only 94 total Vine reviews whereas there were 40,471 non-Vine reviews. Clearly, a smaller amount of total reviews and the amount of those being five-star reviews will result in a higher total percentage.
### Recommendations 
Further evaluation needs to be done to bolster these findings. To determine if there really is bias towards Vine reviews, we could also run a statistical analysis to find other values such as the mean, median, and mode for ratings for both Vine and non-Vine reviews and compare those findings.
