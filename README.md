# Citi_Bike

[link to dashboard](https://public.tableau.com/app/profile/christopher.williams6505/viz/CitiBike_16464090634030/CitiBike)

## Overview

The purpose of this repository was to create visualizations of NYC Citi Bike data in order to determine if the business plan was feasible to be translated to Des Moines, IA. Citi BIke is a service where users can rent bikes and ride them for a specific duration, similar to Bird Scooters or an Uber. They all offer different modes of transportation for people needing to get around. These business specializing in this type of transportation do very well in densely populated cities, but it is unclear how they would perform in a city like Des Moines, IA.

The visualizations created would aid potential investors by higlighting relationships within the collected data. Information on user habits as well as bike usage could mapped out so that investors could determine if this business could be effective in less populated cities.

Before visualizations could be created, the data that was used for this project first needed to be cleaned. Python and the Pandas library was used to ensure all the data was in the correct form, cleaning specific columns as needed. Once the data was cleaned, a csv file was exported to Tableau. Tableau is a great visualization tool however it is unable to feasibly adjust data onced it has been loaded. So it was important that our data was in the form we wanted before creating visualizations.

In Tableau, many visualizations were created to highlight relationships in the data that could be used to draw conclusions. The following were created in Tableau,

1. Heat Map showing Number of Trips by time of day and day of the week.
2. Heat Map showing Number of Trips by time of day and day of the week, filtered by Gender. 
3. Heat Map showing Number of Trips day of the week and gender, filtered by customer type. 
4. Plot showing Number of Trips by duration, filtered by hour. 
5. Plot showing Number of Trips by duration, filtered by hour and gender. 
6. Map of Starting Locations, adjusted by size and color. 
7. Grid of Bike ID's and Number of Trips, used to determine need of Bike Repairs.


## Results

1. Heat Map showing Number of Trips by Time of Day and Day of the Week.

![alt text](https://raw.githubusercontent.com/KitWilliams07/Citi_Bike/main/Screenshots/StopTime.png)

This Heat Map shows that the peak usage is around 8am and 5pm on weekdays and all day on Saturday and Sunday. 


2. Heat Map showing Number of Trips by Time of Day and Day of the Week, filtered by Gender. 

![alt text](https://raw.githubusercontent.com/KitWilliams07/Citi_Bike/main/Screenshots/Gender:StopTime.png)

This Heat Map shows the same trends as above, except it is filtered by Gender. This shows that the bikes are more commonly used by men. 


3. Heat Map showing Number of Trips Day of the Week and Gender, filtered by Customer Type. 

![alt text](https://raw.githubusercontent.com/KitWilliams07/Citi_Bike/main/Screenshots/Gender:Usage:User.png)

This Heat Map shows similar relationships as the previous two but with an added element of user type. This shows that most bike riders are subscribers rather than one time riders. 


4. Plot showing Number of Trips by Duration, filtered by Hour. 

![alt text](https://raw.githubusercontent.com/KitWilliams07/Citi_Bike/main/Screenshots/TripDuration.png)

This plot shows that most of the trip durations are between 5 - 20 minutes. Since the plot is filtered by hour, it shows that no rides were longer than an hour. 


5. Plot showing Number of Trips by Duration, filtered by Hour and Gender. 

![alt text](https://raw.githubusercontent.com/KitWilliams07/Citi_Bike/main/Screenshots/TripDuration:Gender.png)

This plot shows the same data as the previous plot, except filtered by gender. This shows that the duration of the trips were the same between men and women, but again there are just more users who are men.


6. Map of Starting Locations, adjusted by size and color. 

![alt text](https://raw.githubusercontent.com/KitWilliams07/Citi_Bike/main/Screenshots/StartingLocations.png)

This map shows the starting locations of the trips. They seem to be decently spread out but there are peaks in more populated areas (AKA Manhattan).


7. Grid of Bike ID's and Number of Trips, used to determine need of Bike Repairs.

![alt text](https://raw.githubusercontent.com/KitWilliams07/Citi_Bike/main/Screenshots/BikeRepair.png)

This grid shows the distribution of rides per bike. The lower right bikes have seen the fewest use and therefore are not needing repair. The top left bikes have seen the most use and should be monitored to determine if repairs are needed.


## Summary 

Based on the results, a few conclusions can be drawn.

From the heatmaps, it is clear that during the week the most usage comes around 8am and 5pm. This is because people are using the bikes to commute to and from work. Additionally, there is a steady usage of bikes on Weekends throughout the day. This is most likely due to people enjoying their weekend whether for a joy ride or to go places that aren't specifically reliant on time (AKA not work). Additionally, the heatmaps show that the bikes are more used by men compared to women. Finally, more of the bike users are regular subscribers rather than a one time customer. 

So to summarize the heatmaps to the investors, the most bike usage is from men going to and from work who are subscribers to the business.


Based on the plots of trip durations, most of the trips are quick, around 5 - 20 minutes. Des Moines is more spread out than NYC so it would be wise to set up the bikes as central as possible. Or consider putting stations of bikes spread out over the less populated areas. 

The map shows that more bikes are being used in more populated areas. Putting numerous bikes in the downtown area of Des Moines would be effective. Additionally, encouraging people to subscribe is a good move because most of the bike usage comes from those who rely on the bikes for work transportation.

In terms of Bike Repairs, bikes in Des Moines would most likely see less rides than NYC so less repairs means less costs which is a plus.


While these visualizations cannot say for certain whether Citi Bike would do well in Des Moines, they do help to paint a picture that investors can use to make their own decisions. In order to make a more clear decision on this, a few more visualizations could be made with different data. 


One suggestion is to log the money each bike earns. Meaning, each trip is logged for each bike, so you could quantify the total trip cost that the company makes for each bike. You can then compare the money each bike makes compared to the money spent on repairs based on a certain number of rides. This would create an effecienecy for each bike. You could create a plot that plots the overall net gain based on number of trips. You could take this further and compare to the total number of trips. From the plot you can identify the most "effecient bike" in terms of making money on a certain number of rides and then put out enough bikes to keep up with the demand of total rides but stays close to this "efficiency number".

Another suggestion is to log the types of bikes. I don't believe that all of the bikes in NYC are all the exact same. So logging data on the type of bike could be important when determining bike repairs. If a specific type of bike is more inclined to need repairs then it would be more cost effective to use another type. You could create a figure that displays all the different types of bikes and the figure can be adjusted by the frequency of repair as well as the cost. 

