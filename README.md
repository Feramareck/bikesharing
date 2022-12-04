# Bike-Sharing


## Overview of the analysis:
The objective of this project is to analyze data from CitiBike in New York to verify the feasibility of creating a bike-sharing system in Des Moines, IA.

## Results:
For this analysis, data from the Citi Bike program in New York City (https://ride.citibikenyc.com/system-data) were used.  
We use data from August/2019 because there is likely more traffic during the summer months.  

Our first analysis was on the general numbers of the database, where we verified that the total number of rides was 2,344,224, where 65% of these numbers were male users, 25% female and 10% unknown.  
Looking at the type of user of the rides, 1,900,359 are annual subscribers, mostly male (58% of all rides held on 08/2019). Of the rides performed by women, the majority were also performed by annual subscribers. For those who declared themselves unknown, short-term customers prevailed.  

![Numbers_Rides](https://user-images.githubusercontent.com/111664141/205515101-2930cc7e-2f4c-47a6-86ed-0c6b640d2fa5.png)

[link to dashboard] https://public.tableau.com/app/profile/fernanda.reckziegel/viz/Number_of_Rides/Numbers_Rides?publish=yes

Analyzing the duration of the trips, we can see in the graph below that the absolute majority have a maximum duration of 20 minutes, with their peak being trips of 5 minutes.
![Length_Time](https://user-images.githubusercontent.com/111664141/205515261-b762e83c-08ea-4dc9-a245-58e791a78eb6.png)

[link to dashboard] https://public.tableau.com/app/profile/fernanda.reckziegel/viz/Length_of_Time/Length_Time?publish=yes

Analyzing the duration of the trips by gender, we can see that there was not much difference in the duration of the rides in the graph above.  
Peak runs for men are 5 minutes and for women are 6 minutes. For the unknown gender, we can analyze that there is no prominent duration time, with a homogeneous trend occurring up to 30 minutes.  
![Length_Time_Gender](https://user-images.githubusercontent.com/111664141/205515414-97c9342b-c7ca-4179-ba7d-27d2422330f9.png)

[link to dashboard] https://public.tableau.com/app/profile/fernanda.reckziegel/viz/Length_Time_Gender/Length_Time_Gender?publish=yes

In the heatmap below, we compare the start time of the rides with the days of the week for the stop times.  
The busiest time for rides is between 7a.m.-10a.m. and 4p.m.- 8p.m. on weekdays and between 10a.m.- 8p.m. on weekends. Peak usage occurs on Thursdays between 5p.m.-7p.m. The least used quadrant occurs on weekdays between 1a.m.-5am and weekdays 3a.m.-6a.m.
![Trips_Weekday](https://user-images.githubusercontent.com/111664141/205515539-a1d8c8a8-0539-46bb-9a2a-836d2a8f9974.png)

[link to dashboard] https://public.tableau.com/app/profile/fernanda.reckziegel/viz/Trips_Weekday/Trips_Weekday?publish=yes

Broken down the heatmap above by gender, we can see that basically the hourly peaks above refer to the amount of men and women, with a significant amount of the male gender. If we were to analyze unknown genres, we noticed that they are mostly used on weekends between 10a.m. and 7p.m.

![https://public.tableau.com/app/profile/fernanda.reckziegel/viz/Trips_Weekday_Gender/Trips_Weekday_Gender?publish=yes]

Still using the heatmap, we included the Usertype variable to identify the type of user by day of the week. In the heatmap below, we see that the highest usage by short-time customers occurs on Saturdays by gender unknown while annual subscribers are mostly male with their maximum usage on Thursdays and Fridays.
![https://public.tableau.com/app/profile/fernanda.reckziegel/viz/Trips_Gender_Type/Trips_Gender_Type?publish=yes]

In this last map, we analyze the start stations of the rides, filtering by gender, days of the week and start time. Without performing any filter, we verified that the most used stations for the beginning of the rides are those located in Midtown Manhattan, the busiest and most popular tourist destination in New York. If we filter by usage at the peak usage time of the week (Thursday at 5pm), the highest usage continues to be in this area. We can also visualize that the stations, the farther away from this region, the smaller the use for the beginning of the rides.
![https://public.tableau.com/app/profile/fernanda.reckziegel/viz/Station_Gender_Weekdays/Station_Gender_Weekdays?publish=yes]


## Summary:
Analyzing all the charts and maps above, we find that the greatest use of CitiBike in New York is by male people, annual subscribers with the highest concentration on Thursdays and Fridays between 5p.m. and 7p.m. We can also see that the most used region for the beginning of the rides is in Midtown Manhattan, the busiest and most popular region of the city, generally lasting no more than 20 minutes.
For a future analysis, it remains as a proposal to analyze in which region the final stations are located.
Below is the Tableau Story with all the charts and maps presented above.
![https://public.tableau.com/app/profile/fernanda.reckziegel/viz/Rides_16701050125100/Rides?publish=yes]
It would also be interesting to cross the information on the beginning and end of the rides, to verify if there is a pattern of use and if it is possible to link this use by workers or tourists.



