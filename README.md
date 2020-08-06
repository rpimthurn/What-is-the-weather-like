# What's the Weather Like?



## WeatherPy

In this example,I crreated a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

I consturcted a series of scatter plots to showcase the following relationships with the data:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

My analysis of the data is below:

* Based on the Latitude vs. Temperature graph there seems to be a peak around 0 degrees latitude which makes sense because that would be the equator of the globe. What makes this data interesting is that at the same distance either direction from latitude (60 Degrees), the graphs temperature is lower in the norther hemisphere. This of course can be explained by the northern hemisphere being in winter season while the souther has its summer.
* The City Longitude vs. City Latitude grapgh shows the random locations of the city that were pulled from the API. By looking at the wind speed, cloudiness, and humidity there does not seem to be a strong coorelation between these variables and the latiude.
* The Humidity graph does show that most of the data points range in a 60 to 100% Humidity. This could be due to the fact that most of the citys are close to a body of water. The longitutde vs. latitude graph is a cool represenation of where all the cities are and shows us that cities could be close to the water since it outlines the continents of the globe.





