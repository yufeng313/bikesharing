# bikesharing
## Overview
This project is an analysis of New York Citi Bike data, using data visualizations from Tableau to explore the viability of a bike-sharing business in Des Moines.

## Resources
Data Source: 201908-citibike-tripdata.csv<br/>
Software: Python 3.7.6, Jupyter Notebook 6.4.8, Tableau Public 2022.2.1

## Results
### NY Citibike general data visualizations with Tableau in August 2019
![bike general](https://user-images.githubusercontent.com/107179765/190757706-82bd1cb7-bee1-4e3c-b5e1-a248a564aafb.png)
1. The total number of trips in August is 2,344,224, and 81% of the users are annual subscribers.  <br/>
2. 65% of the users are males and 25% are females. Males tend to use bike sharing the most.<br/>
3. There is a wide range of users whose birth year from 1880-2000. Younger users tend to have longer ride duration.<br/>
4. According to the size of the circle on the map, we can easily find out which locations are the top bike locations for starting a journey.<br/>

### Bike checkout times for all riders and genders
![bike checkout times ](https://user-images.githubusercontent.com/107179765/190799368-bb5ae8ea-0a47-4566-9a3c-9d2eb2e260a7.png)
From this chart, we can see that bikes are mostly checked out by males within 1 hour. Within 1-hour, male users take approximately 3 times more rides than the female users. After 1 hour, they almost have the same checkout times.

### Bike trips for all riders and genders for each hour of each day of the week
![trips timings](https://user-images.githubusercontent.com/107179765/190809359-d46e348e-0906-4499-938b-7c56dc4ea0b9.png)
1.Most rides are taking place at around 7-9 AM and 5-7 PM at the weekday, maybe that’s because people are on/off work at that time. Weekend rides are even in the whole day from 9 AM to 6 PM.<br/>
2.Meanwhile, most rides are taken by males as well as subscribers.<br/>

### Link to Tableau Story
https://public.tableau.com/app/profile/yufeng1756/viz/NYCCitiBikeStory_16633611312440/NYCCitiBikeStory?publish=yes

## Summary
The results show high activity of the bike sharing service in New York during the month of August 2019. Most of the rides were in Manhattan Island, taken by male as well as subscribers during morning and evening rush hours. This means that Citi Bike services are used as an alternative public transportation by commuting workers.<br/>
Additional visualizations:
- Distribution of member type per station
- Average bike tripduration at each station
