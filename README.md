# World_Weather_Analysis

This project involves the utilization of APIs in order to provide a product that allows users to find specific weather data, filter out travel destinations and create a travel itinerary based on their preferences. 

In order to create this product, the following resources were used: APIs, Python, Pandas, gmaps, Citypy, Matplotlib, Jupyter Notebook, and JSON. 

## Deliverable 1: Retrieve Weather Data

Weather data was retrieved through a generated set of 2,000 latitudes and longitudes.  By performing an API call ith the OpenWeatherMap, current weather data and descriptions for each city were found and displayed in a new DataFrame. 

<img width="533" alt="Weather Data" src="https://user-images.githubusercontent.com/110862583/191567316-1e905d60-cd61-4ef4-b5f0-b9e18bb55d55.png">

## Deliverable 2: Create a Customer Travel Destinations Map

Through retrieved custommer weather preferences, potential travel destinations and nearby hotels were identified on a layer map with pop-up markers for easier viewing and selection. 

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/110862583/191569423-d159687a-93f4-4253-b716-a3c03ccbfbaa.png)

## Deliverable 3: Create a Travel Itinerary Map

Through the use of Google Directions API, a custom travel intinerary was created -- which shows a route between four citied based on customer travel preferences, as wlel as pop-up markers for each city on the itinerary. 

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/110862583/191570165-e6ec3183-6c59-4c93-8254-06ccc0808c01.png)
