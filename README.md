# WeatherPy

## Purpose
Make use of Python, Pandas, and APIs to propose travel plans based on user input on the weather preferences, and visualize the results in Google maps:
- Add the weather description to the marker layer in the Google map.
- Based on beta tester input to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary.
- Using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Libraries and API used
- Library:
  1. [citipy](https://pypi.org/project/citipy/): determine a city based on given latitude and longitude.
    
- APIs:
  1. [OpenWeatherMap API](https://openweathermap.org) - access current weather data for any location on Earth for over 200,000 cities.
  2. [Google Maps Platform](https://console.cloud.google.com/google/maps-apis):
    - Maps Javascript API - use marker layer to add hotel name, city name, and weather info to the map
    - Places API - use selected city's latitude and longitude to get the nearest hotel
    - Directions API - draw routes between points denoted by latitude and longitude
 
