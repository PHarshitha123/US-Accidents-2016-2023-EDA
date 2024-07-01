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

**Source:** Kaggle
**Columns:** 
1. ID : This is a unique identifier of the accident record.
2. Source : Source of raw accident data.
3. Severity : Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic.
4. Start_Time : Shows start time of the accident in local time zone.
5. End_Time : Shows end time of the accident in local time zone. End time here refers to when the impact of accident on
Start_Lat : Shows latitude in GPS coordinate of the start point.
Start_Lng : Shows longitude in GPS coordinate of the start point.
End_Lat : Shows latitude in GPS coordinate of the end point.
End_Lng : Shows longitude in GPS coordinate of the end point.
Distance(mi) : The length of the road extent affected by the accident in miles.
Description : Shows a human provided description of the accident.
Street : Shows the street name in address field.
City : Shows the city in address field.
County : Shows the county in address field.
State : Shows the state in address field.
Zipcode : Shows the zipcode in address field.
Country : Shows the country in address field.
Timezone : Shows timezone based on the location of the accident (eastern, central, etc.).\
Airport_Code : Denotes an airport-based weather station which is the closest one to location of the accident.
Weather_Timestamp : Shows the time-stamp of weather observation record (in local time).
Temperature(F) : Shows the temperature (in Fahrenheit).
Wind_Chill(F) : Shows the wind chill (in Fahrenheit).
Humidity(%) : Shows the humidity (in percentage).
Pressure(in) : Shows the air pressure (in inches).
Visibility(mi) : Shows visibility (in miles).
Wind_Direction : Shows wind direction.
Wind_Speed(mph) : Shows wind speed (in miles per hour).
Precipitation(in) : Shows precipitation amount in inches, if there is any.
Weather_Condition : Shows the weather condition (rain, snow, thunderstorm, fog, etc.)
Amenity : A POI annotation which indicates presence of amenity in a nearby location.
Bump : A POI annotation which indicates presence of speed bump or hump in a nearby location.
Crossing : A POI annotation which indicates presence of crossing in a nearby location.
Give_Way : A POI annotation which indicates presence of give_way in a nearby location.
Junction : A POI annotation which indicates presence of junction in a nearby location.
No_Exit : A POI annotation which indicates presence of no_exit in a nearby location.
Railway : A POI annotation which indicates presence of railway in a nearby location.
Roundabout : A POI annotation which indicates presence of roundabout in a nearby location.
Station : A POI annotation which indicates presence of station in a nearby location.
Stop : A POI annotation which indicates presence of stop in a nearby location.
Traffic_Calming : A POI annotation which indicates presence of traffic_calming in a nearby location.
Traffic_Signal : A POI annotation which indicates presence of traffic_signal in a nearby location.
Turning_Loop : A POI annotation which indicates presence of turning_loop in a nearby location.
Sunrise_SunsetShows : the period of day (i.e. day or night) based on sunrise/sunset.
Civil_TwilightShows : the period of day (i.e. day or night) based on civil twilight.
Nautical_Twilight : Shows the period of day (i.e. day or night) based on nautical twilight.
Astronomical_Twilight : Shows the period of day (i.e. day or night) based on astronomical twilight.

