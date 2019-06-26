

<img src="bay_wheels.png" style="width:1000px; height:500px"/>
## Lyft's Bay Wheels Bikeshare Analysis
###  Author: Jaekyung Lee

### Dataset
The data consist of approximately 1.1 milion bikeshare trips from January-2019 to May-2019. <br />
- The attributes include: <br />
- Trip Duration (seconds) <br />
- Start Time and Date <br />
- End Time and Date <br />
- Start Station ID <br />
- Start Station Name <br />
- Start Station Latitude <br />
- Start Station Longitude <br />
- End Station ID <br />
- End Station Name <br />
- End Station Latitude <br />
- End Station Longitude <br />
- Bike ID <br />
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual) <br />
- Member Year of Birth <br />
- Member Gender  <br />

17,000+ trip data were removed in the data wrangling process, due to unreal birth date, which in some cases was dated prior 1900, and also those unreal longitude & latitude, such as 0 longitude, 0 latitude.

### Summary of Findings

- There are two types of user using BayWheels, subscribers and customers. Subscribers are **mostly daily commuters**, having short trips to work and renting a bike on weekdays at 8-9 AM and 5-6PM, and. Customers are mainly **tourists on weekends** to discover the Bay Area.

- The bike share system was used more often around summertime (May-October) with a clear drop from January to March, most probably due to the weather condition. Moreover, I have checked if there are some differences in trends for genders.

- The BayWheels is generally used by 88.6% of Subscribers and 11.4% of daily Customers. Weekly usage of BayWheels is high during weekdays (M-F) on average 12.5 minute of trip duration.

- One of the interesting findings is BayWheels users mainly take trips around 8-9AM and 5-6PM; the probable reason for this is that those subscribers commute on bike to work with BayWheels. Also, the IQR for customer is between 9 to 23 min while it's between 6 to 14 min for subscribers.

- There are a lot of male **subscrbiers** who highly likely use bayWheels for commute to work (7-9AM & 4-6PM) and a large number of male **customers** who use BayWheels around 4-6PM during weekends.

- The trip duration for females (25 min) is 4 minute longer than males' trips (21 min)


### Key Insights for Presentation
For the presentation, I aimed to explore user habits of BayWheels customers and subscribers in Jan 2019 - May 2019. In univariate and bivariate visualization, I tried to explore the user type, the average trip duration and hourly, weekly useage of BayWheels. In multivariate visualization, I discover the relationship among user type, number of trips, and gender, or the montly, weekly, hourly usage of BayWheels based on user type and gender.


### Questions:
- How long does the average trip takes?
- Weekly Usage of BayWheels
- User Type of BayWheels
- Hourly Usage of the BayWheels Trips
- The relationship Between User Type and Trip Duration
- The Relatinoship Among User Type and Number of Trips and Gender
- Monthly, Weekly & Hourly Usage of Baywheels Per User Type and Gender
- The Trip Duration per User Type and Gender
# lyft_baywheels_analysis
