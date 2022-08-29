# Challenge_1_Assignmnet-
The submission of Excel Challenge 1
# Kickstarting with Excel

## Overview of Project

Louise started a crowdfunding campaign to help fund her play, *Fever*. Her play came close to its fundraising goal which was over $10,000. In this project we are going to analyze Kickstarter dataset in order to visualize campaign outcomes based on their launch dates and their funding goals.

### Purpose
The aim of this analyze is to have a better insight of how different campaigns fared in relation to their launch dates and their funding goals. This will help us determine whether there are specific factors that make a project's campaign successful.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In order to visualize campaign outcomes based on their launched dates we have created a pivot table filtered based on "Parent Category" and "Years". The "Parent Category" is then filtered on "theater", the row labels are changed to display the months of the year, and the campaign outcomes are sorted in descending order. (See Table 1).


<p align = "center">
<img width="499" alt="Table1" src="https://user-images.githubusercontent.com/109363759/187107283-c86997de-4a23-48d0-9618-42a1fe302fac.png">
</p>
<p align = "center">
Table 1 - Pivot table to visualize theater outcomes based on launch date.
</p>

From this Pivot table we have created a line chart titled "Theater Outcomes Based on Launch Date" to visualize the relationship between outcomes and launch month. (See Fig.1).

<p align = "center">
<img width="499" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/109363759/187109572-c191db47-8ba1-4e98-b5c0-8ee4d7124903.png">
</p>
<p align = "center">
Fig.1 - Theater outcomes based on launch date chart.
</p>

Table 1 and Fig. 1 show that the number of successful theaters is in general higher than the number of failed and canceled ones all year long. 

When looking at the chart of Fig.2 we can notice that most successufl kickstarter campaigns were launched between May and June, with May having the biggest number of successful theater (111) and June the second highest number (100).

The number of successful theaters decreases when going from June to December which is the month with the least successufl kickstarter campaigns and the only month where the number of failed and canceled campaigns is higher than successful ones (In Decemmber there are 38 failed or canceled campaings and 38 successful ones).

It is also good to mention that the number of successful theaters from January to March is considerably low per respect to May and June. 

### Analysis of Outcomes Based on Goals
In order to visualize campaign outcomes based on their funding goal amount we have divided the amount of money in the "Goal" column into 12 ranges. In each range we have counted the number and the percentage of successful, failed and Canceled plays. (See Table 2)

<p align = "center">
<img width="599" alt="Table2" src="https://user-images.githubusercontent.com/109363759/187123646-4865c6ba-b9be-4d02-936c-4e83b8e9e21c.png">

</p>
<p align = "center">
Table 2 - Number and percentage of successful,failed and canceled plays in each goal-amount range.
</p>


From this table we have created a line chart titled "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis. (See Figure 2)

<p align = "center">
<img width="499" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/109363759/187109283-2ff5a8aa-f55a-429c-9a74-e2360a8c8990.png">
</p>
<p align = "center">
Fig.2 - Chart of plays outcomes based on goals.
</p>

Table 2 and Figure 2 show us that the percentage of successful plays is considerably high (>70%) for goal-amount lower than $5000. 
This percentage drops to around 55% when the amount of goal is between $5000 and $10000, to reach 50% when the amount of goal is between $15000 and $19999. 
For goal-amount higher than $20000 the percentage of failed plays is in general higher than that of successful ones unless for ranges between $35000 and $50000 where the percentage of successful plays is 67%. It is also worth mentioning that there is only 6 successful plays in this range. 

### Challenges and Difficulties Encountered

When analyzing theater outcomes based on launch date, I noticed that we have a different number of Grand Total per month which may bias our results. Therefore, I have added a column "Percentage of successful theaters" to check if we will have the same results.(See Table3)

<p align = "center">
<img width="499" alt="Table3" src="https://user-images.githubusercontent.com/109363759/187110694-8f44b335-5f04-4fe0-aaa1-034ab400217b.png">
</p>
<p align = "center">
Table 3 - Percentage of successful theaters based on Launch Date.
</p>

Table 3 shows that the highest percentage of successful Kickstarter campaigns is in May (67%) and the lowest percentage of successful theaters (49%) is in December. 

We can conclude that the difference in Grand Total number did not affect our results. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The analysis of outcomes based on launch date allows us to conclude 2 things:
1. The highest number of successufl kickstarter campaigns is in May. Therefore, we will suggest May as the launching date for Louise. 
2. Decemebr has the lowest number of successufl kickstarter campaigns, therefore we will advise Louise to avoid launching her play during this month.

- What can you conclude about the Outcomes based on Goals?

The analysis of outcomes based on Goals allow us to conclude that, in general, the higher the gooal the higher the risk. Eventhough there is 6 successufl plays with high success rate (67%) and high goal range ($35000 to $45000), Louise's goal is over $10000 and far from this range.

Based on the analysis of Outcomes based on Goals, the percentage of success is around 55% for goals between $5000 and $15000. Thus, the percentage of success for Louise's play should be around 55%. 

- What are some limitations of this dataset?

I believe there are some limitations of this datasets that I am going to state below:

First of all, I noticed the lack of recent data. Most of the data go back to before 2017. I believe recent data could change all our results specially since Covid happened in 2020 and social gatherings as theaters and plays where all canceled. New data would be a must to see how Covid affected our results. Moreover, when adding recent data, the increase in data can help uncover better trends and factors that may help a campaign being successful.

Secondly, having data about the number of posts published on social media and the engagement rate on these posts could give us better insights as social media is the fastest way to reach people and make a campaign successful. 

Finally, we should have specific data as age group of people attending a play or the type of plays (comedy, drama...)

- What are some other possible tables and/or graphs that we could create?

With more data we can create a chart showing the campaign outcomes based on their social media engagement, the type of plays, the age of people attending. We can also create tables showing results before Covid and after Covid. 
With the existed data I suggest analyzing the number of successful, failed and canceled campaigns based on the length of the campaign. And the analyze of outcomes based on the number of backers (we can divide the number of backers into ranges).

