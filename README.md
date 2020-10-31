# bikesharing
Module 14 UT Data Visualization Bootcamp:  Tableau
<!---
Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:
There is a title, and there are multiple sections. (2 pt)
Each section has a heading and subheading. (2 pt)
Links to images are working and displayed correctly. (2 pt)
Analysis (24 points)
The written analysis has the following:
Overview of the statistical analysis:
The purpose of the analysis is well defined. (5 pt)
Results:
There are at least seven visualizations for the NYC Citibike analysis (7 pt)
There is a description of the results for each visualization (7 pt)
Summary:
There is a high-level summary of the results and two additional visualizations are suggested for future analysis (5 pt)
--->

## Overview

Purpose of this analysis is to perform a review of [Citi Bike Data](https://www.citibikenyc.com/system-data) for New York City using [Tableau](https://www.tableau.com/).
Data will have type modification using Python in Jupyter Notebook

## Results

[Link to Python Data Type Modification](https://github.com/jt-schmidt/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)

[Link to JSchmidt Citibike Tableau Story](https://public.tableau.com/profile/jeff.schmidt#!/vizhome/CitiBike_Challenge_16039379492890/Challenge?publish=yes)

Summary of Visualizations Used -- Including Summary Text found in Tableau
* [Course 1 Dashboard (Story pg1)]
(https://public.tableau.com/views/CitiBike_Challenge_16039379492890/Course1?:language=en&:retry=yes&:display_count=y&publish=yes&:origin=viz_share_link)
  1. Course:  Number of Trips
  2. Course:  Customer Type
  3. Course:  Gender Breakdown
  4. Course:  August Peak Hours
  5. Course:  Average Trip Duration
Summary Text:
 ``` 
  Page 1 of Course Exercises for CitiBike Analysis Using Tableau.
  Source Data = https://www.citibikenyc.com/system-data
  Initial Charts:
  --Total Number of Trips:  Raw count of records
  --Breakdown by Customer Type:  Subscriber Favored
  --Breakdown by Gender:  Male Favored & subset of indeterminant gender present
  --August Peak Hours:  High @ 5pm, Low @ 4am
  --Trip Duration based on Age:  Trending increase towards younger riders
  ```
* Course 2 Dashobard (Story pg2)
  1. Course:  Top Starting Locations
  2. Course:  Top Ending Locations
  3. Course:  Bike Repair Heatmap
  4. Course:  Bike Utilization Heatmap
Summary Text:
 ``` 
Map comparison of Start & End locations have no significant difference.  
However, highest density is downtown Manhattan region.

Example of Heat Map using Bike Repairs & Utilization.
Repairs offers no significant insight.
Distribution on Utilization is fairly uniform with random high spikes.
```  
* Challenge 1 Dashboard (Story pg3)
  1. Challenge:  Checkout Times for Users
  2. Challenge:  Checkout TImes for Genders
Summary Text:
 ``` 
Comparison of Checkout Time Duration of Overall versus Gender Breakdown shows how MALE riders skew majority of data trend.
For both genders, peak trip duration is 4~6 hours with FEMALE being slightly higher than MALE.
```  
* Challenge 2 Dashboard (Story pg4)
  1. Challenge:  Trips by Weekday per Hour Heatmap
  2. Challenge:  User Trips by Gender by Weekday Heatmap
Summary Text:
 ```   
Heat Map of rider count.

FIRST
Overall breakdown according to time of day and day of week.
This shows heaviest usage during peak commute hours of:
6am ~ 9am & 4pm ~ 7pm during Monday through Friday.
Weekend hours have even distribution throughout day from 10am ~ 5pm.

SECOND
Breakdown by Gender & User Type across days of the week.
Most significant observation is large MALE distribution on Monday, Tuesday, Thursday, Friday for Subscriber types.
```  
* Challenge 3 Dashboard (Story pg5)
  1. Challenge:  Trips by Gender (Weekday per Hour)
  
  Course Visualization Count = 9
  Challenge Visualization Count = 5
Summary Text:
 ```   
 Final heat map expands on the overall breakdown according to time of day and day of week.with inclusion of Gender display.

Observation continues to highlight majority of MALE riders.  
Of interest is that while FEMALE riders are fewer, their distribution of usage during weekdays and weekends is similar to MALE riders.

6am ~ 9am & 4pm ~ 7pm during Monday through Friday.
Weekend hours have even distribution throughout day from 10am ~ 5pm.
```

## Summary

Overall this was a very interesting first use of Tableau to visualize data.  The level of customization and additional features are apparent especially in relation to Excel used during beginning of course.  Additionally, the learning curve is not quite as steep compared to the Python & Javascript visualizations performed in previous modules.

If I were to explore this particualr data set further, I would consider a deeper dive into:
1.  Gender & User Type differences with the majority data sets removed (MALE & SUBSCRIBER) to see if there is any further detail which can be obtained from minority user groups.
2.  Consider application of time as a layer to the geographical mapping to visualize peak and trough usage over the course of the day and to check if there is any geographic relationship.
