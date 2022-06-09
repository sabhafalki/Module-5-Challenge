# Module-5-Challenge_PyBer_Challenge
# Overview of Project #
The purpose of this Project is to analyze and visualize PyBer 2019 ride-sharing data, to help the company improve access to ride-sharing services and determine affordability for underserved areas.

The analysisis based on the following points among the different city types:
1. Create a ride-sharing summary DataFrame by city type.
    - Calculate total rides, total drivers and total amount of fares for each city type.
    - Calculate the the average fare per ride and the average fare per driver for each city type to create pyber summary DataFrame.    
2. Create a multiple-line chart of total fares for each city type to show the total weekly of the fares .
    - Remove MultiIndex by useing reset_index to remove one or more levels.
    - Reshaped a given DataFrame By using pivot() fuction. 
    - Use to_datetime() method to convert string Date time into Python Date time object.
    - Convert the time series data points index into time order by using dataframe.resample() function. 
    - Plot the chart.
    
# Resources #
Data Source: students_complete.csv, schools_complete.csv  <br>
Software: Python, Anaconda, Jupyter Notebook <br>
Library Modules: Pandas, Numpy, Scipy.stats 

# Results #
We were able to conclude the following from our analysis: <br>
The PyBer Summary DataFrame provides an overview comparison of PyBer's ride-sharing services in three types of cities: rural, surburban, and urban cities.
### The percentage of total rides by city type ###

  ![Total_rides](/analysis1/total_rides.png)
 <br><br>
The summary demonstrates that there is a larger demand for PyBer rides serives among the urban cities compared to suburban and rural cities. The above figure represents Urban cities contributed the most to PyBer's overall rides during this five-month period.
### The percentage of total rides by city type ###

 ![Total_Drivers](/analysis1/Total_drivers.png)
 <br><br>
There are a larger volume of drivers in urban cities compared to suburban and rural cities.The figure above signify the large number of drivers in urban cities during 
this period of time.
 
### The percentage of total fares by city type ###

  ![Total_Fares](/analysis1/total_amount_of_fares.png)
 <br><br>

The rides count in Urban cities is more that compare to the suburban and rural cities, but the fares price is higher in Rural area.The figure above demonstrates where the majority of PyBer's revenue occurred during this period of time that is urban cities.

### The average fare per ride and driver by city type ###
The following bubble chart shows the relationship between the average fare price and the number of rides and drivers categorized by the different city types.

![scatterplot](/analysis1/PyBer_ride_sharing_Data(2019).png)
  <br><br>
  
### The total fare by city type ###
The following line chart shows the total fare by city type from January to April 2019.

![summary](/analysis1/PyBer_fare_summary.png)
  <br><br>
The urban weekly total fare is around 9 and 2.25 times higher than rural and surburban ones respectively. 
# Summary of Outcome #
The following could be observed of PyBer ride-sharinge data:
1. PyBer ride-sharing services would not be the first option for travels as the fares are pretty high. 
2. Drivers in rural cities are earning more than drivers in urban cities. This could discourage potential drivers from working with PyBer given the low average fare
   per driver.
3. The general tendencies is high number of drivers and rides goes with medium to low fare.
4. Suburban drivers were only about 17% of the total drivers but accounted for more than 30% of the total fares and just above a quarter of the rides.
# Further Analysis #
1. There is one outlier in the rural fare data. The average weekly fare price of rural cities is about 3.4 and 4 times lower per city compare to the suburban cities      and the urban cities.

     ![Outlier](/analysis1/PyBer_fare_outliers.png)
<br><br>
2. Geographic maps must be include in the the app for better use. 
3. On the scatter plot, we notice some urban cities with low average fare but pretty high count of rides. Analyzing the average number of drivers against the 
   population and infrastructure and economic activity in those cities would help understand those disparities.   
4. Determine other factors that are contributing high ride costs in rural cities and low driver fares in urban cities. Factors such as travel distances, cellphone        coverage would be needed to get a clearer picture.      

<br>
