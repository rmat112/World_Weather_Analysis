# World_Weather_Analysis
## Overview
PlanMyTrip app is a travel app we created before this challenge, it is up and running and working well. Beta testers recommended a few changes to take the app to the next level. Purpose of this challenge is to make the recommeneded changes as described in the summary section below. 
The deliverables were saved in 3 separate folders:<br/>
* [Weather_Database](https://github.com/rmat112/World_Weather_Analysis/tree/main/Weather_Database)<br/>
* [Vacation_Search](https://github.com/rmat112/World_Weather_Analysis/tree/main/Vacation_Search) and<br/>
* [Vacation_Itinerary](https://github.com/rmat112/World_Weather_Analysis/tree/main/Vacation_Itinerary)

## Tools
Python, Pandas, Matplotlib, citipy, NumPy, SciPy, OpenWeatherMap API, Google Maps API, Google Places API, Jupyter Notebook

## Summary
1. Adding the weather description to the weather data that we retrieved before and exporting the new dataframe as a csv file:
[WeatherPy_Database.csv](https://github.com/rmat112/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)

2. Using input statements to filter the data for their weather preferences and create a new dataframe. Filtered data is then used to identify potential travel destinations and nearby hotels, saved as a csv file: 
[WeatherPy_vacation.csv](https://github.com/rmat112/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv)

3.  A marker layer map is generated that has pop-up markers for each city on the map.
![WeatherPy_vacation_map.png](https://github.com/rmat112/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

4. From the list of potential travel destinations four cities are selected to create a travel itinerary. Using the Google Maps Directions API, a travel route was created between the four cities as well as a marker layer map.
 ![WeatherPy_travel_map.png](https://github.com/rmat112/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

5. Finally a marker layer map was created, where each marker shows hotel name, city, country, and current weather description with the maximum temperature.
![WeatherPy_travel_map_markers.png](https://github.com/rmat112/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
