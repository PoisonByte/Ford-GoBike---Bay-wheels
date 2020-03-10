# Ford GoBike - Baywheels
## by Serena Zatara


## Dataset

> This document will explore the Ford GoBike's trip data for public containing approximately 295,854 bike rides for January 2020. "With a Ford GoBike membership, you get the first 45 minutes free, not just the first 30." With this report this will be an analysis of membership/subscriber usage and the duration of usuage for the launch of Ford GoBike now under Baywheels for 2020.

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


## Key Insights for Presentation

> The Count of user of bikes Customers totaled at 124,866 Subscribers totaled at 170,988. That's a total of return bike rides of 295,854 with Market St at 10th St to top start point and San Francisco Caltrain(Townsend St at 4th St) most popular end point. With both user type together and seperate Friday would be our profitable day with Wednesday and Thursday following. Interestingly even though there a high usage of bike per Wednesday through Friday. This data shows bikes being used longer on Saturday and Sunday.