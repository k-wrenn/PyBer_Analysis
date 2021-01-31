# PyBer_Analysis
## Project Overview

The purpose of this analysis is to examine the data provided by PyBer, a ride sharing company, and the differences amongst city types. This is done by creating a summary DataFrame of the ride-sharing data. Then, using Pandas and Matplotlib, create a multi-line graph that shows the total weekly fares for each city type between a specific date range (01/01/2019-04/29/2019). This analysis will contain a written report that summarizes how the data differs by city type and how the differences can be used by decision-makers at Pyber.

## Resources
Data source: city_data.csv, ride_data.csv

Software: Anaconda 4.9.2, Jupyter Notebook, Python 3.7.9

## Analysis
First, the two data sources needed to merged into one DataFrame. From there, total rides, total drivers, total fares, average fare per ride, and average fare per driver were calculated for each of the three city types (urban, suburban, rural). A second DataFrame was created conatining the above information. The final results are shown below:

<img width="307" alt="Summary_df" src="https://user-images.githubusercontent.com/74752756/106379629-db346e00-6372-11eb-8b02-492c876a3aef.PNG">


### Total Rides
Urban cities had the largest total number of rides (1,625) which is more than 2 times greater than the total number of rides in suburban cities and 13 times more than the total number in rural cities. This is likely due to differences in population size Urban cities have a larger population and therefore a larger number of potential PyBer users but further data would need to be collected to support this conclusion..

### Total Drivers
Urban cities also have the largest total number of drivers, with 2,405 compared to just 490 and 78 for suburban and rural types respectively. Again, this is likely due to populations size.

### Total Fares
Yet again, urban cities are atop this list, with $39,854.38 total fares. Suburban fares were at $19,356.33 and rural at $4,327.93.

### Average Fare per Ride
Rural cities had the highest average fare per ride, with $34.62, and urban cities had the lowest, $24.53. This difference could be due to a multitude of things. There could be more distance traveled per ride in rural areas due to not being as densely populated. Further research and analysis would need to be done in order to determine this.

### Average Fare per Driver
Rural cities also had the highest average fare per driver ($55.49). Urban cities had the lowest average fare per driver ($16.57).

### Total Fare by City Type
A mulit-line chart was created to examine the total fare by city type between January 1, 2019 and April 29, 2019:

<img width="494" alt="fare_by_city_type" src="https://user-images.githubusercontent.com/74752756/106379655-0e76fd00-6373-11eb-8ca1-85de313dc65d.PNG">


Examining the chart, we can see the Urban city type is more profitable for PyBer than the Rural and Suburban cities, even though it has a considerably lower average fare per driver and average fare per ride. Every week in the above chart, urban cities consitently produced the most total fares compared to suburban and rural cities. 

Rural, suburban, and urban cites all have peaks and valleys in total fares throughout the months examined. Interestingly, all three city types show a spike in total fares around the same time in mid to late February.

## Summary
As illustrated above, there are several disparities between different city types and ride-sharing. 

One recommendation I would make is to look at the marketing strategy in each of the different city types. Are total rural fares so low because the population is not as aware of PyBer compared to that of an urban city? Or is there just no demand for ride-sharing in rural areas? 

Second, I would reccomend trying to get feedback from customers in each of the three city types to see what improvements and changes can be made that would increase customer usage.

Third, in attempt to increase ride-sharing in rural areas, it may be beneficial to offer incentives such as discount codes to new and existing customers to encourage more rides. Discount codes may also be a good idea to incorporate during lulls. Further research would need to be done into when more users are ride-sharing (i.e. weekdays vs. weekends, morning vs. night, close to holidays? , etc.)  to determine which times of the year tend to be slower. 

