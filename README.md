# World_Weather_Analysis
Analyze WeatherPy weather data using Python 3.9.6, Jupyter Notebook 6.3.0, Google Maps APIs and OpenWeather APIs

## Overview of Project

### Background
As an introduction to Python APIs, this project calls GoogleMaps and OpenWeather APIs in Pandas DataFrames with Python to analyze WeatherPy data. In the original project, I analyzed historic weather data from random locations to study the relationships between latitude and weather parameters, such as humidity, wind speed and cloudiness. The results of this analysis were visualized in linear regression scatter plots and Google Maps marker and heatmaps.

### Purpose
The purpose of this analysis was to use Google Maps and OpenWeather APIs to get historical weather data to and filter the results based on user input preferences. To practice using heatmaps and marker layers, I also produced maps displaying vacation options and directions based on input preferences for a prospective travel application.


## Results

### Deliverable 1: _Retrieve Weather Data_
Weather data was retrieved for 2000 cities from randomized latitudes and longitudes. Along with city, country and various weather parameters, the weather description was displayed in the data summary by using index listing in a for loop. 

<img width="599" alt="Screen Shot 2021-07-27 at 2 19 09 PM" src="https://user-images.githubusercontent.com/85946042/127392822-e6a2c1c4-f4d7-4b0e-a060-a897acb53bf0.png">


### Deliverable 2: _Create a Customer Travel Destinations Map_
Potential travel destinations were identified by filtering with user-input temperature preference. The travel destinations are displayed on a Google Maps marker layer, where each marker information box identifies the city, country, weather description, maximum temperature and nearby hotel information. The hotels were found by using a nearby search with the Google Maps API. 

<img width="660" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/85946042/127392613-40cded2f-66f2-4da9-8846-06671837111b.png">


### Deliverable 3: _Create a Travel Itinerary Map_
A potential travel itinerary was created by choosing four cities from the travel destinations map and creating a directions route between the four cities. The start city and end city are the same, so the route comes back to the starting point. To practice using marker layers, markers were then created for each of the four cities to show city, country, weather description, maximum temperature and nearby hotel information in each information box. The resulting maps could be used as a travel itinerary for a Mediterranean city tour. 

<img width="661" alt="Screen Shot 2021-07-27 at 3 22 59 PM" src="https://user-images.githubusercontent.com/85946042/127392849-24cbba96-7018-47f2-b9e3-a232fac899de.png">
<img width="658" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/85946042/127392646-ab278af4-3014-45b9-8d7b-8f9e3d733251.png">
<img width="924" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/85946042/127392660-c8761ca0-f502-4583-8ed0-640b084baf6a.png">


## Summary
In this analysis, I practiced calling APIs for weather and geocode data. The results were created by using maps with marker layers from Google Maps. In another iteration of this analysis, I would consider also displaying most popular tourist season dates for the destination. Another interesting data point to consider would be average plane prices from the user's home city to each destination. 

