# USA Flight Analysis
By Manal Akallas
## Overview </br>
 This is a part of Udacity Nanodegree project. The original dataset reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays, from 1987 to 2008.

I will analyse the domestic flights from USA 2008. The data set can be downloaded from http://stat-computing.org/dataexpo/2009/the-data.html.

Programming language: Python. Module: numpy, pandas, matplotlib, seaborn, calender and datetime
Data structure

## Data Structure
There are 7.009.728 observations in total and 29 columns.

## Variable descriptions

 - **Year**:     2004 - 2008
 - **Month**	           1-12
 - **DayofMonth**	       1-31
 - **DayOfWeek**     	   1 (Monday) - 7 (Sunday)
 - **DepTime**	          actual departure time (local, hhmm)
 - **CRSDepTime** 	       scheduled departure time (local, hhmm) 
 - **ArrTime** 	       actual arrival time (local, hhmm)
 - **CRSArrTime**	       scheduled arrival time (local, hhmm)  
 - **UniqueCarrier**	   unique carrier code                         
 - **FlightNum**	       flight number                        
 - **TailNum**	           plane tail number                    
 - **ActualElapsedTime**  in minutes
 - **CRSElapsedTime**	   in minutes
 - **AirTime**	           in minutes
 - **ArrDelay**	       arrival delay, in minutes
 - **DepDelay**	       departure delay, in minutes
 - **Origin**           origin IATA airport code
 - **Dest**	           destination IATA airport code
 - **Distance**	       in miles
 - **TaxiIn**	           taxi in time, in minutes
 - **TaxiOut**	           taxi out time in minutes
 - **Cancelled**	       was the flight cancelled?
 - **CancellationCode**   reason for cancellation (A = carrier, B = weather, C = NAS, D = security)
 - **Diverted**	       1 = yes, 0 = no
 - **CarrierDelay**	   in minutes
 - **WeatherDelay**	   in minutes
 - **NASDelay**	       in minutes
 - **SecurityDelay**	   in minutes
 - **LateAircraftDelay**  in minutes

Reference http://stat-computing.org/dataexpo/2009/the-data.html

## Data Wrangling


