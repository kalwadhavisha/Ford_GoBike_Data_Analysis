# Ford GoBike Data Analysis

Data Analysis/Data Visualization Report: Bike Ride Trends and Biker Types of Ford GoBike System February, 2020

Dataset This document explores the Ford GoBike's trip data for public containing bike rides for the month of February 2020. The attributes included the trip start/end latitude/longitude, as well as additional measurements such as user type, rental access methods. About 90k data points were removed from the analysis due to missing values in some fields, data inconsistent, or outliner issues.

## Data Source

The dataset, 202002-baywheels-tripdata.csv, is downloaded from https://s3.amazonaws.com/baywheels-data/index.html and licensed by Ford GoBike.
Each trip in this dataset is anonymized and includes:

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)

## Summary of Findings

1. Bike rides on weekdays had greater usage durations than those on weekends.
2. Bike rides were used maximum on Thursdays.
3. The peak usage time was at 8 AM and 5 PM on weekdays.
4. Customer user type using App rental access method used the bike for more number of minutes.
5. Subscriber user type peak usage is on Thursday and Customer user type peak usage is on Saturday
6. Higher variations and higher count in the usage of bikes is seen with a Subscriber data user than with the customer user type
7. Average Trip duration for a customer user type (18 minutes) is greater than the average trip duration of a subscriber user type (12.5 minutes)
8. Most of the rides are within 100 minutes with an average ride time/most frequently occuring ride time of 13 minutes.
