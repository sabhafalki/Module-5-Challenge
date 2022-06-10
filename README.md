# Module-5-Challenge_PyBer_Challenge
# Overview of Project #
The purpose of this Project is to analyze and visualize PyBer 2019 ride-sharing data, to help the company improve access to ride-sharing services and determine affordability for underserved areas. The data sample consisted of data from January to April months, for three regions: urban, rural and subburbon. 

The analysisis consisted of the following:
1. A Summarized DataFram of the ride-sharing data by city type
2. A Multiple-Line Graph that shows the total weekly fares for each city type

# Resources #
Data Source: city_data.csv, ride_data.csv  <br>
Software: Python, Anaconda, Jupyter Notebook <br>
Library Modules: Pandas, Numpy, Scipy.stats 

# Results #
The PyBer Summary DataFrame provides an overview comparison of PyBer's ride-sharing services in three types of cities: rural, surburban, and urban cities.

## Detailed Overview ##
### The Percentage of Total Rides by City Type ###
![Total_rides](/analysis1/total_rides.png)
<br><br>

We were able to conclude from the Pie Chart that there was a larger demand for PyBer ride serives among the urban cities, compared to suburban and rural cities. The above figure indicated that the Urban cities contributed to the most PyBer's rides overall over the five-month period.

### The Percentage of Total Drivers by City Type ###
![Total_Drivers](/analysis1/Total_drivers.png)
<br><br>

We were able to deduce that there were a larger number of drivers in urban cities compared to suburban and rural cities, for the given period of time. This is directly related to the total rides in the city.
 
### The Percentage of Total Fares by City Type ###
![Total_Fares](/analysis1/total_amount_of_fares.png)
<br><br>

Although the price fares are higher in Rural Regions, the ride count was substantially high in Urban Cities, and thus it generated the highest income, compared to suburban and rural ciites. Again, this coorelates to our previous findings, where we found out that the Urban Cities have the highest Total Drivers and hightest Total Rides.

## In-Dept Analysis ##
### PyBer Summary DataFrame ###
![summary](/analysis1/pyber_summary.png)
<br><br>

The average fare for rides in the rural cities is about $10 more per ride, than in urban and suburban cities. The average number of drivers in rural cities is nine to four times less per city, than in urban and suburban cities.

### Relationship Between the Average Fares, Total Rides and Drivers by City ###
The following bubble chart shows the relationship between the average fare price and the number of rides and drivers categorized by the different city types.

![scatterplot](/analysis1/PyBer_ride_sharing_Data(2019).png)
<br><br>

It is evident from the scatter plot, the as the total number of rides increases, the average fare per ride decreases. 

### The Total Fare by City Type ###
The following line chart shows the total fare by city type from January to April 2019.

![summary](/analysis1/PyBer_fare_summary.png)
<br><br>
The urban weekly total fare is around 9 and 2.25 times higher than rural and surburban ones respectively. 

## Conclusion ##
### Summary ###
The following could be observed from analyzing the PyBer ride-sharinge data:
1. Urban Region had the highest Total Ride count, followd by suburban and rural regions
2. Urban Region had the highest Total Riders, followd by suburban and rural regions
3. Urban Region had the highest Revenue, followed by suburban and rural regions
4. Rural Region had the highest Fares, followed by Urban and suburban regions
5. From the Dataframe, it is evident that the drivers in the rural cities are earning the highest, followed by Suburban and Urban
6. Suburban Drivers were only about 17% of the total drivers but accounted for more than 30% of the total fares and just above a quarter of the rides.

### Business Recomendations ###
1. The highest revenue generated was from Urban Regions. It might be worthwhile to expand in Urban Regions where PyBer does not have a presence. 
2. Since the lowest revene generated was form Rural Regions, furhter analysis should be conducted to understand the reason. Whether this is because of low demand, or is it because of the lower number of drivers. This research can help PyBer in either increasing, decreasing or spreading out the drivers. 
3. Janurary seemed to have the lowest revenue, while March had the highest revenue generated for the regions. Hence, it might be better to introduce promotions in Janurary to promote revenue.

### Further Analysis ###
1. There is one outlier in the rural fare data. This may indicate that there could be an error in the data.
![Outlier](/analysis1/PyBer_fare_outliers.png)
<br><br>

2. There could be a correlation to the total population in a particular region, and the total revenue generated there. We need to get more details around the   population, infrastructure and economic activity to better understand this correlation. 
3. There could alo be certain locatinos within a region, which constitue a high number of riders and revenue. We should get additional data to determine this. 
4. We also do not have information on the duration of the ride, which could be useful.
5. It appears that the higher costs is directly related to the lower number of Rides. However, if we gather additional information around traveling distance, cellphone coverage, availability of drivers, etc.
6. We should also try to calculate the average total revenue earned by a driver
7. We should also try to establish the correlation between supply and demand
<br>
