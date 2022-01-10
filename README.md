# Kickstarting with Excel

## Overview of Project
The purpose of this project is to analyze kickstarter campaigns from 2009 to 2017 to discover trends in campaign success based on different factors. These factors included campaign category, start date, how long the campaign lasted, fundraising goal, and amount raised. The main category of focus for this analysis was theater campaigns, specifically plays.

### Purpose
The purpose of this analysis is to collect the kickstarter data and analyze the outcomes based on launch date and the outcomes based on goals. Two line charts were produced, one for outcomes based on launch and one for outcomes based on goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A pivot table was created from the 'kickstarter' sheet. This pivot table would filter the data by years and parent category. The number of successful, failed, and cancelled projects are totalled for each month of the year. A line graph of number of projects per month was generated with a line per outcome. The month of October had no cancelled projects in the theater category.
### Analysis of Outcomes Based on Goals
A new sheet was created that pulled data from the 'kickstarter' sheet. This sheet pulled a count of each project in the plays subcategory. There were no cancelled projects in the plays subcategories. Totals and percentages were generated from these values.
### Challenges and Difficulties Encountered
The challenge of this analysis was creating separate =COUNTIFS functions for each price category.
![Countifs screenshot](https://user-images.githubusercontent.com/95397823/148708844-baf11f6d-9c7a-446f-96d9-12c35e3b5c4a.PNG)

## Results
From Outcomes based on Launch Date, you can conclude that most theater campaigns are launched between May and July. Additionally, the success rate of theater campaigns decreases during the winter months, but success picks back up again in the spring. However, in 2016, March through May was the most successful time to launch an campaign.

From the Outcomes based on Goals, you can conclude that more campaigns had a goal of $1000 to $4999 than they did of any other price range. For campaigns over $45000, there were only two successful campaigns and 15 failed campaigns. There were no cancelled campaigns in the plays subcategory. For plays under $10000, the majority of the plays were successful.

The limitations of this data set is that it only cover the years 2009 to 2017. In addition, there are other factors that affect outcome that were not captured, such as promotion on social media. Additionally, the dataset does not capture if the failed campaigns were relaunched as another campaign.

We could make another graph that captures outcomes based on goals as a total rather than a percentage. As the goal value increases, there are fewer campagins in that category. The percentages are skewed because they are only made up of a few values. We could also make another graph for outcomes based on campaign length, to see if longer campaigns were more successful than shorter campaigns.

