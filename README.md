# kickstarter-analysis
Week 1 Challenge - Kickstarter
## Overview of Project
  The playwriter, Louise, estimates an over $10K budget for her coming play, fever. She needs some advice to arrange a crowdfunding campaign to fund the play.
  The project focus on using excel to conduct an analysis by existing site data to see if fundraising dates and goal amount are specific factors to determine if compaign sccucceeded. The analysis should offer Louise some guidelines on launch date and goal to arrange her campaign.
## Analysis and Challenges
  Although, there are 4,113 campaigns records in existing site data, there are only 1,369 records are related to compaigns for theater. Since Louise is look for funding for a play and play is a subcategory belongs to thether category, the analysis will base on the 1,369 records first. First, we create a line chart shows if companigns outcome will have a different pattern between launches in different month. 
  Then, among 1,379 theather compaign record, there are three types of subcategory, plays, musical,spcaes and there are 1,047 records related to compaigns for play.Using these 1,047 data, we make a statistical table to calcuate successfull, failed and cancelled percentage base on different goal amount break to see if play's compaign outcomes have any relationship with different goal amount.
## Result
### Analysis of Outcomes Based on Launch Date
  During 2009 to 2017, there are total 1,369 campaign records, and 839 compaigns are successful, 493 are failed, and 37 are canceled. From the pivot table chart, it can be concluded that most successful campaigns are held in May, Jun, Jul, Aug, and Oct and especially in May. 
![Theater_Outcomes_vs_Launch](./resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
  The line chart displays that it is 50% that the compaign could be succeeded or failed while the goal amount between $15,000 to $19,999. It is more likely to succeed, percentage successful rate is more than 50%, while the goal amount is less than $15,000 and it is more likely to failed, percentage failed rate is more than 50%, while the goal amount is higher than $19,999. While the goal amount exceeds $35,000 and is less $44,999, it is again more likely to succeed. However, while the goal amount is more than $45,000, the successful percetage could be merely 0% and 13%.
![Outcomes_vs_Goals](./resources/Outcomes_vs_Goals.png)
### Limitations of this dataset
  Since we try to drag a conclusion based on the existing data on hand, it is necessary to use the most updated data. Since now it is 2021 and the data only included till year of  2017. The market might have a different preference during these 4 years. Our conclusion could only delivery that before 2017, the most successful campaigns were held in May, Jun, Jul, Aug, and Oct and especially in May.
  Another factor not considered is that country. Louise did not specially point out that where is she going to do the campaign. 
###  Other possible tables and/or graphs that we could create
![Outcomes US](./kickstarter-analysis/Outcomes US.png)
![Outcomes GB](./kickstarter-analysis/resources/Outcomes GB.png)
