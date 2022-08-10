# World_Weather_Analysis

## Overview

Beta testers love the PlanMyTrip app and recommend adding the weather description to the weather data previously retrieved. The purpose of this analysis is to update the app to allow the beta testers to use input statements to filter the data for their weather preferences, which will identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will be able to choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, a travel route between the four cities and a marker layer map will be created.

## Resources
### Software
- Python 3.7.6
- Conda 4.13.0
- Jupyter Notebook 
- Dependencies:
  - Python Pandas Library
  - Python Numpy Library
  - Python Citipy Library
  - Python Requests Library
  - Python Time and Datetime Libraries
- API Keys:
  - OpenWeatherMap
  - Google Maps
  - Google Directions

## Results

### Deliverable 1: Retrieve Weather Data

The full Jupyter Notebook for this deliverable can be referenced here: 
https://github.com/lkachury/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb

The purpose of this deliverable was to generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city using the citipy module, and perform an API call with the OpenWeatherMap. Then, retrieve the following information from the API call [Latitude and longitude, maximum temperature, percent humidity, percent cloudiness, wind speed, and weather description (for example, clouds, fog, light rain, clear sky)] for each city. And lastly, create a new DataFrame containing the updated weather data and export it as a CSV file. The table below is the DataFrame created using the OpenWeatherMap API:

![image](https://user-images.githubusercontent.com/108038989/183809219-a2071682-ea4f-4809-835a-a68c4b8683f2.png)

### Deliverable 2: Create a Customer Travel Destinations Map

The full Jupyter Notebook for this deliverable can be referenced here:
https://github.com/lkachury/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb

The purpose of this deliverable is to use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers. 

The image below displays potential travel destinations and nearby hotels by using the Google Maps API:

![image](https://user-images.githubusercontent.com/108038989/183809108-dc767a4b-1360-4e28-9ca3-f8ff3d9cbc5c.png)

### Deliverable 3: Create a Travel Itinerary Map

The full Jupyter Notebook can be referenced here: 
https://github.com/lkachury/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb

The purpose of this deliverable was to use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary. 

The images below display the driving travel route vacation itinerary and city description for four cities in Indonesia by using the Google Directions API: 

![WeatherPy_travel_map](https://user-images.githubusercontent.com/108038989/183820401-034a0ba6-0427-4d3a-af7a-09772c1adedd.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/108038989/183820993-3ac05e65-dbf8-400a-86f8-24f05a859720.png)
