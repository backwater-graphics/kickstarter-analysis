# Kickstarting with Excel
## Overview
Louise reached out after her play Fever fell short of its fundraising goal, which the fundraiser they ran only for a small amount of time. She wants to know how the different play campaigns fared in relation to their launch dates and their funding goals. 

This project excel will track the data analysis of several play projects to uncover the trends of the campaign’s outcomes, whether it was successful, it failed, or it was concealed. This project will also show the correlation based off the launched date and the funding goal.
### Purpose
The purpose of this excel project was to provide Louise with information from people who are successful at fundraising to finance their plays. It will also help her understand the specific factors that make a successful fundraising campaign, which will allow her to mirror those techniques so that her next fundraising campaign will be successful.

The results from this analysis can be found here: ![kickstarter_challange](https://github.com/backwater-graphics/kickstarter-analysis/blob/main/Kickstarter_Challenge-MU.xlsx)
## Analysis and Challenges of the Outcomes Based on Launch Date
Based on the Kickstarter Challenge excel data in order to preform the analysis of the Outcomes Based on Launch date we need to first convert the Unix timestamps to Human dates conversion with the Month, Date, and Year to set up the analysis, so that we can determine whether the timing was factor in successful fundraising campaigns. 
After the conversion was done, we needed to setup a pivot table and pivot chart so that we could show and determine from the data if a campaign was Successful, Failed, or it was Canceled. The live campaigns were filtered out and the pivot table was sorted in ascending order by month to create the line chart.
The analysis in the chart below shows both the number of campaigns as well as the success rate.
### Analysis of Outcomes Based on Launch Date

![Theater Outcomes Based on Launch Date](https://github.com/backwater-graphics/kickstarter-analysis/blob/main/ParentCategoryOutcomes1.png)
---
## Analysis and Challenges of the Outcomes Based on Goals
Louise also wanted to know what the Outcomes Based on Goals pledged showed toward successful campaigns. So based on the Kickstarter Challenge excel data we needed to setup a table with 12 ranges of $Pledged by goal
We used the COUNTIFS() function to group the ranges into Successful, Failed, and Canceled outcomes for the "plays" subcategory and a percentage outcome was calculated for each range.
The chart below was created to visualize the outcomes by Goal $ Segment. This was useful to determine whether $ value of Goals have an impact on outcome.
### Analysis of Outcomes Based on Goals
### Challenges and Difficulties Encountered
A challenge that we encountered in this analysis was the inability to get more specific actions that would guide Louise in her campaign other than when to launch and that the dollar size of the goal or pledge did not predict the rate of success.
In addition to those challenges listed above, the data also indicated that there are some failed Kickstarter campaigns with really high goals. We also noticed that each outcome subset of Goals and Pledges had a similar distribution given the proximity of the Mean and Median values in each case. However, the fact that the Standard Deviation of goal for Failed projects is high would suggest that there are some Failed programs that had extremely high goals set.
## Results 
Based on the analysis, we can determine the following:
What are two conclusions can you draw about the Theater Outcomes by Date?
•	When we analyze the data in the Kickstarter Excel document, we determine that the month of May outcomes has the highest overall success rate of launching campaigns
•	From the excel data we can also determine that the months of May, June, and July have the most or highest success rate for fundraising campaigns
What can you conclude about the Outcomes based on Goals?
•	From the outcomes based on goals data we can conclude that the successful range decrease as the funding goals increase, meaning that asking for too much money while fundraising may cause it to fail.
What are some limitations of this dataset?
•	Some of the limitations with this dataset is that it does not factor in what else could influence the data to determine if a project is successfully funded.  Another limitation with this data set is that it does not have a lot of information on what donors expect to receive in exchange for their donations (e.g. tickets, backstage passes, merchandise, etc.). This could impact a donor’s decision to donate. As you can see the limitations listed above are clearly other factors then Goal amount and month of the year that could influence whether a project is successfully funded. These factors should be included in the data set so that future funders can use the information to increase their probability of success.
What are some other possible tables and/or graphs that we could create?
There several possibilities of tables/graphs the we could create, below I have listed a few of those possible ideas to display the data:
•	A graph showing the correlation between the number of backers vs what the outcome was. To show if the most successful had more backer’s vs the failed or canceled had the least number of backers.
•	A graph and table that would exclude significant funding goal outliers.
•	A graph and table that could show the fundraiser location, amount of donation , outcome, percentage, type of fundraiser.
