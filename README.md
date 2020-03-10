# Ford-GoBike---Bay-wheels
Data Analysis of Ford GoBike - Bay wheels - January 2020 data
> This document will explore the Ford GoBike's trip data for public containing approximately 295,854 bike rides for January 2020. "With a Ford GoBike membership, you get the first 45 minutes free, not just the first 30." With this report this will be an analysis of membership/subscriber usage and the duration of usuage for the launch of Ford GoBike now under Baywheels for 2020.

Data Info Provided:
>Trip Duration (seconds)
Start Time and Date
End Time and Date
Start Station ID
Start Station Name
Start Station Latitude
Start Station Longitude
End Station ID
End Station Name
End Station Latitude
End Station Longitude
Bike ID
User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)

>Cleaning Data
Define
start_station_id and end_station_id should be string
start_time and end_time are objects and should be datetime
user_type should be category
bike_share_for_all_trip should be category
Obtain Start month name, month number, weekday
Obtain End month name, month number, weekday
Obtain duration hours and min

>Looking through the data I plan to provide a report for bike users for 2020 to help provide a look at the start for the first month trends for future forecasting.
>This will include looking into the following:

1. Bike demand for weekday for the first month report, and for furutre schedule planning
2. The current duration of time spent on bikes
3. The users type- subscriber vs customer
4. Top most popular start and end locations

## Summary of Findings

> With the output I was able to discover for the first month report there was a higher usage in subscriber's. The max usage was aprox 13 min with most usage starting and ending on Friday, Wednesday and Thursday showing a mid week rise then previously thought. Top start point is Market ST at 10th ST and end point San Francisco (Townnsend ST at 4th ST)

> Showing for both customers and subscribers a high mid week usage, but for subscribers Wednesday and Thursday are almost equal in usage. It shows a not a high weekend usage. Still showing subscribers to be utilizing the bike more for duration time.
> I did find interesting for duration with weekday I found Saturday and Sunday to be higher with the output.
> I found the percentage of bikes rides per weekday by now using the bike_id data. Once calculated it continues to support the month of January had over mid week high usage with Friday, Wednesday and Thursday in ranking order.
I took the start time, duration by minutes and user type and ploted them together. I repeated the same process switching out the start time with end time. I also continued the process with the duration by hours finding subscribers to have a higher result for sunday. 
> Interestingly enough I found once these three data collection were plotted together subscribers used bikes more requently on thursday. However on remaining days customers are showing a longer duration of bike usage highest on Saturday, Friday and Wednesday. Could be due to high tourist days in the middle of the week and weekends, and could explain why subscribers which could be local residents decide to bike longer on sundays when tourist may leave.
