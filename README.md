# Overview of PyBer Analysis
The whole process of analysis and data visualization were kind of remind of Uber. We had two data sets: ride data with location, date and fare for every ride, and city data which describes type of city and number of drivers. Our goal was to compare quantity and fares of rides in different city types and based on our datasets we had to make data visualization like different types of charts and diagrams with matplotlib library ( using Jupyter Notebook and Pandas ) to let the CEO know the performance in each city types. Also when we are showing our analysis results as data visualization (charts, graphs, etc..), our data is more clear to someone who does not have that much idea of analyzing processes.

# Results
After merging two data sets and using the groupby() functions, the fare per ride and fare per driver averages were calculated resulting in the summary DataFrame by city type.

<img width="607" alt="Screen Shot 2022-04-10 at 11 40 05 AM" src="https://user-images.githubusercontent.com/100812201/162627523-381b19b2-3023-47f7-b19a-0dcb7f1e35d9.png">

The surprising part for me was when I notices even though the urban area had way more drivers and rides compare to rural, but it had way more less fare per ride and also fare per driver.

Also, rural area had the least number of drivers that is why it has the most average fare per driver, even though the ratio of total rides to total drivers is similar to suburban. 

Also, I created total fare by city type chart. Based on that urban area had more total fare, after that was suburbuan and then rural area.

![PyBer_fare_summary](https://user-images.githubusercontent.com/100812201/162628745-4e8852e4-64dc-4416-9b88-eccfeadf225d.png)


# Recomendations
First of all I would recommend to reduce the number of drivers in urban cities, compare to the results, there are 2405 drivers but the total rdies are 1625, which means 780 drivers would not get even one ride. I would say with applying some restrictions to hire drivers like driving record check or having full driver's license we can easily reduce the drivers number.
Another recommendation that I have is to give every dirver an area like if a dirver lives in urban city, and he is in downtown, he can only take trips in downtown (based on his address on his driver's license). 
Also, the other reason that the total of rides are a lot in urban city compare to others is because the urban areas are compact and mostly everything is close by, rather than rural or suburban, so with Pyber analysis we can calculate the trip duration and also the milage and then go from there.
