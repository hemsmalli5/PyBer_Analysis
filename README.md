# PyBer_Analysis
For Pyber Data Analysis, we will analyze large csv files and create visualization using matplotlib to show case relation between the city, the number of drivers and riders, summarize key metrics for the ride-sharing data by city type and create a  multiple-line graph that shows the total fares for each week by each city type. This analysis will help Pyber to determine the fare estimations for underserved neighborhoods. As part of this challenge, we are creating a summary DataFrame showcasing below details: 
o	Total Rides; ride count grouping by city type 
o	Total Drivers; driver count grouping by city type 
o	Total Fares; fare sum grouping by city type 
o	Average Fare per Ride; total fares / total rides
o	Average Fare per Driver; total fares/ total drivers
All these metrics pulled into a summary DataFrame

Inline-style: 
![Summary](https://github.com/hemsmalli5/PyBer_Analysis/blob/master/Summay%20DataFrame.PNG)

Inline-style: 
![Line Graph](https://github.com/hemsmalli5/PyBer_Analysis/blob/master/Line_graph.png)

Summary DataFrame reveals that Rural cities have highest average fare per driver ($55.49) and Urban cities have least average fare per driver ($16.57) even though Urban cities have higher number of drivers (2,405) and have highest fare collection ($39,854.38). The Line chart that shows fares from Jan 1, 2019 to April 28, 2019 based on weekly data, reveals same data that the total fare by Urban stands highest in comparison with Suburban & Rural Areas. This analysis is indicative of total fares are directly proportional with total riders and drivers’ number and we can conclude that the Pyber rideshare app is good bet on Urban areas.

The technical analysis was straight forward except few challenges that were resolved such as formatting the columns, setting and dropping the indexes where necessary, resampling weekly data for line graph. We used Python and Pandas functions to overcome these challenges.

Recommendations: the summary stats and line graph represent good trips are focused around urban areas with lowest average fare for drivers. This solidifies that ride share app is popular among urban cities. If required, we can conduct further analysis. We have limited dataset between Jan 1, 2019 to April 29, 2019 to draw conclusions. Bigger span of dataset could probably lead better conclusions. We can also focus on different datasets focusing on seasonal/peak hour trips to derive conclusions. Even though we observe the urban cities have highest total fares among other city types, conducting additional analysis on breaking down peak hours from timestamps as line graphs would provide better understanding of exploring rideshare business in underserved cities.
