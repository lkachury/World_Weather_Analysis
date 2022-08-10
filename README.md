# World_Weather_Analysis

##

Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

Deliverable 1: Retrieve Weather Data
Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city using the citipy module, and perform an API call with the OpenWeatherMap. Retrieve the following information from the API call [Latitude and longitude, maximum temperature, percent humidity, percent cloudiness, wind speed, and weather description (for example, clouds, fog, light rain, clear sky)] for each city. Then, create a new DataFrame containing the updated weather data and export it as a CSV file.

https://github.com/lkachury/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb

![image](https://user-images.githubusercontent.com/108038989/183809219-a2071682-ea4f-4809-835a-a68c4b8683f2.png)


Deliverable 2: Create a Customer Travel Destinations Map
Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

https://github.com/lkachury/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb

![image](https://user-images.githubusercontent.com/108038989/183809108-dc767a4b-1360-4e28-9ca3-f8ff3d9cbc5c.png)

Deliverable 3: Create a Travel Itinerary Map
Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

https://github.com/lkachury/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb


![WeatherPy_travel_map](https://user-images.githubusercontent.com/108038989/183820401-034a0ba6-0427-4d3a-af7a-09772c1adedd.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/108038989/183820838-a296ce27-01e6-474b-888f-ffb3727d4acb.png)
