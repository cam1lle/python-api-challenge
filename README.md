# Python API Challenge
## Background
I undertook a project to analyze weather data from cities around the world. The goal was to visualize the relationship between weather variables and latitude and use this information to plan future vacations.

## Repository Setup
To set up the project repository, I followed these steps:

1. Created a new repository named "python-api-challenge" specifically for this project.
2. Cloned the repository to my local machine.
3. Inside the local Git repository, created a directory named "WeatherPy" for the weather analysis.
4. Inside the "WeatherPy" directory, added the files "api_keys.py", "WeatherPy.ipynb", and "VacationPy.ipynb" from the starter code ZIP file.
5. Added a .gitignore file to prevent the API key file ("api_keys.py") from being shared publicly.

## WeatherPy
In the WeatherPy part of the project, I created a Python script to visualize the weather of over 500 cities at varying distances from the equator. I used the citipy library, the OpenWeatherMap API, and my problem-solving skills to analyze and plot the weather data.

## Requirements
1. Created scatter plots to showcase the relationship between weather variables and latitude:
* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed
2. Computed linear regression for each relationship and created scatter plots with the linear regression line, the model's formula, and the r values. Plots were separated into Northern Hemisphere and Southern Hemisphere.

## Analysis
After analyzing the scatter plots and linear regression results, I observed the following relationships and findings:

* Northern Hemisphere: Temperature vs. Latitude: There is a negative correlation between latitude and temperature in the Northern Hemisphere. As latitude increases, temperature tends to decrease.
* Southern Hemisphere: Temperature vs. Latitude: There is a positive correlation between latitude and temperature in the Southern Hemisphere. As latitude increases, temperature tends to increase.
* Northern Hemisphere: Humidity vs. Latitude: There is no significant correlation between latitude and humidity in the Northern Hemisphere.
* Southern Hemisphere: Humidity vs. Latitude: There is no significant correlation between latitude and humidity in the Southern Hemisphere.
* Northern Hemisphere: Cloudiness vs. Latitude: There is no significant correlation between latitude and cloudiness in the Northern Hemisphere.
* Southern Hemisphere: Cloudiness vs. Latitude: There is no significant correlation between latitude and cloudiness in the Southern Hemisphere.
* Northern Hemisphere: Wind Speed vs. Latitude: There is no significant correlation between latitude and wind speed in the Northern Hemisphere.
* Southern Hemisphere: Wind Speed vs. Latitude: There is no significant correlation between latitude and wind speed in the Southern Hemisphere.

## VacationPy
In the VacationPy part of the project, I used the weather data and various libraries, including geoViews and the Geoapify API, to plan future vacations based on ideal weather conditions.

Requirements
1. Created a map that displays a point for every city in the city_data_df DataFrame, where the size of the point represents the humidity in each city.
2. Narrowed down the city_data_df DataFrame to find cities with ideal weather conditions, such as a max temperature between 21 and 27 degrees Celsius, wind speed less than 4.5 m/s, and zero cloudiness.
3. Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4. Used the Geoapify API to find the first hotel located within 10,000 meters of the coordinates for each city.
5. Added the hotel name and country as additional information in the hover message for each city on the map.

## Analysis
Using the generated map and the filtered data, I was able to identify cities that meet the specified weather conditions for ideal vacations. The map provided a visual representation of the humidity in each city, helping me make informed decisions about potential travel destinations.
