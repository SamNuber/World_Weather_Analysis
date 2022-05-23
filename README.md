# World_Weather_Analysis

## Overview of the Project

The purpose of this project is to create the ability for travellers to search for areas to visit based on weather criteria, find nearby hotels and plan travelling routes to visit your chosen locations.

## Project Results

Using the google API, we are able to filter for possible destinations based off the following.
* Latitude and longitude
* Cloudiness
* Maxi temperature
* Generalized weather description
* Humidity percentage
* Wind speed

I created DataFrames to store hotel names along with city, country, max temp, and coordinates.

### Map Generation

Using temperature as a search criteria, I chose a starting/ending city as well as 3 other cities to travel to. I then created a route that leads to all those destinations which begins and ends in the starting city.

