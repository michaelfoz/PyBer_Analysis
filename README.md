# PyBer_Analysis
UCD Module 5

# Deliverable 3 Written Report
### Overview/Purpose of the new analysis:
Module 5 goes in depth with Matplotlib's built-in functions and methods that can be used to create graphs or visuals of data. These visuals can be in the form of scatter plots, box-and-whisker plots, bar graphs, line graphs and pie charts. Similar to Excel and VBA, Matplotlib's functions can be used to select or highlight certain rows or columns of a datasheet (or, in this case, a CSV file) to create the DataFrame. From these new DataFrames, we can create visuals to observe trends. For this challenge, we compare fares or trips made between 3 types of cities (Urban, Suburban and Rural) over a duration of time. In this case, the timespan we observe in the assignemnt is between 2019-01-01 through 2019-04-29 (in other words, from the beginning of the year 2019 to the end of April 2019). A multiple line graph best shows these trends from the ride-sharing data. 
### Results:
![Pyber_fare_summary](https://user-images.githubusercontent.com/101305696/163699936-422638ac-ffe4-4ed1-bad0-44758703ec94.png)

<img width="100%" alt="Deliverable_2_DataFrame" src="https://user-images.githubusercontent.com/101305696/163700226-1368a1b2-63aa-4b04-bf47-08ed75a927ae.png">

From the data, we observe an indirect or inverse relationship between (a) the total numbers of rides, drivers and farves vs. (b) the average fare (price) per rides and per drivers. Although Urban type cities have a higher volume of rides, drivers and fares, the average fares per rides and drivers have the least $USD value amount. In like fashion, rural type cities have a lower volume or rides, drivers and fares and it makes sense that the average fare per ride and per driver would be the highest $USD value amount of the 3 city types. In summation, as the number of rides, drivers and fares increase, the average fare per ride and per driver decreases. As the number or rides, drivers and fares decrease, the average fare per ride and per driver increases.

### Summary (3 Business Recommendations to the CEO for addressing any disparities among city types):
#### (1) Look into a total duration of a ride and charge for the ride duration.
#### (2) Similarly, look into the total mileage of a ride and charge for that mileage.
#### (3) Look into what might be the busier/busiest times of day where there is an increased need for drivers--for example, rush hour--and charge proportionately or accordingly to that demand of drivers needed at that given time of day.
