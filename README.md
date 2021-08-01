# PyBer_Analysis

## Overview of the Analysis
This is an analysis of ride-sharing data to create a readable chart of total rides, drivers, and fares as well as to calculate averages of rides and drivers between rural, suburban and urban cities. The data initially gathered in the attached data resources files provided no readable format to make comparisons nor provided averages and totals for each city type.

#### Initial sample of [Pyber Data](https://github.com/LauraHaq/PyBer_Analysis/blob/main/Resources/PyBer_ride_data.csv) after merging data files:

![merged_data](https://user-images.githubusercontent.com/86267773/127724808-a82563db-63cf-41a0-a8ec-10c02631ca0d.png)

I used Python pull data from January 1, 2019 to April 29, 2019 to make calculations and reformat those values into a new usable DataFrame. Then I incorporated Matplotlip library to provide a visual comparison of fares over time for the three different types of cities for V. Isualize and to make business recommendations  to Pyber to address disparities between the city types. 

## Resources
- Data Sources:
  - [city_data.csv](https://github.com/LauraHaq/PyBer_Analysis/blob/main/Resources/city_data.csv)
  - [ride_data.csv](https://github.com/LauraHaq/PyBer_Analysis/blob/main/Resources/ride_data.csv)
- Software: 
  - Python 3.7

## Results
#### New Summary DataFrame:

![Summary DataFrame](https://user-images.githubusercontent.com/86267773/127724816-9c163b4d-3383-41a8-8d99-a516f3c4ad9e.png)

First impression is of the large average dollar amounts per driver in rural cities ($55.49) compared to the urban city type's ($16.57) as well as the small totals in rural cities ($4,327.93 Total Fares) to that of the Urban city types ($39,854.38 Total Fare). The suburbs are in the middle of the road with $19,356.33 Total Fares and $39.50 Average Fare per Driver. A simple take away is that as population density increases the cost to the customer is lower. As we get away from the city life, trips occur less but distance travelled is longer so the cost is more. However, as we look between the columns the differences between each value are disproportional and the number of drivers compared to total number of rides is not equal. 

#### Line chart of Fares over Time:

![PyBer_fare_summary](https://user-images.githubusercontent.com/86267773/127725486-37f61106-1b0b-425c-80be-8e0466bb4b34.png)

Looking at how Total Fares change over time in this line-graph will tell a story of how the need for rides change from late Winter to early Spring. This graph shows Total Fares in Rural City types experiences a spike every five weeks. It also shows a steady increase of Total Fares in Urban City Types coming out of mid-Winter and fluctuates into early Spring. Suburban Total Fares hovers around $1,000 and does not show any increase or decrease in supply or demand. Interestingly, all three city types experience a spike late February of Total Fares. 

## Summary
My first recommendation to Pyber is to look into the number of drivers compared to the number of rides in Urban City Types. There are 2,405 drivers but only 1,625 rides taken taken from January to April. Pyber will need to either increase the number of rides through marketing or relocate drivers to other city types. This will also decrease the gap between Average Fare per Driver in Urban city type compared to the Rural Average Fare per Driver. This will also make the Average per Driver more related to the Average Fare per Ride. Another disparity is the Suburban data not following the same pattern on line graph of Fares over the months of January to April. As all three types spike in late feb, Suburban City Type Fares do not increase again until later in April. Providing more drivers in Suburban cities through relocation or hiring in March will show an increase to the previous month as it did for Urban and Rural cities. Largest profit with the least cost is Rural City Types. Each additional new customer in this location will produce a larger profit than one new customer in Urban or Suburban cities. So, to take advantage of this will be to see where people are going to. If they are coming to the city for supplies or appointments, then we have drivers in rural areas carpool the customers to the city and then we have drivers who are without work available to take them home according to their individual schedules. These disparities in the data show that there are too many drivers supplied in Urban cities and that the demand in Suburban or Rural City types are unknown until we supply enough drivers to see what the actual demand is and see a line-graph that produces a true pattern.
