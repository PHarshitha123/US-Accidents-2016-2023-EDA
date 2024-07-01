# US-Accidents-2016-2023-EDA

## Project Title

US Accidents 2016-2023 Exploratory Data Analysis

## Description

This project presents an in-depth Exploratory Data Analysis (EDA) of US accident data using Python. The analysis includes detailed visualizations and statistical summaries to uncover trends and factors influencing accident occurrences, aiming to inform safety strategies and mitigate risks on the roads.

## Data Source

The dataset used in this project, sourced from Kaggle, comprises detailed information on US accidents.
This is a countrywide car accident dataset that covers 49 states of the USA. The accident data were collected from February 2016 to March 2023, using multiple APIs that provide streaming traffic incident (or event) data. These APIs broadcast traffic data captured by various entities, including the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road networks. The dataset currently contains approximately 7.7 million accident records.
### Dataset:
[Link for downloading dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

**Source:** Kaggle<br>
**Columns:** 
1. ID : This is a unique identifier of the accident record.
2. Source : Source of raw accident data.
3. Severity : Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic.
4. Start_Time : Shows start time of the accident in local time zone.
5. End_Time : Shows end time of the accident in local time zone. End time here refers to when the impact of accident on
6. Start_Lat : Shows latitude in GPS coordinate of the start point.
7. Start_Lng : Shows longitude in GPS coordinate of the start point.
8. End_Lat : Shows latitude in GPS coordinate of the end point.
9. End_Lng : Shows longitude in GPS coordinate of the end point.
10. Distance(mi) : The length of the road extent affected by the accident in miles.
11. Description : Shows a human provided description of the accident.
12. Street : Shows the street name in address field.
13. City : Shows the city in address field.
14. County : Shows the county in address field.
15. State : Shows the state in address field.
16. Zipcode : Shows the zipcode in address field.
17. Country : Shows the country in address field.
18. Timezone : Shows timezone based on the location of the accident (eastern, central, etc.).\
19. Airport_Code : Denotes an airport-based weather station which is the closest one to location of the accident.
20. Weather_Timestamp : Shows the time-stamp of weather observation record (in local time).
21. Temperature(F) : Shows the temperature (in Fahrenheit).
22. Wind_Chill(F) : Shows the wind chill (in Fahrenheit).
23. Humidity(%) : Shows the humidity (in percentage).
24. Pressure(in) : Shows the air pressure (in inches).
25. Visibility(mi) : Shows visibility (in miles).
26. Wind_Direction : Shows wind direction.
27. Wind_Speed(mph) : Shows wind speed (in miles per hour).
28. Precipitation(in) : Shows precipitation amount in inches, if there is any.
29. Weather_Condition : Shows the weather condition (rain, snow, thunderstorm, fog, etc.)
30. Amenity : A POI annotation which indicates presence of amenity in a nearby location.
31. Bump : A POI annotation which indicates presence of speed bump or hump in a nearby location.
32. Crossing : A POI annotation which indicates presence of crossing in a nearby location.
33. Give_Way : A POI annotation which indicates presence of give_way in a nearby location.
34. Junction : A POI annotation which indicates presence of junction in a nearby location.
35. No_Exit : A POI annotation which indicates presence of no_exit in a nearby location.
36. Railway : A POI annotation which indicates presence of railway in a nearby location.
37. Roundabout : A POI annotation which indicates presence of roundabout in a nearby location.
38. Station : A POI annotation which indicates presence of station in a nearby location.
39. Stop : A POI annotation which indicates presence of stop in a nearby location.
40. Traffic_Calming : A POI annotation which indicates presence of traffic_calming in a nearby location.
41. Traffic_Signal : A POI annotation which indicates presence of traffic_signal in a nearby location.
42. Turning_Loop : A POI annotation which indicates presence of turning_loop in a nearby location.
43. Sunrise_SunsetShows : the period of day (i.e. day or night) based on sunrise/sunset.
44. Civil_TwilightShows : the period of day (i.e. day or night) based on civil twilight.
45. Nautical_Twilight : Shows the period of day (i.e. day or night) based on nautical twilight.
46. Astronomical_Twilight : Shows the period of day (i.e. day or night) based on astronomical twilight.

## Libraries Used:
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn

[Python File for Reference](usaccidentseda-2016-2023.ipynb)

## Exploratory Data Analysis:

**Problems/Questions Addressed with this EDA**

1. How Many US cities are there in the dataset?
2. New york being the most populated city why it did not show up in the top 10 cities by accidents ?
3. Even Though the NewYork City is listed in the dataset why NewYork City has less Accidents being a most populated City?
4. There are 50 States in US which of the state accidents data is not collected?
5. What are the top 20 Cities by Accidents?
6. What are the top 10 States by Accidents?
7. What is the Distribution of cities by accidents?
8. What is the percentage of accidents with different accident factors?
9. Does the accidents are occuring in hottest temperature or coolest temperature?
10. What time of the day are accidents most frequent in?
11. Which days of the week have the most accidents?
12. Which months have the most accidents?
13. What is the Accidents Trend by Year?
14. On what Weather Condition does the accidents occuring?

## Inferences:

* New York City being the high populated city did not show up in top 10 or 20 . It's possible that the data sources may not have adequately captured or reported accidents in New York City, potentially explaining why it ranks lower in accident frequency and doesn't appear at the top of the list.[External Source to justify above inference](Source:https://www.rosenbaumnylaw.com/new-york-car-accident-lawyer/statistics/)
* It can be inferred that **"Hawaii"** is not included in the dataset, likely indicating that data for this state was not collected or reported.
* The observed exponential decrease in accidents across the distributions warrants further investigation to understand the underlying causes.
* 8% of the cities have more than 1000 accidents.
* Factors such as 'Amenity', 'Bump', 'Give_Way', 'No_Exit', 'Railway', 'Roundabout', 'Traffic_Calming', and 'Turning_Loop' have a negligible effect on accidents, each accounting for less than 2% of the total accidents.
* Factors like 'Station' and 'Stop' have a moderate impact, contributing to between 2% and 4% of the total accidents.
* More significant factors include 'Junction' (7%), 'Crossing' (11%), and 'Traffic Signal' (15%).
* Human error at junctions and crossings, such as misjudging oncoming traffic, failing to yield, and not adhering to signals, often contributes to accidents, exacerbated by poor visibility and inadequate signage. Traffic signal-related accidents are frequently caused by drivers running red lights, making sudden stops, or speeding to beat the light.
* Accidents occurring between 15°C to 25°C are influenced by drivers' complacency in comfortable weather conditions, resulting in distractions and relaxed driving habits. Additionally, the higher traffic volume and variable road conditions within this range contribute to increased accident rates due to congestion and unpredictable road surfaces.
* Accidents are more likely to occur between 7:00 AM and 10:00 AM, corresponding to the morning rush hour when people depart for work. Similarly, another peak period for accidents is between 3:00 PM and 7:00 PM, coinciding with the evening rush hour when commuters return home from work.
* In 2016 year january month data is not collected.
* In 2023 only three months data is collected (Jan,Feb,Mar).
* The distribution of accidents by weather condition indicates that favorable weather conditions such as 'Fair', 'Mostly Cloudy', 'Clear', and 'Cloudy' are associated with the highest number of accidents. Conversely, adverse weather conditions like 'Light Rain', 'Fog', and 'Heavy Rain' also contribute significantly to accident rates, suggesting that both clear and inclement weather conditions can pose risks for road safety.
  
