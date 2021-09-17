# Bikesharing Analysis
Module 14 Challenge Files/Links
- [NYC_Citibike_Challenge.ipynb](https://github.com/aseo67/bikesharing/blob/main/NYC_Citibike_Challenge.ipynb)
- [Link to Bikesharing Analysis](https://public.tableau.com/app/profile/amy.seo/viz/BikesharingAnalysis_16317748911980/NYCStory?publish=yes)

## Overview of Analysis
Having been inspired by the Citi Bike bikesharing business in NYC, the team is looking to start a similar bikesharing business in Des Moines. The first steps for this venture are to figure out how Citi Bike worked for NYC, in order to gather insights into such a bikesharing business. To do so, the trip data for NYC in August of 2021 has been analyzed. Once knowledge is gathered in how a bikesharing business works, the team will gather investors and start investigating how a bikesharing service may work for a city like Des Moines. 

## Results

### Basic Info About NYC Bikesharing in August
First of all, basic information about the bikesharing service for this time period in NYC was gathered. This visualization presents a dashboard with the total number of trips, gender breakdown of its users, and the customer type (short-term customer vs. long-term subscriber) of this month's users. While the total trips for the month are significantly high, it is important to note that this is reflective of a large city like NYC. Furthermore, we see that bikeshare service users are primarily male, and consist mainly of subscribers. 
![Screenshot](https://github.com/aseo67/bikesharing/blob/main/Screenshot_1_Basic%20Summary.png)

### Average Trip Duration by Birth Year
Next, this visualization helps show what typical trip durations are for users, based on their birth years (i.e. age). This shows us that younger populations tend to utilize this bikeshare service more consistently than older generations. 
![Screenshot](https://github.com/aseo67/bikesharing/blob/main/Screenshot_2_Avg%20Trip%20Duration.png)

### Checkout Times for Users
To dive a bit deeper into the usage behavior of this service, a chart was created plotting typical trip durations. We see that most of the bike trips are fairly short - typically being ended after about 30 minute or less. This suggests that there isn't a large group of people utilizing bikesharing for longer, leisurely bike rides around the city. Rather, more destination-oriented, shorter trips may be the main use case. 
![Screenshot](https://github.com/aseo67/bikesharing/blob/main/Screenshot_3_Checkout%20Times%20for%20Users.png)

### Checkout Times by Gender
Parsing this out even further by gender indicates that this trend of shorter trips is pretty consistent across all genders. Of course, males make up a majority of the users, so we see higher spikes, but in general, all genders demonstrate spikes for trip durations less than ~30min.
![Screenshot](https://github.com/aseo67/bikesharing/blob/main/Screenshot_4_Checkout%20Times%20by%20Gender.png)

### August Peak Hours
To figure out what times of day see the most bikesharing activity, the following visualization was created - a bar chart of number of trips for each hour of the day. Here, we see that there are peaks in bikeshare activity particularly in the morning and early evening - suggesting that commute times may play a role. 
![Screenshot](https://github.com/aseo67/bikesharing/blob/main/Screenshot_5_August%20Peak%20Hours.png)

### Trips by Weekday per Hour
The next visualization dives even deeper in the time trends of bikesharing in NYC, and provides a heatmap that indicates at what times on what days of the week we see the most activity. The weekday/time with darker (redder) colors, indicate heavier use of bikesharing. This solidifies the hypothesis that weekday commute times are when we see the heaviest usage. On the weekends, the usage tends to peak less, with most activity occurring between late morning and early evening. 
![Screenshot](https://github.com/aseo67/bikesharing/blob/main/Screenshot_6_Trips%20by%20Weekday%20per%20Hour.png)

### Trips by Gender (by Weekday per Hour)
Breaking this down even further by gender, we see that the heaviest usage is indeed from the male population. However, both females and males demonstrate similar "peaks" in usage during weekday commute hours. 
![Screenshot](https://github.com/aseo67/bikesharing/blob/main/Screenshot_7_Trips%20by%20Gender.png)

### User Type by Gender by Weekday
Next, we look at the user type - split by weekday of trips and gender - also displayed as a heatmap. Here, we see that most of the user base comes from long-term subscribers who are male. 
![Screenshot](https://github.com/aseo67/bikesharing/blob/main/Screenshot_8_Type%20by%20Gender%20by%20Weekday.png)

## Summary
Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

In summary, the key takeaway to move forward with about bikesharing services is that users primarily utilize this service in their daily commute. While there might be some usage on the weekends for other purposes, the heaviest bikesharing activity is seen during morning and evening commute hours during the weekdays. Given this dynamic, we see that the majority of users are long-term subscribers, rather than one-time customers. Furthermore, this service is primarily used by male customers - majority of whom are subscribers using the service for their commute. As demographics, trends and transportation methods for Des Moines specifically are investigated moving forward, it'll be important to see if these usage patterns will fit in well with what the people of Des Moines may look for. 

Two additional visualizations/charts that may provide further insight for future analyses are...
1. What is the age break-out of the customer/user base? Understanding the breakout of birth years or users' age will important to see what age brackets bikesharing can serve. This can be in the form of a bar chart or heat map. 
2. What is the demographic breakdown (age, gender, user type) of weekend users of the bikesharing service? This can help diagnose who utilizes the service for non-commute types of trips, which can be especially important if a commute-targeted strategy isn't as well-suited for Des Moines. This can be in the form of pie charts or heat maps. 

