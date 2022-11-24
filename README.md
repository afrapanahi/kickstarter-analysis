# Kickstarting with Excel

## Overview of Project
In this project we are using excel to analyze the outcome of fund-raising campaigns for different plays. We want to determine what percentage of the campaigns were successful and if the launch date affects the outcome. To do that, we are looking at the theater outcomes by launch date and the outcome base on goals.
### Purpose
The purpose of this study is to see which campaigns have been successful in generating the targeted funds for plays.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
In order to investigate the theater outcome by launch date, I made a pivot table that is filtered based on years and categories. I put the date of each launch as the rows and the count of each outcome as the values. The result of this analysis can be observed in sheet “Theater Outcomes by Launch Date”. 
### Analysis of Outcomes Based on Goals
To do the next analysis which can be seen on the sheet “Outcomes Based on Goals”, I used countif to determine what percentage of plays were successful in meeting their campaign goals and what percentage of them failed.  
### Challenges and Difficulties Encountered
The main challenge for me was to write a code that would efficiently (without having to do many countif commands) keep track of each goal bracket. I ended up hardcoding the limits of the goals (as can be seen on the sheet) which is not easy to modify in future (if needed) 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. According to the plot that depicts number of campaigns versus months, in the month of May 111 campaigns were successful which is the maximum successful campaigns among all months. From the month of May to September, the total number of campaigns along with number of successful campaigns decreases. 
2. The maximum number of failed campaigns happened in the month of October with 50 failed campaigns. It is worth noting that the month of October is also the only month with no cancelled campaigns.  
- What can you conclude about the Outcomes based on Goals?
Generally, the percentage of failed campaign increases with the goal of the campaign.  The two exceptions are $ 35,000 to $40,000 and $40,000 to $ 45,000 where the 67% of the campaigns manage to meet their goals. 
- What are some limitations of this dataset?
There is no data on who the backers are. 
- What are some other possible tables and/or graphs that we could create?
We can analyze campaigns for other platforms and compare with plays and determine the one with most success. To do that we can do a pivot table similar to the one we did for plays and compare.
# kickstarter-analysis
![Outcome vs goals](/resources/Outcomes_vs_Goals.png?raw=true "Outcome vs goals")
