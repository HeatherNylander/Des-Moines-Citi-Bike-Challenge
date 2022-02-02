# Des Moines Bike Sharing Challenge

## NYC Citi Bike Analysis

[Link to Tableau NYC Citi Bike Analysis](https://public.tableau.com/app/profile/heather.nylander/viz/NYCCitiBikeAnalysis_16437498010700/NYCCitiBike "Link to Tableau NYC Citi Bike Analysis")


### Overview of Analysis
Analysis done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, a bike trip analysis from NYC has been done with visualizations made using Tableau.

## Results

### Customer Type
| Customer Stats from Tableau <img width=1000/>  | Analysis <img width=1000/> |
| ------------- | ------------- |
| <img src="https://github.com/HeatherNylander/Des-Moines-Citi-Bike-Challenge/blob/main/Resources/CustomerStats.png" width="450" height="650"> | **Customer stats show users are predominantly male. The breakdown is as follows:** <br /> 	• Male: 65% <br /> 	• Female: 25% <br /> 	• Unknown: 10% <br /> <br /> **Customer stats show an overwhelming percent of users prefer the annual subscription to the short term subscription. The breakdown is as follows:** <br /> 	• Annual Subscriber: 81% <br /> 	• Short-term Subscriber: 19% <br /> <br /> **Customer birth chart shows younger users more likely to use Citi Bike.** <br /> 	• Peak around 1990 indicates users in their late twenties are more frequent customers. <br /> 	• Peak at 1969 is most likely intentional user error. I reccomend treating this data point as if it followed the trend set by 1968 and 1970.|


### Trip Duration
| Trip Duration Stats from Tableau <img width=1000/> | Analysis <img width=1000/>|
| ------------- | ------------- |
| <img src="https://github.com/HeatherNylander/Des-Moines-Citi-Bike-Challenge/blob/main/Resources/TripDuration.png" width="450" height="650">  | **The graphs show most users check a bike out and return within an hour.** <br /> 	• This may be explained by the distance one would expect to travel in NYC to reach a new destination. <br /> <br /> **The graph broken down by gender mirrors the same result for each gender with a negligible exception for 'unknown' gender.** <br /> 	• No significant change in trend by gender. We already noted that males are far more likely to use Citi Bike.|

### Trip Density
| Trip Desnity Stats from Tableau <img width=1000/> | Analysis <img width=1000/>|
| ------------- | ------------- |
| <img src="https://github.com/HeatherNylander/Des-Moines-Citi-Bike-Challenge/blob/main/Resources/TripDensity.png" width="450" height="650">  | **Trips by Weekday per Hour** <br /> 	• We see the greatest range of peak times during the weekend with roughly 11am to 5pm being peak hours. <br /> • During the week, we see three days with more user activity specifically between the hours of 5pm and 7pm. The three days being Monday, Tuesday and Thursday. <br /> • Weekdays between 8am and 9am also show an increase in riders. This may be due to users choosing a bike share program to get tp work. <br /> <br /> **Trips by Gender** <br /> 	• The trend of peak hours is very similar between male and female users and again, we see a negligible difference with the 'unknown' gender data. <br /> <br /> **User Trips by Weekday** <br /> 	• Thursday is the most popular day to check out a bike within annual subscribers with Friday coming as a close second. <br /> 	• Short-term subscribers are more likely to check out a bike on Saturday or Sunday.|

### Bike Usage 
| Bike Usage Stats from Tableau <img width=1000/> | Analysis <img width=1000/>|
| ------------- | ------------- |
| <img src="https://github.com/HeatherNylander/Des-Moines-Citi-Bike-Challenge/blob/main/Resources/BikeUsage.png" width="450" height="650">  | **Bike Usage by ID: In this breakdown, we see how many hours of usage each particular bike gets.** <br /> 	• Based on this data, it appears that only a portion of bikes follow a trend of more users on a given bike = more time usage on that bike. <br /> 	• A significant portion of bikes are checked out for a number of days: The continual use of these bikes may indicate a greater need for more frequent repair. <br /> <br /> **Individual Bike Usage: This chart shows how many users a particular bike has had.** <br /> 	• This analysis may be helpful to determine how often certain bikes should be repaired if number of users is considered instead of total time usage of a given bike.  |

## Summary
- Users are predominantly male.
- Most users opt for annual subscription.
    - Of annual subscribers, Thursday between 5pm and 7pm shows peak hours.
- Of short-term subscribers, the weekend shows peak hours.
    - This may indicate the tourist population opting for both short-term subscription and weekend use. 
- Most users ride for less than an hour with an exception of users who opt for multiple day usage. 
- Both a breakdown of individual bike usage by sheer number of users and actual time spent checked out is shown. 
    - To determine how often bikes should be inspected, I reccomend opting for the time spent checked out graph as it considers actual bike usage instead of quantity of users. 

- For further analysis, I reccomend a visualization showing location of bikes that see the highest time usage. 
    - This may be helpful to determine if a routine rotation of bikes should occur between more and less busy locations. 
- Another visualization to add would be average distance per bike usage to determine how bikes are being used (to get to work vs. to see tourest attractions etc.)
