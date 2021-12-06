# CitiBike NYC Bike Data

## Overview
Analysing publicly available data from Citibike NYC to inform if it is profitable to start a bike share program in Des Moines. 
Using Python to re-format the data and tableau to visualise the data and showcase the insights.  

### Products used
- Tableau Public
- Python 
  - Pandas
  - datetime

### Link to tableau 
[Dashboard/Story](https://public.tableau.com/views/citibike_challenge_16387466468210/Citibike_story?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)  

## Using Pandas to re-format the datatypes

Using the Pandas and Datetime libraries in Python, we reformat the trip-duration data which is an integer into a datetime format.  
![datetime](Images/python.png)  

## Analysis
### Insight 1: Most trips are just 5 minutes in duration.
![check-out-time](Images/checkout_time_user.png)
### Insight 2: Men take 3X more trips than women, however, women have a marginally longer trip duration
![check-out-time-gender](Images/checkout_time_gender.png)
### Insight 3: Avoiding traffic is the main reason why people choose our bikes. The peak bike usage coincides with the usual peak-traffic hours. Our bikes help alleviate a pain-point of being stuck in traffic.
![trips-by-weekday](Images/trips_by_weekday_per_hour.PNG)  

As per the above image, we can also hypothesise that people take our bikes to and from work.  
*The working male is an important demographic. However we also have opportunities to develop the women and weekend segment of the bike-share market*  
![trips-by-weekday-gender](Images/trips_by_gender_weekday_per_hour.png)
### Insight 4: 


