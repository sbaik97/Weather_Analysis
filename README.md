# Weather_Analysis
Using APIs to Visualize Weather Data

# Background
Use google maps API and OpenWeather API to create heatmaps and pop-up location markers for hotels within a certain radius of the cities where our customers travel.
Herein, we practice the JSON analysis, visualization, and statistical skills by retrieving and analyzing weather data for a hypothetical travel company, PlanMyTrip. Successfully completing the tasks will draw on the knowledge of Python, decision and repetition statements, data structures, Pandas, Matplotlib, and SciPy statistics.

## Basic Project Plan

1. Task: Collect and analyze weather data across cities worldwide.
2. Purpose: Use the data to recommend ideal hotels based on clients’ weather preferences.
3. Method: Create a Pandas DataFrame with 500 or more of the world’s unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

## Main Stages

1. Collect the Data

- Use the *NumPy module* to generate more than 1,500 random latitudes and longitudes.

- Use the *citipy module* to list the nearest city to the latitudes and longitudes.

- Use the *OpenWeatherMap API* to request the current weather data from each unique city.

- Parse the *JSON* data from the API request.


2. Exploratory Analysis with Visualization

- Create scatter plots and linear regression of the weather data and determine the correlations.

- Create a series of heatmaps using the Google Maps and Places API.

3. Visualize Travel Data

Create a heatmap with pop-up markers that can display information on specific cities based on a customer’s travel preferences. 

# Challenge

## Background

Add the amount of rainfall or snowfall within the last three hours so that customers can filter the DataFrame based on the temperature range and whether or not it is raining or snowing. Create a directions layer Google map that shows the directions between multiple cities for travel.

## Process

**1. Get the Weather Description and Amount of Precipitation for Each City.** 

- Jupyter Notebook: [Weather_Database.ipynb](/Weather_Database.ipynb)

- Result csv file: [WeatherPy_challenge.csv](/data/WeatherPy_challenge.csv)

- **Conclusion: There are 56 cities recorded rainfall, and 28 cities snowing.**

**2. Have Customers Narrow Their Travel Searches Based on Temperature and Precipitation.**

- Jupyter Notebook: [Vacation_Search.ipynb](/Vacation_Search.ipynb)

- Result csv file: [WeatherPy_vacation.csv](/data/weatherPy_vacation.csv)

- Result dataframe screenshot: [Hotel_DataFrame.png](/filtered_Hotel_DataFrame.PNG)

- Google marker_layer map ![WeatherPy_vacation_map.png.png](/image/WeatherPy_vacation_map.png.png)

- Google pop-up box marker_layer map ![vacation_pop-up_Map.PNG](/image/vacation_pop-up_Map.PNG)

**3. Create a Travel Itinerary with a Corresponding Map.**

- Jupyter Notebook: [Vacation_Itinerary.ipynb](/Vacation_Itinerary.ipynb)

- The route between four cities from the customer’s possible travel destinations:
![WeatherPy_travel_map.PNG](/image/WeatherPy_travel_map.PNG)

- Map with pop-up markers for the four cities:
![WeatherPy_travel_map_markers.PNG](/image/WeatherPy_travel_map_markers.PNG)



## Conclusion
1. 
