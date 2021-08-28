## Kickstarter-analysis
# Kickstarting with Excel

## Overview of Project
 

### Purpose

Louise is marching towards raising $10000+ for her production Fever. She is almost close to reach her fundraising goal. Now she needed to understand how various campaigns were successful or unsuccessful based on launch dates as well as fundraising goal amount. Visualization of outcome based on launch dates and amount will help predict likelihood of success for Louise’s project by comparing similar project like her. Additionally, it will help her determine next steps to reach her fundraising goals. 

## Analysis and Challenges
Two analyses were completed for this project. The first analysis was outcome based on goal and 2nd analysis was outcomes based on month launched. 

On the 1st analysis, each of the goals are categorized into several goal range starting with goal less than $1000 and then incremental ~$5000 goals up to $50000 and over $50000. After that I used COUNTIFS formula to only count successful plays for each goal range. Similar process is repeated to count failed plays and canceled play. Then utilized SUM formula to total of successful, failed and canceled play for each goal range. Finally, the percentage of successful, failed and canceled were calculated. Then following chart is created to visualized the data. 

![myimage-alt-tag](/Resources/Outcomes_vs_Goals.png)

On the 2nd analysis, pivot table was created based on campaign date created. Then added filter for Parent category and Year. After that counts of outcomes were added to values and columns. The Date created conversion was added to row, and removed Year and Qtr data to display only month. Finally, pivot chart was created to as shown below.   

![myimage-alt-tag](/Resources/Theater_Outcomes_vs_Launch.png)

### Challenges and Difficulties Encountered
The analysis exercise was fun to work.   I encountered small challenge while working on 2nd deliverable of project.  The direction for outcome based on goal was slightly vague. For the goal of $1000 to $4999, my formula was looking for less than or equal to $4999 (<=$4999) instead of <5000 in Countifs formula. Similar mistake was replicated for all other goal range. I crossed checked the count with actual Kickstarter data tab and realized the error to fix it.  

## Results

### Analysis of Outcomes Based on Launch Date

Successful outcomes are higher than failed outcomes and cancelled outcomes throughout the year. There are very few canceled outcomes found and none of the theatres campaigns are cancelled in October.  October and December are worst month to launch campaign because it has most failed and least successful outcomes respectively. 
 
Theater outcomes is generally successful. Number of successful campaign starts to trend up in March and reaches its peak in May. After May it continues to trend down rest of the year with exception of month of October.  May is the best time of the year to launch new campaign as it is likely to succeed. 

### Analysis of Outcomes Based on Goals
Outcomes are more successful for goals less than $15000 and goals between $35000 to $45000. 
The fact that there are no cancelled outcomes infers that plays are not cancelled even when its likely to fail. As Louise’s goal is ~$10000, her campaign has higher likelihood of succeeding. 


### Limitation of dataset 
It is noted that dataset do not have any data to indicate time took to reach goal for successful outcomes and if the campaign was cancelled, when it was cancellation. If those details are found it would have been easier to understand the patterns on of successful outcomes. Furthermore, the data do not have any information on how the campaign was executed to help understand factors for success or failure.

### Additional recommendation for graph
It is recommended to create graph with outcomes based on goal by launch date to identify the likelihood of success based on launch dates. This will help further refine the type of outcomes that is similar to Louise's campaign, goal and rollout period. 

