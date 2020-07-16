# (Ford GoBike Data Exploration)
## by (Abdulrahman Almajhad)


## Dataset

Ford GoBike System Data is a dataset consists of information about bike trips, which has a attributes for approximately 150102 bikes.


## Summary of Findings

In the exploration, I used the histogram plot to explore the distribution of duration trips, I found that following:
- Most of the duration trips are less than 60 minutes.
- The duration is not in a normal distribution.

Then by bar chart and pie chart, regarding the data about stations names and user types, I found:
- The San Francisco Caltrain station is the most station that bike riders start at (3094 trips).
- The San Francisco Caltrain station is the most station that bike riders end at (4791 trips).
- We have 2 user types (Customer & Subscribers)
- The number of customers is more than subscribers. As the number of customers is 67909 (54.59%) while the number of subscribers is 56498 (45.41%).

After that, I used the bar charts to found data about (day of month, day of week, hour of day) based on the number of trips, in the following points:
- Most of the trips are active in the Q1 and Q2 of the month.
- Most of the trips are active on Mondays, Tuesdays and Thursdays, and less active in on Saturday and Sunday (Weekend).
- Most of the trips are active in the mornings and afternoons hours (usually work start/end times).

Moreover, I used the scatter plot between the duration trips and the station latitude/longitude then found:
- The fastest way to finish the trip lies between 37.750 and 37.875, -122.2 and -122.5 "lat/long".

Then I used the cat plot between user types and days & hours, and I got that:
- The customers and subscribers almost the same, except that the customer has clearly more trips from day 16 to day 20 and a few increase for the rest of the month compared with the subscribers.

And box plot told me:
- Subscribers finish the trip faster than Customers.

After that, I used point plot between (start station latitude/longitude and duration trips) for each user type and I found: 
- There is a slight change that indicates that subscribers take less time during the trip per minute.

Finally, with the violin plot between (day of week and hour of day) for each user type, I knew this:
- The trips are active in the morning periods (7,8,9) and evening periods (16,17) "Usually work start/end times" compared to the days of the weekend that indicates a different activity, usually the afternoon period. These notes are the same by subscribers and customers.


## Key Insights for Presentation

For the presentation, I focused on the relationship between more than one factor, such as who of user type takes less duration trip time compared with the other and why, and which stations that have the most number of trips (start/end).
I used bar chart to find What is the station has the most number of trips, and pie chart to find What are the most User Types, and violin plot to find When Bike Trips goes active during the hours of the day.