# surfs_up
Investing In Waves &amp; Ice Cream Shop - Perform Weather Analysis of Oahu (Utilizing Python, SQLite, VS code, Jupiter Notebook)

# Tool-Kit
Utilized SQLAlchemy is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL. 
SQLite is a C-language library that implements a SQL database engine. SQLite is the most used database engine in the world. SQLite is built into all mobile phones and most computers and comes bundled inside countless other applications that people use every day.
# Purpose
To determine whether the seasons could affect the surf and ice cream shop business. Specifically, there are certain times of the year mainly June and December when business might be slower, or the type of customer could be different
Review Oahu, Hawaii seasonality weather data difference for the months of June and December 9 stations utilizing multiple years precipitation and temperature recorded data. The data was provided in SQLite format.
# Findings
## Rainfall 
Below are the Rainfall statistics for across stations and years.  Based on our observations, average rainfall in Jun is 0.14 inches vs. Dec 0.22 inches.  Also the standard deviation from mean for June is 0.3 vs. Dec 0.54.  This means we have higher chances of rain in Dec vs. June.  In addition, max rainfall during the month of June is 4.4 inches vs. Dec 6.4 inches.  Also, shown in the table below are the quartiles for the inches of rain, 50% quartile show 0.02 inches of rain vs. Dec 0.3 inches

![alt text](https://github.com/vsanand27/surfs_up/blob/master/Rainfall%20Statistics%20for%20June%20and%20Dec.PNG)

Over the years, the trend show that rainfall totals are trending downwards.  Though Dec averages look higher the frequency of rainfall is low vs. Jun.

![alt text]( https://github.com/vsanand27/surfs_up/blob/master/Rainfall_June%20and%20Dec%20Comparison.PNG )

## Temperature
Below are the Temperature statistics for across stations and years.  Based on our observations, average Temperature in Jun is 74 degrees vs. Dec 71 degrees.  Also, the standard deviation from mean Temperature for June is 3.25 vs. Dec 3.74.  This means in both month, there are high changes the temperature could vary in both months from the mean.  In addition, max Temperature during the month of June is 85 degrees vs. Dec 83 degrees.  Also, shown in the table below are the quartiles for Temperature, 50% quartile show 75 degree in June vs. 71 degrees in December.  In conclusion, the weather between two month is similar, except for it is bit colder during December as temperature can go down to 56 degrees.  

![alt text](https://github.com/vsanand27/surfs_up/blob/master/Temperature%20Statistics%20for%20June%20and%20Dec.PNG)

Histogram for Temperature show similar trends as discussed above. The frequency of Temperature readings show temperature varies between 70 to 74 degrees most of the times.
![alt text](https://github.com/vsanand27/surfs_up/blob/master/Temperature%20Histogram%20for%20June%20and%20Dec.PNG)

