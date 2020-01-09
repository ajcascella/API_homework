## Background

Using Python requests, APIs, and JSON traversals I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Specifically, I used the CitiPy library and the [OpenWeatherMap API](https://openweathermap.org/api) to create representative model of weather across world cities.

## Step by Step

* Randomly selected **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Performed a weather check on each of the cities using a series of successive API calls.
* Included a print log of each city as it's being processed with the city number and city name.
* Built a series of scatter plots to showcase the following relationships:
    * Temperature (F) vs. Latitude
    * Humidity (%) vs. Latitude
    * Cloudiness (%) vs. Latitude
    * Wind Speed (mph) vs. Latitude