# Kickstarting with Excel

## Overview of Project
1.	Import data into a table for analysis.
2.	Apply filters, conditional formatting, and formulas.
3.	Generate and interpret pivot tables.
4.	Calculate summary statistics 
5.	Illustrate data and identify outliers in datasets.
6.	Perform an Excel analysis with visualizations.
7.	Interpret Excel visualizations.

### Purpose
The purpose of this analysis is to aid up-and-coming playwright, Louise. She plans to start a crowdfunding campaign to help fund her play “Fever”. 
Throughout this project we will organize, sort, and analyze crowdfunding data to determine whether there are specific factors that make a campaign successful.  
The information gathered will allow Louise to set up her own campaign for success. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Louise plans to start a crowdfunding campaign to help fund her play “Fever”. Therefore, the Kickstarter data was filtered to show only theatre data. 
The number of live outcomes were minimal and were thus filtered from the data set. As shown in the chart below, the most successful theater outcomes occurred in May.
Please refer to Theater_Outcomes_vs_Launch chart in the resources folder.
 

### Analysis of Outcomes Based on Goals
Louise’s interest is in theatre, but more specifically the “plays” subcategory, therefore an additional filter was applied to the data set. Once again, the number of 
live outcomes were minimal and were filtered out from the data set. The Kickstarter goals were sorted into groups of $5,000. The total number of successful, failed, 
and canceled outcomes were calculated for each group and then converted into percentages. The graph below offers a visual representation of the data gathered. 
Please refer to Outcomes_vs_Goals chart in the resources folder.

 
### Challenges and Difficulties Encountered
Once the formula to calculate the percentage of cancelled projects was created, all of the groups had zeros. After careful examination, it was discovered the percentage formula
 was inverted and dividing the total projects by the number of canceled projects. The solution was quite simple, all I had to do was divide the number of canceled projects by the 
total number of projects. The data was then filtered to confirm that no cancelled plays existed and the formulas were checked for accuracy.  

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
•After viewing the graph, it can be observed that the most successful theater projects occurred in the months of May and June before slowly declining throughout the year. 
Therefore, the best months to launch a successful theatre project are May and June. 
•Lastly, it can be observed that there were very few canceled theater projects, with the exception of the month of October. 

- What can you conclude about the Outcomes based on Goals?
•	After viewing the graph, it can be observed the most successful percentages of outcomes are projects with goals that are less than $5000 goals or between $35000 and $50000.

- What are some limitations of this dataset?
There was limited data on failed projects and even less information on canceled projects. 
Additionally, there were no examples of canceled plays in the subcategories. 

- What are some other possible tables and/or graphs that we could create?
We could create a table that shows the correlation between the goal amount, deadline, and outcome. Is the outcome of the project solely dependent on the goal amount or the time needed 
to reach that goal? 
