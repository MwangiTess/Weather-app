# WeatherWise - Weather Dashboard

## Overview

WeatherWise is a simple weather dashboard that allows users to check the current weather and a 5-day forecast for a specific city or use their current location.

## Features

- **Search by City:** Enter a city name to get the current weather details and a 5-day forecast.
- **Use Current Location:** Get weather details based on the user's current location.
- **Responsive Design:** The dashboard is designed to be user-friendly on various devices.


## Technologies Used in WeatherWise Weather Dashboard

### 1. HTML
### 2. CSS
### 3. JavaScript

- **Description:**  In WeatherWise, JavaScript is crucial for interacting with the OpenWeatherMap API, handling user input, and dynamically updating the dashboard based on received data.

### 4. OpenWeatherMap API

- **Description:** The OpenWeatherMap API is a key component of WeatherWise, providing real-time weather data. The API key is essential for authentication and access to weather information. WeatherWise utilizes the API to fetch current weather details and a 5-day forecast based on user input or the user's current location.

   - **API Key:** Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) and replace the placeholder in the `index.js` file for seamless integration.

   - **Endpoints:** WeatherWise utilizes the OpenWeatherMap API endpoints to retrieve weather information. These endpoints include:
      - Current Weather: `http://api.openweathermap.org/data/2.5/weather`
      - 5-Day Forecast: `http://api.openweathermap.org/data/2.5/forecast`

   - **Data Handling:** The received JSON data from the API is processed in JavaScript to dynamically update the dashboard with details such as temperature, wind speed, humidity, and weather icons.

   - **Geocoding API:** Additionally, the Geographic Location API is used to obtain the latitude and longitude coordinates of a city based on user input, facilitating the retrieval of accurate weather information.

