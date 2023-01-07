# Pyber_Analysis

## 1. Overview of analysis:
The purpose of this analysis was to generate a visible data report to decision-makers at PyBer to show the differences between city types and how that differences can be used to address any disparities among city types.

There were 2 CSV files that we used for the resource. First is a data of the city([city_data.csv](https://github.com/ninicholasas/Pyber_Analysis/blob/main/Resources/city_data.csv))(3 columns x 121 rows) that is consisted from city, driver count, city type. The second one is a data of the rides([ride_data.csv](https://github.com/ninicholasas/Pyber_Analysis/blob/main/Resources/ride_data.csv))(4 columns x 2376 rows) that is consited from city, date , fare, id.

## 2. Results:
### 2.1 Summary Dataframe by City Type
Using Pandas I have created the dataframe below.

<img width="850" alt="PyBer_cityType_dataFrame" src="https://user-images.githubusercontent.com/110373282/211169708-2db46999-b2a9-48b1-8438-5daf180177a9.png">
From this dataframe we could tell that the Urban cities are the ones that generate the most revenue. It felt kind of interesting that there are almost 8 times the drivers in the Urban cities compared to the Suburban cities the Total Fares is just over 2 times. Also from comparing the Total Rides and the Total Drivers we could tell that for some of the drivers for Urban cities, they were not able to get a ride within this time period. While the drivers in Suburban and Rural Cities at least got one ride.


### 2.2 Total Fare by City Type 
Next, I have used Matplotlib to generate a line chart that is comparing the Fares by Month for each city type.

![PyBer_fare_summary](https://user-images.githubusercontent.com/110373282/211169783-8c281521-a67e-4f4f-9025-69aef78fb43c.png)
We can't really see any trends from this chart, maybe if we increase the data up to one year we might be able to see some tendencies by seasons.
There is a related spike at the end of February for each city type, but it is hard determine what the cause is since there are no related holidays or famous events.
### Conclusion
From the given data we could tell that the Urban cities are the ones that has the most revenue, but at the same time has too many drivers compared to the rides. \n
If we can access the data for the ride length, the profit for ride, expense cost, and if the drivers recieve any salary even though the driver did not give a ride I probably could create a more detailed report.

### 3. Summary
