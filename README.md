# World_Weather_Analysis

## Overview of analysis: 
Updating PlanMyTrip app to include weather description among other things to allow users to make informed travel destination choices. 

## Results: 
1) Retrieve Weather Data by:
	- generating a set of 2000 random latitudes and longitudes
	- retieving nearest city data
	- performing API call with OpenWeatherMap

2) Create a Customer Travel Destinations Map by:
	- using statements to retrieve customer weather preferences
	- identify potential travel destinations and hotels
	- create a marker layer map with pop-up markers

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/96352427/153736113-311dec29-2aff-4a2f-b277-ccb0bfe2a823.PNG)

3) Create a Travel Itineary Map by:
	- using Google Directions API to create a itineary showing route between 4 cities chosen by customer
	- creating a marker layer map with pop-up marker for each city on itineary

![WeatherPy_travel_map](https://user-images.githubusercontent.com/96352427/153736132-0f74cd44-da28-4fb5-be1c-b5d289db8f38.PNG)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/96352427/153736138-d665eb87-3e09-4e21-b275-9d16d9b688f4.PNG)
