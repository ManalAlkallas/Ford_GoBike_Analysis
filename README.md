# USA Flight Analysis
By Manal Akallas
## Overview </br>
 This is a part of Udacity Nanodegree project. The original dataset reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays, from 1987 to 2008.

I will analyse the domestic flights from USA 2008. The data set can be downloaded from http://stat-computing.org/dataexpo/2009/the-data.html.

Programming language: Python. Module: numpy, pandas, matplotlib, seaborn, calender and datetime
Data structure

## Data Structure
There are 7.009.728 observations in total and 29 columns. 

## Variables
'Year', 'Month', 'DayofMonth', 'DayOfWeek', 'DepTime', 'CRSDepTime','ArrTime', 'CRSArrTime', 'UniqueCarrier', 'FlightNum', 'TailNum',
       'ActualElapsedTime', 'CRSElapsedTime', 'AirTime', 'ArrDelay',
       'DepDelay', 'Origin', 'Dest', 'Distance', 'TaxiIn', 'TaxiOut',
       'Cancelled', 'CancellationCode', 'Diverted', 'CarrierDelay',
       'WeatherDelay', 'NASDelay', 'SecurityDelay', 'LateAircraftDelay'

Reference http://stat-computing.org/dataexpo/2009/the-data.html

## Research questions

In this investigation, I wanted to analyse:
- Cancelled Flights, What is the main reason behind the Cancelling flights, and what Cancelled Flights ratio.
- Diverted Flights, What is the Diverted Flights ratio
- Delayed Flights, What is the main reason behind delaying flights, and what delayed Flights ratio.
- The Distance and Distance vs. AirTime¶
