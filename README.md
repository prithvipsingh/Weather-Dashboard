# Deployed Application Link:
https://prithvipsingh.github.io/Weather-Dashboard/Develop/index.html

# 06 Server-Side APIs: Weather Dashboard

Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. 
My challenge is to build a weather dashboard that will run in the browser and feature dynamically updated HTML and CSS.
## Serverside API 
I am using the [OpenWeather API](https://openweathermap.org/api) to retrieve weather data for cities. The documentation includes a section called "How to start" that will provide basic setup and usage instructions. Use `localStorage` to store any persistent data.

## User Story

```
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly
```

## Acceptance Criteria

```
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
WHEN I open the weather dashboard
THEN I am presented with the last searched city forecast
```

The following image demonstrates the application functionality:

![weather dashboard demo](./Weather-Dashboard/Assets/Weather-Dashboard.png)



# How do you deliver this? Here are some guidelines:


Use the OpenWeather API to retrieve weather data for cities. The documentation includes a section called "How to start" that will provide basic setup and usage instructions.


Use AJAX to hook into the API to retrieve data in JSON format.
Your app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.
Display the following under current weather conditions:

City

Date

Icon image (visual representation of weather conditions)

Temperature

Humidity

Wind speed

UV index

Include a search history so that users can access their past search terms. Clicking on the city name should perform a new search that returns current and future conditions for that city.

Include a 5-Day Forecast below the current weather conditions. Each day for the 5-Day Forecast should display the following:


Date


Icon image (visual representation of weather conditions)


Temperature


Humidity

Use localStorage to store any persistent data.


# Minimum Requirements
Functional, deployed application.

GitHub repository with a unique name and a README describing the project.

User can search for weather reports by city using the openweathermap API.

After searching for a city, the following information is displayed:

Current temperature

Current humidity

Windspeed

Uv index

5 day forecast




Application uses icons to represent weather conditions.


Application stores previously searched for cities in localstorage and displays them to the user.


Application loads last searched city forecast on page load.


# Bonus

Use the Geolocation API to add the user's current location to the initial landing page.


Add the application to your portfolio.


## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
