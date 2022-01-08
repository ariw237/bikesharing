# bikesharing
## Overview  
Citi Bike is a privately owned bicycle sharing system serving New York City and Jersey City named after lead sponsor Citigroup.  Data for ridership for August of 2019 has been provided from which analysis is being used to determine the feasibility of starting a similar system in another city. An overview of the bike trip data analysis follows. See the following detailed visualizations on Tableau Public: [Link](https://public.tableau.com/app/profile/ar3196/viz/CitiBikeVizs/CitiBikeOverview)
## Results  
### Peak Usage  

![august_peak_hours](https://user-images.githubusercontent.com/60231630/148628494-59bb9fb0-c3de-4cb6-a693-a75a8ee31b95.png)  

The data show two periods of usage between 7 and 10 am and 4 and 8 pm. Lowest usage is during the early morning hours between 2 and 5 am.  

###  Bike Utilization for the entire month
![bike_utilzation](https://user-images.githubusercontent.com/60231630/148628598-1fe6bd88-69dd-4d2e-b17b-fa287b241924.png)  

This plot simply depicts total time a particular bike (based on bike ID) was in use. Larger circles correspond to bikes with longer total usage. Bikes with longer usage times are likely to require more frequent maintenance.



### Peak Trip Start Locations  


![starting_locations](https://user-images.githubusercontent.com/60231630/148628640-99bc209f-9c94-4196-9026-324569ef5394.png)  

### Peak Trip End Locations  


![end_locations](https://user-images.githubusercontent.com/60231630/148628656-83fc0f87-03de-4e89-a31a-3d3f765175a3.png)  

The greatest number of trips (both starting and ending locations) appear to be centered in Manhattan area.

### Overall Trip Durations  

![trip_duration](https://user-images.githubusercontent.com/60231630/148628678-a453411d-0e9c-4f7d-b6e3-c7b21580e8b8.png)  

The vast majority of bike trips last less than one hour with the most frequent usage times of approximately 20-30 minutes.

###  Overall Trip Durations based on Gender  

![trip_duration_gender](https://user-images.githubusercontent.com/60231630/148628692-a324c2bb-121f-414c-97ef-12ab83b2d6dc.png)  

A higher level of usage is noted for males but a substantial amount of gender data is missing.

###  Number of Trips for each hour/day  

![start_time_by_week_hour](https://user-images.githubusercontent.com/60231630/148628725-4313192e-709c-4192-8783-3d6f0166ef14.png)  

The majority of trips are intiated on weekdays with slightly less usage on Wednesday.  Peak usage on weekdays is between 7 and 10 am and between 4 and 8 pm. Weekend usage is more evenly distributed between the hours of 10 am and 5pm.

###  Number of Trips for each hour/day based on Gender  

![start_time_by_week_gender](https://user-images.githubusercontent.com/60231630/148628739-41a2c92a-c052-4fff-ba1b-7791b97a4c6d.png) 

A similar pattern is noted when trips are broken down by gender. As noted earlier, male usage is higher.

###  Number of Trips for each day based on Gender and Usertype  

![start_time_by_week_usertype](https://user-images.githubusercontent.com/60231630/148628751-00312f30-8abc-409e-b4f3-64726d4bb254.png)  

Subscribers have higher levels of usage compared to non-subscribing customers.

## Summary  
Based on the data we see some general helpful trends. Peak demand for bikes overlaps with general rush hour times during the workweek with peaks during the morning and evening times. Usage is generally higher among males and most trips last between 20-30 minutes. A subset of bikes appear to be utilzed more often based on total amount of time of usage during the one month period and those bikes are likely to have more "wear" and "tear".  On weekends we see a more general trend of usage during the later morning through early evening hours with lesser usage compared to weekday peak times. Along these lines we note that subscribers are more likely to make use of the bike sharing program compared to one-time customers. A couple of additional visualizations would benefit this data.  For example, average distance traveled during usage might provide insight into how much time a bike is spent being ridden during the checkout period. Likewise a geographic representation of routes taken by a subset of bikes with the highest usage might also help for planning purposes.


