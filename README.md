# (Dataset Exploration Title)
## by Eluwa Chisom

> The 


## Dataset

> The dataset contains data of 183,000 rides made in a bike-sharing system covering the San Francisco Bay area. Data features include duration (secs) and others such as DateTime, customer type, gender, as well as some additional variables. The dataset can be downloaded from [here] (https://console.cloud.google.com/marketplace/details/san-francisco-public-data/sf-bike-share?pli=1&project=graphite-argon-344013)


## Summary of Findings

> In the exploration process, here are my discoveries:

- The dataset is for the months of February and March 2019
- The mean duration for the trips is 726 seconds
- The ford bikers users contain 75% male, 23% female, 2% others
- The weekends have the least trips for starting and ending
- The user type shows two categories: Subscriber 158386 members and Customer 16566 members.
- The most prominent members fall within ages 19-45 for the members
- Trip durations on weekends are longer than on weekdays.
- Peak periods are between 6th to 9th hour (6am - 9am) and between 16th & 21st hour (4pm and 7pm). 
- The lowest trip periods is between 0hr to 5hrs (12midnight - 5am)
- Only 10% of users share bikes for all trips.
- Only subscribers have records of shared trips
- Customer take longer times than Subscribers
- There are more males as both Customer and Subscriber user type than other genders.
- The gender of entries as "others" travel longer times than male and females.
- There are more Subscribers than Customers on every day of the week; there are more Subscribers taking trips on Thursdays.


## Key Insights for Presentation

> For my analysis, I focus on all variable of interest to understand their distribution: like members' ages, gender, user types, the frequencies of rides per hour, day but ignored other geospatial variables. My goal is to discover how these variables influenced trip durations, riding hours, and riding days of the week. I start by checking out individually percentage of gender, count of users, trip frequencies by hours and days of the week and the user type using different plots. 

> Then, I delved into checking different relationships between different variables. The categorical variables of interest were gender, user type and how they span across days and hours of each day and duration of trips. I explored them using boxplot, countplot, and heatmap for identifying any correlation between variables. Clear titles, legends and different color palettes for each variable were used in the plots to ensure clarity of insights

