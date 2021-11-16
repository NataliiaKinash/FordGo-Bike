# Ford GoBike System Data
## by Nataliia Kinash


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

I have started from downloding the dataset, converting the datatypes, when needed, dropping NaNs and adding extra columns such as `duration_hours` and `member_age`. I also took a look at descriptive statistics of the dataset.


## Summary of Findings

The most interesting finding for me is a result of map exploration. Visually I have noticed that  there are 3 different bike station location areas: San Jose, San Francisco and Oakland .

##### Main Results of Univariate Exploration:

- The distribution of ride duration is strongly skewed to the right, which means that most rides have duration less than 2k seconds, which is approximately half an hour.
-  The age distribution is again right-skewed distribution, telling that the mean age of service users is about 36 years.
- There are significantly more Subscribers than non-Subscribers.
- The service is more popular on weekdays rather than on weekend.
- Bikes are the  most popular during the rush hours: 8 and 9 am in the morning and 4-6 pm in the evening. They are moderately popular during the day and not popular at all at night.

##### Main Results of Bivariate Exploration:

- Shorter rides (less than 5 hours) among younger people seem to be the most popular ones.
- While customers are using the bikes more or less equally regardless of the weekday, there is significant reduction of bike usege during the weekends among subscribers.
- Both customers and subscribers use bikes more during the rush hours, though this behaviour is much more significant among subscribers.
- The service users are mostly men, regardless of subscription type.

##### Main results of Multivariate Exploration:

- People mostly use bikes during the day rush hours regardless of gender or subscription type. Users make their longest rides around 8-9 am in the morning.
- People, who have not identified their gender mostly make short-time rides. In general there are more service users among younger people and short rides are more popular than the long rides.
- Though the amount of Female users in significantly smaller than the amount of Male users their behaviour as users does not differ much.


## Key Insights for Presentation

The goal of the presentation is to demonstrate the relation between the number of rides and subscriber type depending on the day of the week and the hour of the day.

Analysis of ride duration depending on the age and gender is also included into the presentation.