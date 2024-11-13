Part 1 : WeatherPy
Using OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code.Created a series of scatter plots to showcase the following relationships:
Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

Doing brief summary analysis between the comparisons

Part 2 :  VacationPy
Project using Jupyter notebooks, the geoViews Python library, and the Geoapify API.

Created a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

Narrowed down the city_data_df DataFrame to find your ideal weather condition. For example:

A max temperature lower than 27 degrees but higher than 21

Wind speed less than 4.5 m/s

Zero cloudiness

Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, used the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

Added the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
