# Kickstarting with Excel

## Outcomes of Kickstarter Projects Based on Launch Date and Goal Amount

This analysis looks at launch dates of Kickstarter campaigns for theater projects to determine if launch date impacts the success of the campaign. It further looks at established goal amounts set at the launch of the campaign, also to determine if goal amount impacts the probability of success.

### Purpose

The purpose of performing this analysis is to determine when is the most opportune time to launch a Kickstarter campaign for a theater project and if there is an optimal level to set the goal to increase the chances of success.

## Analysis and Challenges

To gather the data needed to make the launch date analysis, I created a pivot chart that sorted Kickstarter campaigns by launch month and outcome.  This allowed me to chart this data in a line graph that shows a clear picture of how many campaigns were launched each month and whether they were successful. Below I have shared an image of the pivot table and the chart will be shared with the launch date analysis. The challenging part of this analysis was sorting the months launched from the overall launch date.

![image](https://user-images.githubusercontent.com/78807451/115763514-894c2480-a372-11eb-866e-cca5a5b2b4b9.png)


### Analysis of Outcomes Based on Launch Date

The time of the year when a Kickstarter campaign is launched has a noticeable impact on the success rate of the campaign. Campaigns launched in the late spring have the best chance of achieving the desired goal.  This trends down over the course of the remainder of the year. The best time to launch is between the end of April and the beginning of September.  Campaigns launched late in the year are much less likely to be successful. This is likely due to the holidays when people are dealing with the associated expenses. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/78807451/116123517-148a2a80-a691-11eb-9f0a-b7570285f888.png)

### Analysis of Outcomes Based on Goals

The amount of money that one is trying to raise in a Kickstarter campaign shows a direct impact on how successful the campaign turns out.  There is a slight decline in success rate as the goal increases from less than $1,000 up to around $5,000. After that the success rate trends down quickly up to the $20,000 range. The data indicates success at varying ranges up to $50,000, but the sample size is too small to draw any conclusions. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/78807451/116126342-89ab2f00-a694-11eb-8357-7cb7367d60e1.PNG)

### Challenges and Difficulties Encountered

Getting the data sorted and converted to correct date formats was the first challenge for me. Another challenge was the amount of data included that was not needed for the analysis we were conducting.  The only other difficulty I encountered was ensuring the required level of attention to detail to achieve the correct data was pulled from the data set.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  * Late spring is the best time to launch a Kickstarter campaign. The propensity for success drops off through the summer.
  * Launching a Kickstarter campaign near the Christmas holiday time greatly decreases your chances for success.

- What can you conclude about the Outcomes based on Goals?

  * Campaigns in the $5,000 or less range tend to have a greater chance of reaching their desired goal.
 
- What are some limitations of this dataset?

  * There are many factors that could contribute to the success or failure of a Kickstarter campaign. This data set could be more complete in dealing with background and experience levels of the people behind the campaigns. There was also a lot of data points that could have been filtered out before we started because they were not relevant to our analysis.

- What are some other possible tables and/or graphs that we could create?

  * We could use a clustered bar graph to group campaigns by type or launch date to visualize the success or failure rate more clearly by category or sub-category.
