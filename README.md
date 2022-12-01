## Week6 - Python API Challenge: Author - Jyothi Palle

# Objective:

The activity is broken down into two deliverables, WeatherPy and VacationPy.

# Part 1: WeatherPy

In this deliverable, created a Python script to visualize the weather of over 500 cities of varying distances from the equator. Using citypy extracted the cities and using the city information extratced weather info using OpenWeatherMap API from an external site. 

Created scatter Plots to Showcase the Relationship Between Weather Variables and Latitude

* Latitude vs. Temperature

* Latitude vs. Humidity

* Latitude vs. Cloudiness

* Latitude vs. Wind Speed

Computed Linear Regression for Each Relationship, separately for Northern and Southern Hemisphere data. Below are my observations - 

* Found only Temperature vs latitude has strong corelation i.e near to the equator higher the temperature.
* Found no corelation between latitude and other weather variables like Humidity,cloudiness and wind speed


# Part 2: VacationPy

* Created a map that displays a point for every city in the city_data_df DataFrame as shown in the image. Used the humidity in each city as size in the map.

* Selected cities that has tempature between 20 and 27 degrees and wind speed less than 4.5m/s with zero cloudiness

* For each selected city, used the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

* Added the hotel name and the country as additional information in the hover message for each city on the map.
