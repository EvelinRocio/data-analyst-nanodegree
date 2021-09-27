# Bike Sharing System Data
## by Evelin Battocchio


## Dataset

In this project, I investigate a data set containing information about individual rides made in the bike-sharing system provided by Bay Wheels in 2019, which covers the greater San Francisco Bay area. To obtain the dataset for the whole year, I joined together multiple .csv files, which I obtained from the Bay Wheels company website: https://www.lyft.com/bikes/bay-wheels/system-data.

The final dataset contains 16 columns and 2407259 rows, representing information about:

* Bike ride duration, start and end time
* Start station ID, name, latitude and longitude
* End station ID, name, latitude and longitude
* Bike ID
* User type: either Subscriber or Customer

Most variables are numeric, except for station names and user type.

I focus my research on the following questions:

* When are most trips taken in terms of day of the week and month of the year?
* How long does the average trip take?
* Does the above depend on whether a user is a subscriber or a customer?


## Summary of Findings

After the analysis, the following conclusions can be derived:

* The majority of bike rides last less than 25 minutes.
* Approximately 80% of the people who used the bicycles are subscribers, while the remaining 20% are occasional users.
* The use of the bike system remained almost constant during the week, but dropped significantly on the weekends.
* The months of the year in which the bike system was most used were March, April and October, while the month in which it was least used was December.
* On average, the duration of bike rides is longer in occasional customers (approx. 22 min) than in subscribed users (approx. 11 min).
* Although the number of trips is lower on Saturdays and Sundays, the average trip duration is longer during the weekend than on weekdays. This is mainly attributed to occasional users.
* Throughout the year, the ride duration remains more or less constant for subscribers. In the case of occasional customers, the trip length decreases during the winter, especially in December.


## Key Insights for Presentation

The key insights I'll show in the presentation are the following:

* Visualization of bike rides distribution per user type (subscriber or customer)
Approximately 80% of the people who used the bicycles are subscribers, while the remaining 20% are occasional users.

* Visualization of ride count per day of the week, considering the information on the trip starting time.
The number of bike rides remains almost constant during the week, but drops significantly on the weekends.

* Visualization of mean trip duration per day of the week and user type.
On average, the duration of bike rides is longer for occasional customers than for subscribed users. Trip lengths are longer on the weekends, and this is mainly attributed to occasional users.


