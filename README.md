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
- The Distance and Distance vs. AirTime

## Analysis Results
### Cancelled Flights Anaysis:
- The weather is the number one cause for flight cancellation, shortly followed by carrier. The gap in between both of them is not large but rather very close. NAS is the third highest reason for flight cancellation. No flight cancellations have been reported because of security. I assume that there is an appropriate level and standards of security. Nevertheless, weather is something out of hand.
- There were more cancellations from October to December and in the first month of the year. The bad weather in the winter is most likely the reason behind all the cancellations. In the summer it seems to be the most stable throughout the whole year.
- The ratio of cancelled flights to all the flights might seem pretty low. However, in reality 2 percent of 7 million is 137434. That is a respectably high number.

### Diverted Flights Anaysis:
- The percentage of diverted flights is much lower than the percentage of cancelled flights. 0.2 percent of 7 million is only 17,265. That is almost 8 times less than the amount of cancelled flights.

### Delayed Flights Anaysis:
- The delayed flights ratio is 19.3%. The ratio is higher than both cancelled and diverted flights. 19.3 % is a very high number that is almost one fifth of flights being delayed.
- Most delays happen in December. This is probably caused by the Christmas holidays. If we look at June and July (when the summer holidays start) it is also pretty high. However, during Christmas more people leave and travel to other states or countries. In March there is Easter that is why the number in March is also high.
- Flights in the afternoon and evening are more delayed than early morning and night on any day of the week
- Flights delays are maximum on Friday and Sunday evenings at 8 pm
- The percentage of flights delayed at 3am shows higher than normal, but that is a result of bias created by considering percentages instead of the raw numbers.

### The relation between Distance and AirTime
- There is a positive moderate correlation between distance and airtime. That is convenient because the further the distance is the more time consuming it will be.


