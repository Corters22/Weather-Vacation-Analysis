# Python API Challenge

### How to find the perfect vacation spot.

#### Description

This challenge includes two parts, WeatherPy and VacationPy. I started with WeatherPy and randomly choose a collection of latitude and longitude coordinates. From these coordinates, I ran through the cities module and grab the city that is closest to the coordinates. Using these cities, I pulled the current weather information from the public weather API, api.openweathermap.org/data/2.5/weather?q. Note that not all cities will produce a result. After pulling the weather information, I then saved the city and weather information to a csv and analyzed the weather data. There are several charts available with observations based on those charts.

The VacationPy starts with the city csv pulled from WeatherPy. I started with displaying the humidity of those cities with a google heatmap. I then chose cities based off of "perfect" weather conditions. Your idea of perfect weather could change the results. From these cities, I found the closest hotels and marked them on our existing heatmap using the google maps nearby API (https://maps.googleapis.com/maps/api/place/nearbysearch/json). Included is also an info_box with the hotel name, city and country.

#### Included Images

You can find all the chart images in the Images directory by clicking [here.](Images)
 
#### Conclusions

I ran this code in Feburary 2021. My conclusions are based on weather from that time. You can run this with your own api keys and may find different correlations depending on time of year and which cities were randomly chosen.
