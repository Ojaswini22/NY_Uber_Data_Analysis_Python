# NEW_YORK_Uber_Data_Analysis_Python

 ## Introduction
 
 The objective of this project is to understand the traffic in different boroughs of New York City and to try and categorise the various zones within various boroughs as being: office destinations, residential destination, popular brunch destination or party destination according to it's popularity given the time-range and the day of the week.

I have used data generated by Uber, an online transportation network company. This data is available at Kaggle under the heading: 'Uber Pickups in New York City', provided by user: 'FiveThirtyEight' who obtained the data from the NYC Taxi Limousine Commission (TLC) by submitting a Freedom of Information Law request on July 20, 2015.


The directory downloaded contains data on over 4.5 million Uber pickups in New York City from April to September 2014, and 14.3 million more Uber pickups from January to June 2015. I have used Python to extract knowledge and mine the dataset.


The dataset downloaded contains:

#### Uber trip data from 2014 (April - September), separated by month, with location information (longitude - latitude values)

Uber trip data from 2015 (January - June), with less fine-grained location information
Non-Uber FHV (For-Hire Vehicle) trips. The trip information varies by company, but can include day of trip, time of trip, pickup location, driver's for-hire license number, and vehicle's for-hire license number.
Aggregate ride and vehicle statistics for all FHV companies (and, occasionally, for taxi companies)

### This project used two groups of files that was generated by Uber:

Uber trip data from 2014 (April - September)

Uber trip data from 2015 (January - June)

#### Uber trip data from 2014

There are six files of raw data on Uber pickups in New York City from April to September 2014 (uber-raw-data-xyz14.csv). The files are separated by month and each has the following columns:

  . Date/Time : The date and time of the Uber pickup

  . Lat : The latitude of the Uber pickup

  . Lon : The longitude of the Uber pickup

  . Base : The TLC base company code affiliated with the Uber pickup

#### Uber trip data from 2015

Also included is the file uber-raw-data-janjune-15.csv This file has the following columns:

  . Dispatching base num : The TLC base company code of the base that dispatched the Uber

  . Pickup date : The date and time of the Uber pickup

  . Affiliated base num : The TLC base company code affiliated with the Uber pickup

  . locationID : The pickup location ID affiliated with the Uber pickup

