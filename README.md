# Kickstarting with Excel

## Overview of Project - The project is based on a kickstarter campaigns that use crowdfunding data used to examine and analyze trends.

### Purpose - The purpose of the analysis is to visualize the relationship between outcomes of the kickstarter campaigns and their launch dates and outcomes of the kickstarter campaigns and their funding goals.

## Analysis and Challenges - 

### Analysis of Outcomes Based on Launch Date - This analysis aims to show any relationships between the success failure or cancelation of a project based on the month that the project was launched in. To achieve this goal, we first had to convert the dates from unix time stamps and extract the years date created so that it could be used in a pivot table to compare it with our outcomes. Next that pivot table had to be filtered to only show theater campaigns, months of the year and non live campaigns. Next a line graph was used to easily see how the campaigns stacked up against each other.


### Analysis of Outcomes Based on Goals - This analysis aims to show any relationships between the play campaign based on outcomes (only successful and failed since non were canceled) and the goal of the campaign. To achieve this goal, we first have to create a table that counts the number of each outcomes in different goal ranges using excels COUNTIFS(). Next we use the SUM function to calculate the total for each range regardless of outcome so that we can calculate the percentages of our segregated values when compared to the total . Finally, a line chart was used to visualize this comparison.

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?


- What can you conclude about the Outcomes based on Goals?
1. Based on the line graph, our data shows that projects that have a higher goal tend to have a higher chance of failing as well as projects that have lower goals have a higher chance of success. The graph does show however that it is very possible that projects with higher goals can still succeed and projects with lower goals fail.


- What are some limitations of this dataset?
Methods of fundraising and other variables

- What are some other possible tables and/or graphs that we could create?
