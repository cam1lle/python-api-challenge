# python-api-challenge

This repository contains the Python API Challenge project files, which aim to answer the fundamental question of "What is the weather like as we approach the equator?" using Python requests, APIs, and JSON traversals.

**WeatherPy**

In this deliverable, I have created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python library and the OpenWeatherMap API. The WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file guided me through the process of using my Python coding skills to develop a solution to address the required functionalities.

**Requirements**

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, I created a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, I computed the linear regression for each relationship. I separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). I defined a function in order to create the linear regression plots. After that, I created a series of scatter plots, including the linear regression line, the model's formula, and the r values.

**Plots**

I created the following plots:

Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude
After each pair of plots, I explained what the linear regression is modeling. I also described any relationships that I noticed and any other findings I uncovered.

**VacationPy**

In this deliverable, I used my weather data skills to plan future vacations. I used Jupyter notebooks, the geoViews Python library, and the Geoapify API.

**Requirements**

My main tasks were to use the Geoapify API and the geoViews Python library and employ my Python skills to create map visualizations.

**Deliverables**

I created a map that displays a point for every city in the city_data_df DataFrame. I used this map to find ideal hotels for a vacation based on customers' weather preferences. I also added a heatmap to illustrate the relationship between latitude and temperature.

The files included in this repository are:

WeatherPy.ipynb: the Jupyter notebook containing the code for the WeatherPy deliverable
VacationPy.ipynb: the Jupyter notebook containing the code for the VacationPy deliverable
api_keys.py: file to store API keys. This file is not included in the repository for security reasons.
.gitignore: a file to specify which files should be ignored by Git. The api_keys.py file is included in this file.
