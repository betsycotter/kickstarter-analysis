# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends. 

## Overview of Project

### Purpose

Our client, Louise, is looking to put on her own play. She will be seeking donations through a crowdfunding system and would like to learn more about similar campaigns. We have analyzed the data she has provided to determine valuable insights to help her with her fundraising process. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

We took the data and created a line graph called “Theater Outcome Based on Launch Date” to see if the launch date could determine if the campaign will likely become successful. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/116031639/198141769-5356b3f9-9116-4701-bdeb-c7d08ff84573.png)

Based on the above chart, we can see that successful campaigns were more often launched in May, June, and July. On the other hand, launch dates in November and December saw the lowest amount of successful campaigns. Furthermore, in November and December, the gap between successful and failed campaigns was the smallest. Additionally, the lines for both successful and failed seemed to follow in a similar pattern, so this could mean that there is more volume in May, June, and July as compared to November and December. The canceled data had no significant insights or correlations. 

### Analysis of Outcomes Based on Goals

Louise has an estimated budget of over $10,000. When reviewing our chart called “Outcomes Based on Goals” we see that there are varying outcomes based on fundraising goals. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/116031639/198141902-bcdb4b55-c6f3-4670-8dd6-5d37a395cc45.png)

For Louise specifically, in the goal bracket of 10,000 to 14,999, we can see that the percent successful versus percent failed is similar, yet successful has a slightly higher percentage. However, as we move to the next goal bucket larger, they are exactly even. Should Louise need additional funds, she should understand that this could come at a greater risk of failure than her original budget. However, if she can reduce her goal, she has a greater chance of success, as the buckets less than 10,000 have a greater chance at success, based on the historical data. 

### Challenges and Difficulties Encountered

One challenge encountered is that we did not account for currency exchanges in the goals and pledged amounts. We assumed that all of the data was the same, however, there is a column that shows the currency for each row. The analysis is flawed in that the goal buckets assume that the currency is all equal. Additionally, we assumed that Louise’s goal of $10,000 was the same as the 10,000 to 14,999 bucket. To overcome this challenge, we could convert everything into the same currency. For our client, USD is the most appropriate, since that is what she will be collecting. 

Along those lines, the data was for a range of countries. It appears that there are countries in both the northern and southern hemispheres. We did not factor into the analysis if the data was affected by the season. Maybe one suggestion is to have another field that shows what season is being evaluated, rather than the month. 

Furthermore, another challenge is that the monthly data for the outcomes based on launch date does not show the details based on each year. There could be fluctuations annually, which are not shown in this analysis. While this data is only through 2017, something like COVID-19 could have significantly changed the monthly patterns, yet we do not have that visible on this graph. To overcome this challenge, one could have a graph with the annual details to see if there are additional patterns. 

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?

First conclusion: if possible, Louise should launch her campaign in May. This would allow her to have a greater chance at successfully funding her project. 

Second conclusion: it is not recommended to launch her campaign in the last quarter of the year. The gap between successful and failed is the smallest during that time. Furthermore, December has nearly the same number of successes and failures. 

### What can you conclude about the Outcomes based on Goals?

Campaigns with the lowest goals have a greater chance at being successful. Our client is looking for $10,000, which is likely to be successful, however, setting a lower goal is recommended if the quality of the play is unchanged. 

### What are some limitations of this dataset?

1. Some of the columns were not explained, so we were unable to use them for analysis. These columns include: staff_pick and spotlight. 

2. Another piece of data that could be helpful is another subcategory that has a summary of the type of project. While the data shows a description of the campaign, called the “blurb,” it would be helpful to have a generic subject assigned to each campaign. Specifically for Louise, it could be helpful to see a generic subject of the plays, for example: comedy, historical, musical, romantic, etc. If this data was collected, we can dig deeper to see if the subject of her play has particular patterns and success rates.

3. Also mentioned above, some limitations include: currency exchange rates and seasonality based on the country. 

4. The dataset did not include reasons why something was canceled. This might provide some insights and lessons for Louise, prior to launching her campaign. 

### What are some other possible tables and/or graphs that we could create?

1. How many donations she might need, based on the average for her goal bracket. Also, what is the average donation for her goal bracket? 
2. Average time it took for something to be successfully funded. Does the date range from launch to deadline change the outcome from failed to successful? Do backers feel a sense of urgency with a shorter time frame or does a longer time frame help more backers find time to fund the cause?  
3. What is the variance between goal and pledged? Does setting a lower goal actually produce more donations? Can Louise ultimately receive $10,000 or more pledged but ask for a lower goal initially? 
