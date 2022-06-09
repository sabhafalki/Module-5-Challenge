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
We were able to conclude the following from our analysis:
- District Summary Overview (i.e. Effects of Cleaning Up Data) <br>
The Updated Summary (i.e. cleand up data) indicates the following:
  - Average Math Score dropped by 0.01
  - Average Reading Score didn't change
  - Passing Math % dropped by 0.2%
  - Passing Reading % dropped by 0.3%
  - Overall Passing Percentage dropped by 0.1%
<br>
The effect of cleaning up the code had nominal impact on the outcome. 

![DistrictSummaryOriginal](/Screenshots/DistrictSummaryOriginal.png)
![DistrictSummaryUpdated](/Screenshots/DistrictSummaryUpdated.png)
<br><br>

- School Summary Overview (i.e. Effects of Cleaning Up Data) <br>
The Updated Summary indicates the following for Thomas High School:
  - Average Math Score dropped by 0.1
  - Average Reading Score dropped by 0.2
  - Passing Math % dropped by 0.1%
  - Passing Reading % dropped by 0.2%
  - Overall Passing Percentage dropped by 0.3%
<br>
The effect of cleaning up the code had nominal impact on the outcome. 

![SchoolSummaryOriginal](/Screenshots/SchoolSummaryOriginal.png)
![SchoolSummaryUpdated](/Screenshots/SchoolSummaryUpdated.png)
<br><br>

- Thomas High School's Performance after Cleaning Up Data (i.e. Replacing 9th Graders' Math and Reading Scores) <br>
After cleaning up the data, Thomas High School is second highest school after ranking based on Overall Passing Percentage. The impact of the changes were nominal to impact the outcome.

![SchoolSummaryUpdated](/Screenshots/SchoolSummaryUpdated.png)
<br><br>

- Impacts of Replacing Ninth-Grade Scores for Thomas High School <br>
  - Math and Reading Scores <br>
  The Math and Reading Scores for 9th Grade were Nan (i.e. Null). The rest of the data was unimpacted. 
  
  ![ScoresByGradeOriginal](/Screenshots/ScoresByGradeOriginal.png)
  ![ScoresByGradeUpdated](/Screenshots/ScoresByGradeUpdated.png)
  <br><br>
  
  - Scores by School Spending <br>
  Thomas High School falls in the Range of "$630-$644", and hence the following fields were impacted:
    - Average Match Score dropped by 0.01
    - Average Reading Score dropped by 0.01
    - Passing Math Percentage dropped by 0.02%
    - Passing Reading Percentage dropped by 0.08%
    - Overall Percentage dropped by 0.1
    The changes to the outcoem were nominal. 
  
  ![SpendingSummaryOriginal](/Screenshots/SpendingSummaryOriginal.png)
  ![SpendingSummaryUpdated](/Screenshots/SpendingSummaryUpdated.png)
  <br><br>
  
  - Scores by School Size <br>
  Thomas High School falls in the "Medium - 1000-2000" Range, hence the other two Ranges were not impacted. The following could be observed for the Medium Range:
    - Average Match Score dropped by 0.01
    - Average Reading Score dropped by 0.01
    - Passing Math Percentage dropped by 0.01%
    - Passing Reading Percentage dropped by 0.06%
    - Overall Percentage dropped by 0.1
    The changes to the outcoem were nominal.   

  ![SchoolSizeSummaryOriginal](/Screenshots/SchoolSizeSummaryOriginal.png)
  ![SchoolSizeSummaryUpdated](/Screenshots/SchoolSizeSummaryUpdated.png)
  <br><br>

  - Scores by School Type
  Thomas High School is a Charter Type of Schools, and hence District School overview was not impacted. The following were noticed for Charter Type:
    - Average Match Score dropped by 0.01
    - Average Reading Score dropped by 0.01
    - Passing Math Percentage dropped by 0.01%
    - Passing Reading Percentage dropped by 0.03%
    - Overall Percentage dropped by 0.1
    The changes to the outcoem were nominal. 
  
  ![SchoolTypeOriginal](/Screenshots/SchoolTypeOriginal.png)
  ![SchoolTypeUpdated](/Screenshots/SchoolTypeUpdated.png)
  <br><br>

# Summary of Outcome #
The following could be observed about the outcome after modifying the data:
1. Since Thomas High School is a Charter Type of School, the District Summary outcome was effected. However, the effect was nominal. 
2. Since Thomas High School is a Mid Size School (1000-2000), the Size Summary outcome for Mid Size School was effected. However, the effect was nominal. 
3. Since Thomas High School fell under the $630-$644 Spending Range, this outcome was also effected. However, the effect was nominal. 
# Further Analysis #
1. There is one outlier in the urban ride count data. Also, the average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and    suburban cities
5. The Rank of the school was unaffected even after NaNs were applied to Grade 9 Reading and Math Scores
<br>
