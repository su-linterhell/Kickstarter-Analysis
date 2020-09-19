# Kickstarter-Analysis
Performing analysis on Kickstarter data to uncover trends
## Overview of Project 
This project analyzes the success & failures of different crowdfunding campaigns to understand what factors makes a successful campaign. The goal of this project is to give Louise, better insight on how she can start a crowdfunding campaign for her play, "Fever".
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)

This chart shows the outcome of a theater campaign based on its launch date. There are a few trends we can see from this chart. Cancelled campaigns appear to remain relatively the same throughout the year/different dates. We see an increase in successful campaigns that were launched from March – June, June being the month with the highest number of successful campaigns. After June, we see a continuous decline in successful campaigns, with December being the month with the least amount of successful campaigns. 
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](Resources/Outcomes_vs_Goals.png)

This line graph demonstrates the trends in success and failure, based on the crowdfunding goal. Overall, there were more successes than failures (694 successes vs. 353 failure campaigns) in crowdfunding. A successful campaign is one where the goal set was met or passed with the amount of money that was pledge. Successful campaigns on average had lower campaign goals by $5,505.33 compared to campaigns that failed. 
### Challenges and Difficulties Encountered
An initial challenge was editing or reformatting the data so that it was easier to utilize. Category & Subcategory were combined into one column, making it harder to look at more specifics between the two. After a simple reformat, I was able to breakdown each field into two separate columns. Additionally, dates were given in a format that was not understandable off the bat. Through a few steps, I was able to understand that this was saved as a Unix Timestep. Through some conversions, I was able to store the “Deadline” and “Launch Date” fields in a much easier way to understand. Through both of these initial reformatting steps, the data was significantly easier to use to view trends. 
## Results
### Conclusions Drawn from the Outcomes based on Launch Date
By looking at outcomes based on launch date, I would reccomend launching a crowdfunding campaign in Spring rather than Fall or Winter. I highly reccomend avoid starting any campaigns in December. June appears to be the most fruitful month to launch a campaign as we can see in the chart above. 
### Conclusions on Outcomes based on Goals 
On average, failed crowdfunding campaigns had goals set that were $5,505.33 higher than successful campaigns. Larger campaign goals take more effort to meet. The average goal for a successful campaign was around $5,048.88. If Louise's goal for her campaign will be the same as her projected budget of 10k, it may be more unlikley that her campaign is successful. However, if she takes her launch date into consideration that could make a difference between being a successful campaign or failed campaign. 
### Limitations of this dataset
Limitations of this dataset include analyzing campaigns that are still live. There are 50 live campaigns that cannot be counted as either successful or failed. However, some of these live campaigns have already passed their goal, and others are so far away from meeting their goals. However, since they are still live, they cannot be taken into consideration by the way we label our data. The additional data could provide more insight on different trends or strengthen trends we already see. 
### Other possible trends, graphs or tables to consider 
Through this project trends on outcomes based on launch date by month were looked at. Another useful graph could be the same information displayed by years instead of months. This will give better insight if the trends we are seeing are relatively consistent throughout each year, or if the year itself has an impact on a campaign’s success.
