# Ford GoBike Bike-sharing System 2019 Usage Visualization

## by Truc Phan


## Dataset

Ford GoBike (now known as [Bay Wheels](https://en.wikipedia.org/wiki/Bay_Wheels)) is the first regional and large-scale bicycle sharing system deployed in California's San Francisco Bay Area. The system was originally launched as Bay Area Bike Share in August 2013. In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company. As of January 2018, the Ford GoBike system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose with about 10,000 annual subscribers. 

The dataset used for this study includes information about 180,000+ individual rides made in a bike-sharing system in February 2019 in CSV format covering the greater San Francisco Bay area, raw data (without member information) also available in [here](https://s3.amazonaws.com/baywheels-data/index.html).

## Summary of Findings

Duration (min) has a long-tailed distribution, with a lot of trips on the short duration end, and few on the long duration end. When plotted on a log-scale, the duration distribution looks like a normal distribution, with a peak between 5 and 20 minutes. The number of trips peaked around 8-9 AM and 5-6 PM during a day, which is typical rush hours. There were more trips on workdays (Mon-Fri) compared to weekends.It indicates a pretty stable and efficient usage of the bike for commuting purposes on workdays, while more casual flexible use on weekends.

User-wise, most riders were male subscribers and did not use bike share for all trips. Most members were around 25 to 35 years old, and when riders got older than 40, bike usage dropped significantly. Male riders are slightly older and bike moderately faster on average compared to female riders. The bike users during weekdays are a bit older than those who bike on weekends, which supports the observed work commute usage from the trip distribution over day of week plot.

In terms of user type, much more subscribers utilized the bike-sharing system than casual customers. Subscribers and customers have quite different riding habits and patterns. Most of subscribers' journeys take place on working days and especially during peak hours (morning to work and afternoon to leave work). Meanwhile, in addition to commuting trips during rush hours, consumers prefer to ride for fun in the afternoon on weekends. Furthermore, subscribers tended to have much shorter/quicker trips than customers, making subscriber usage more efficient.

The top ten stations with the highest number of bike rentals were mainly on Market Street and Townsend Street.


## Key Insights for Presentation

Overall, most bike trips were short, between 5 to 20 minutes, and more trips were taken on weekdays (Monday - Friday) than on weekends. In the Ford Gobike bike-sharing system in February 2019, there were many more subscribers than casual customers and much more males than females. Moderately different riding habits and usage patterns are noticeable between the two types of bike riders. While subscribers rode mainly on workdays (Mondays - Fridays), customers also utilized the system on weekends, especially in the afternoon. On weekdays, the bike usage of both subscribers and casual customers increased significantly around 8:00 - 9:00 AM and 5:00 - 6:00 PM as they all biked for the work commute. However, subscribers' usage around these rush hours is far more than casual customers' usage. In addition, subscribers tended to have much shorter/quicker trips than customers, making subscriber usage more efficient. Finally, male riders biked faster and with the more consistent trip length in comparison to female riders.