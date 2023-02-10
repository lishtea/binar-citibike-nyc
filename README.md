# Citbike Rental Overview Report
Dataset taken from Google's public bigQuery with table ID `bigquery-public-data:new_york_citibike.citibike_trips`.

## Overview
Citi Bike is NYC’s official bike share program, designed to give residents and visitors a fun, affordable and convenient alternative to walking, taxis, buses and subways. 

Using the data from 2015 - 2016 we're analyzing the data to look for: 
1. Total trip
2. Average trip duration
3. Average bike trip per day
4. Average bike numbers used daily
5. Top start station
6. Top bikes used
7. Daily trend
8. Trip duration from user's gender
9. Most used bikes

## Result
Tools : SQL query using google BigQuery, Data visualizaton using Looker Studio (GDS). 

Firstly, let's take a look at the overall analysis.

- Overall Analysis
![image](images/1.jpg)

To answer previous questions : 
1. Total trip made is over 3 million trips over a year (2015 - 2016)
2. Average trip duration is 979 seconds or around 27 minutes per trip. 
3. Average bike trip per day is over 30,000 trips a day.
4. Average bike numbers used daily is over 4,500 bikes everyday.

We also put that the furthest trip made in the year is over 8 km while the average trip people made is around 1,8 km.

With the number of bike used increased every year, we can safely assume that so far in until 2016, the citibike business is thriving. More people used bike every year.
From average trip duration per month in the year 2015 to 2016, we can see there are ups and downs. Especially in October to March, there are less people using the bike probably due the weather since it's winter and too cold to bike. 
The same can be said on June where the number also decreased, probably due weather. It is possible in June they had common rain, or even storm which made them impossible to ride. 

- Top Start Station & Used Bike
![image](images/2.jpg)

- Favorite Biking Day
![image](images/3.jpg)
We can see from the chart, that user most likely biking on Wednesday or Thursday over the weekends. This probably because more user having other events or even just staying at home resting on weekends. This means that citibike needs to prepare for a lot of bike stock ready to use during the time. 

- Customer Segmentation
![image](images/4.jpg)
We breakdown our user to their gender, but since it is not mandatory to fill when registered there are a lot of "unknown" user. 
From gender, we can also see that male user ride faster than female users, probably because they like to speed up during biking. 

But what's with the unknown user? Why they have longer duration?

- User Age
![image](images/5.jpg)

- User Type
![image](images/6.jpg)
