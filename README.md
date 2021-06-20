# NYC CitiBike-sharing Program Analysis

## Overview of Project

### Purpose
The main goal of this analysis was to create a Tableau story using data collected from a NYC bike-sharing program that would convince investors that opening a bike-sharing program in Des Moines is a good business opportunity that should have their support. In order to do this, the data was used to create 7 visualizations that showed the popularity of starting locations in NYC, the popularity of ending locations in NYC, how long bikes were used, how long each gender group used the bikes, how often and when bikes were used on each day of the week, how often and when each gender group used the bikes on each day of the week, and how often and when each user type used the bikes on each day of the week. After these visualizations were made, they were put together into a Tableau story that can be seen [here](https://public.tableau.com/views/Module14Challenge_16241483567880/NYCBikeTripAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link).

## Results

### Visualization 1: Top Starting Locations
![](https://github.com/HannaKim4673/bikesharing/blob/main/Images/Figure%201.png)
The above visualization shows how often different NYC CitiBike starting locations are used. An interactive version of this visualization can be found [here](https://public.tableau.com/views/Module14Challenge_16241483567880/TopStartingLocations?:language=en-US&:display_count=n&:origin=viz_share_link). Given that a majority of the darker, larger circles are clustered around the Manhattan area, this figure suggests that starting locations in Manhattan are the most popular amongst Citibike users in NYC. This result may be due to the fact that there are many tourists that go to visit Manhattan. In turn, this suggests that it would be prudent to set up bike starting locations in popular tourist areas in Des Moines.

### Visualization 2: Top Ending Locations
![](https://github.com/HannaKim4673/bikesharing/blob/main/Images/figure%202.png)
The above visualization shows how often different NYC CitiBike ending locations are used. An interactive version of this visualization can be found [here](https://public.tableau.com/views/Module14Challenge_16241483567880/TopEndingLocations?:language=en-US&:display_count=n&:origin=viz_share_link). Comparing this visualization to the Top Starting Locations visualization reveals that the most popular starting places also tend to be the most popular ending places. This is most likely because the bike stands are at these locations, and bikes users are probably meant to return bikes to one of these stands once they are done using them.

### Visualization 3: Checkout Times for Users
![](https://github.com/HannaKim4673/bikesharing/blob/main/Images/Figure%203.png)
The above visualization shows how long bikes are taken out by users. An interactive version of this visualization with toggleable filters can be found [here](https://public.tableau.com/views/Module14Challenge_16241483567880/CheckoutTimesforUsers?:language=en-US&:display_count=n&:origin=viz_share_link). This visualization shows that most bike users tend to use the bikes for about 5 minutes before putting them back, and vey few users use the bikes for more than an hour. This finding implies that users prefer to use the bikes as a means of quick transportation as opposed to using the bikes for something that can take a long time like city tours.

### Visualization 4: Checkout Times by Gender
![](https://github.com/HannaKim4673/bikesharing/blob/main/Images/Figure%204.png)
The above visualization is essentially the same as the previous one, except that it shows how long users of each gender take out and use the bikes. An interactive version of this visualization with toggleable filters can be found [here](https://public.tableau.com/views/Module14Challenge_16241483567880/CheckoutTimesbyGender?:language=en-US&:display_count=n&:origin=viz_share_link). Along with the previous visualization, this one reveals that bike users from all gender groups prefer to use bikes for about 5 min instead of for longer periods of time, but male users in particular prefer to use the bikes as a means of quick transportation and generally use the bikes more often than female and unknown users.

### Visualization 5: Trips by Weekday by Hour
![](https://github.com/HannaKim4673/bikesharing/blob/main/Images/Figure%205.png)
The above visualization shows the frequency at which bikes are taken out and used at each hour of the day for each day of the week. The main finding of this visualization is that CitiBike usage in NYC peaks on Thursdays between the hours of 5 PM and 7 PM.

### Visualization 6: Trips by Gender (Weekday by Hour)
![](https://github.com/HannaKim4673/bikesharing/blob/main/Images/Figure%206.png)
The above visualization shows the frequency at which users of different gender groups use the bikes at each hour of the day for each day of the week. An interactive version of this visualization with toggleable filters can be found [here](https://public.tableau.com/views/Module14Challenge_16241483567880/TripsbyGenderWeekdayperHour?:language=en-US&:display_count=n&:origin=viz_share_link). This visualization reveals that male users are mainly the reason why bike usage peaks on Thursdays between 5 PM and 7 PM. Also, it supports the finding from visualization 4 that male users use the bikes more than female and unknown users.

### Visualization 7: User Trips by Gender by Weekday
![](https://github.com/HannaKim4673/bikesharing/blob/main/Images/Figure%207.png)
The above visualization shows the frequency at which users of different gender groups and customer types use the bikes at each hour of the day and each day of the week. An interactive version of this visualization with toggleable filters can be found [here](https://public.tableau.com/views/Module14Challenge_16241483567880/UserTripsbyGenderbyWeekday?:language=en-US&:display_count=n&:origin=viz_share_link). This visualization reveals that male and female users who are subscribers use the bikes more than their customer counterparts. Interestingly, the opposite seems to be true for users whose genders are unknown - i.e., subscribers use the bikes less than customers.

## Summary
Overall, the visualizations incorporated into the Tableau story revealed the following findings. First off, areas with large numbers of tourists see the most bike usage, and popular starting locations also tend to be popular ending locations, most likely due to the presence of bike stands at these locations. Secondly, users, regardless of what gender group they belong to, seem to prefer using the bikes for less than an hour at a time, which implies that the bikes are used for quick transportation and not for time-consuming activities like touring. Third, male users generally use the bikes more than female users and users whose genders are unknown. Fourth, bike usage in NYC seems to peak on Thursdays between 5 PM and 7 PM. Lastly, users who are subscribers generally use the bikes more than their customer counterparts.

In addition to the visualizations made for the story, the following two visualizations would also help to provide more useful information in further analyses: a line chart showing trip durations for users of different birth years and another line chart showing trip durations for the two user types.
