# Kickstarting with Excel

## Overview of Project

### Purpose

This is an analysis of the outcomes of various Kickstarter campaigns for plays and theater productions. The analysis attempts to provide insight into the success of various projects based on their launch dates and fundraising goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The analysis of outcomes based on launch dates was done by creating a sub-table of the dataset by filtering the data by the month in which the fundraiser was launched and the number of successful, failed or cancelled projects. A line graph was then generated out of this table to more easily visualize the data.


### Analysis of Outcomes Based on Goals

The analysis outcomes based on goals was done by breaking up the goal amount into 12 categories and then calculating the number of successful, failed or canceled fundraisers for those ranges. These data were extrapolated further into the percentage of successful, failed or canceled fundraisers in each goal range. Another line chart was made of the percentages to show which goal range had the most success or failure.

### Challenges and Difficulties Encountered

The first challenge I encountered with this analysis was converting the Unix-based dates in calendar dates that could be manipulated while performing an analysis. The second was formatting the percentages in a way that was translatable into a graph. I modified by formula for calculating the percentage to counter excels default percentage convesion. This is the formula I used to clean up the presentation.

'=((B2*100)/E2)/100'

## Results

Based on this analysis, it seems that the most successful fundraisers took place in the early summer months (April-July) and began to taper of in August and were at their lowest during the fall. The number of failed campaigns remain relatively steady with a slight jump in October.

Most of the successful campaigns appear to be those that had a fundraising goal which was relatively low, the exception being those that were in the $35,000 to $45,000 range.

This analysis could be improved by determing the variations between countries and the year that they were executed. Charts that show these two variables could provide a more robust analysis.
