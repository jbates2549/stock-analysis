# Kickstarter Analysis of Theater Projects

## Overview of Project
  This project provides statistical analysis of kickstarter campaigns for theater projects with specific focus on plays.  The report evaluates different criteria which can influence the success of the campaign including launch date and fundraising goal. 

### Purpose
The purpose of the project is to determine the factors which influence the success of kickstarter campaigns for the theater category.  Using past data for kickstarter campaigns, this report will provide analysis of key factors which contribute to successful campaigns.

## Analysis and Challenges  
### Analysis
This analysis focuses on the influence of the time of year that theater projects are launched.  The goal is to determine if the time of year influences the success of kickstarter campaigns for theater projects.  The report provides additional analysis for the plays category with the objective of determining the impact of goal amounts to the success of campaigns for plays.

### Analysis of Outcomes Based on Launch Date
The chart below shows successful and failed theater campaigns based on launch date.  We can see that successful campaigns peak in the month of May followed by the months of June and July.  The failed campaigns remain fairly consistant, varying between 31 and 52 for each month.  Although there are small spikes in the months of May and October, the failure rate is relatively consistent.  The differences in successful campaigns vary much more with a high of 111 successful campaigns in May and a low number, 37 in December.


![image_name](https://github.com/jbates2549/Kickstarter-Analysis/blob/master/Theater_Outcomes-vsLaunch.png)


### Analysis of Outcomes Based on Goals

In this analyis we review the impact of fundraising goal amount on the success of the plays subcategory.  The chart below shows that campaigns are generally successful, 76%, with goal amounts under $1000.  The success rate steadily declinces as goal amounts increase, dropping to a 20% success rate for goal amounts of $25,000 to $30,000.  From there the success rate increases to 67% for campaigns in the range of $35,000 to $50,000.  From that point, campaign success drops sharply with no successful campaigns in the $45,000 to $50,000 range until a small recovery begins for campaigns over $50,000. 


![image_name](https://github.com/jbates2549/Kickstarter-Analysis/blob/master/Outcome_vs_Goal_Plays.png)


### Challenges and Difficulties Encountered

In the analysis of outcomes based on fundraising goals, the number of samples tended to decline as goal amounts increased.  The smaller sample sizes tend to reduce the predictive accuracy of the report.  To provide additional goal amount analysis we provide additional analysis for the entire theater category to increase the sample size.  The below chart showing outcomes based on fundraising goal for the entire theater group generally confirms the findings of the plays subcategory.

![image_name](https://github.com/jbates2549/Kickstarter-Analysis/blob/master/Outcome_vs_Goal_Theater.png)

## Results

### Conclusions from Outcomes Based on Launch Date

The Months of May through June are the best months to launch a kickstarter campaign for theater projects  These months produce the largest variance between successful and failed campaigns.  We recommend that kickstarter campaigns for theater projects be launched during these months.

There is a smaller positive spike in successful campaigns in the months of February.  This month can be considered a secondary target to the Summer months for launch date.  We However these spikes are matched by similar spikes in failed campaigns 


### Conclusions from Outcomes Based Fundraising Goals

From the analysis of goal amounts for plays we can conclude that low budget, less than $1,000, campaigns are, on average, the most successful.  There is also a high correlation of success for campaigns in the $35,000 to $50,000 range.  Campaigns over $50,000 seem particularly risky and should be avoided.

As stated in the challenges section, the data set is limited and samples decline as goal amounts increase.  We should be somewhat suspect of the data for the higher dollar campaigns.  


### Further Analysis
Similar analysis can be performed based on country location or region to see if there is a correlation between location and the success of the campaign.  We can also look at the number of backers and average donations to further analyze campaign success.
