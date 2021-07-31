# PyBer_Analysis

## Overview of the Anaylsis
This is an analysis of ride-sharing data to create a readiable chart of total rides, drivers, and fares as well as to calculate averages of rides and drivers between rural, suburban and urban cities. The data initially gathered in the attached data resources files provided no readible format to make comparisons nor provided averages and totals for each city type. 
Initial chart after merging data files:
![merged_data](https://user-images.githubusercontent.com/86267773/127724808-a82563db-63cf-41a0-a8ec-10c02631ca0d.png)

I used Python pull data from Janurary 1, 2019 to April 29, 2019 to make calculations and reformat those values into a new usable DataFrame. Then I incorporated Matplotlip library to provide a visual comparison of fares over time for the three different types of cities for V. Isualize and to make busness reccomendations to Pyber to address disparities between the city types. 

## Resources
- Data Sources:
  - city_data.csv
  - ride_data.csv
- Software: 
  - Python 3.7

## Results
New Summary DataFrame:

![Summary DataFrame](https://user-images.githubusercontent.com/86267773/127724816-9c163b4d-3383-41a8-8d99-a516f3c4ad9e.png)

First impression is the large average dollar amounts per driver in rural cities ($55.49) to urban cities ($16.57) and the small totals in rural cities ($4,327.93 Total Fares) to that of the Urban city types ($39,854.38 Total Fare). The suburbs are in the midde of the road with $19,356.33 Total Fares and $39.50 Average Fare per Driver. Simple take away as population density increases the cost to the customer is lower with possibly shorter trips, higher number of available drivers available, increase number of commuters. However, the differences between each value are unportional as we compare columns and the number of drivers compared to total number of rides is not equal. 

Line chart of Fares over Time:

![PyBer_fare_summary](https://user-images.githubusercontent.com/86267773/127725486-37f61106-1b0b-425c-80be-8e0466bb4b34.png)

Rural spikes every five weeks.
urban shows a steady increase coming out of middle of winter and fluctuates late winter to early spring. 
suburban hoves around the $1000 shows similar pead in late feb as rural and urban but does not show any form of pattern to take away other than its peak



## summary
long distances?
damand higher? hire drivers
increase profits ride shares(per ride more money)
increase of drivers during late feb to come out of cold months to prepare for spring. 
too many drivers in urban cities mid-late winter. 
demand to suppy of drivers in sububant show that it is not equal as there is no pattern. 


cities:
24.per ride by 16 per drivers?
Use your repository README file to write your analysis of how to address any disparities in the ride-sharing data among the city types.


Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
Deliverable 3 Requirements

Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections. (2 pt)
Each section has a heading and subheading. (2 pt)
Links to images are working and displayed correctly. (2 pt)
Analysis (14 points)
The written analysis has the following:


Results:

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)
Summary:

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)
