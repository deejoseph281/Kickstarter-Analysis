# Kickstarting with Excel

## Overview of Project

### Purpose
This project reviewed Kickstarter data campaigns, focusing on 'Plays' that were successful, failed, or canceled and the associated goals of each 'Plays' campaign. The purpose of the project was to understand whether there was a trend for outcomes that led to successful, failed, or canceled campaigns based on their launch dates and based on their funding goals. The analysis can be found at https://github.com/deejoseph281/Kickstarter-Analysis/blob/main/Kickstarter_Challenge.zip. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
We were able to understand plays by launch date and whether the launch date by month impacted the campaigns probability of success. 
![Outcomes Based on Launch Date](https://github.com/deejoseph281/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
We were able to understand outcomes by goals and whether there was a clear indicator of outcome based on the goal value. 
![Outcomes Based on Goal](https://github.com/deejoseph281/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
The differentiation between COUNTIF for a single criteria and COUNTIFS for multiple criteria was easily missed. 
I did not know how to add the range as criterial within COUNTIFS and needed to lean on external resources to understand how to write the formula for the range using the function. The range would need to be classified as two seperate criteria, while I was tryign to write it into a single criteria. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 
Campaigns are most likely to succeeed when launched in May and June. 
Campaigns are least likely to succeed when launched in December.

- What can you conclude about the Outcomes based on Goals? 
Campaigns are most successful when their goals are less than $1,000
Campaigns are more likely to fail than succeed when the goal is above $45,000.

- What are some limitations of this dataset?
There is no variance field for goal value vs pledged value. 
There is no number of days live for each campaign. 
There is no sub-category subset of type of plays. 
- What are some other possible tables and/or graphs that we could create?
Outcomes Based on Days Live
Percentage of Pledged vs Goal Values for Failed Campaigns
Outcomes by Spotlight 
