# Weather-API-app
A Python desktop weather application built with PyQt5 that uses the OpenWeather API to display real-time weather data for user-selected cities.

# 🌦️ Python Weather App

A desktop weather application built with **Python** and **PyQt5** that retrieves current weather information using the **OpenWeather API**.

The user can enter a city name and view the current temperature, weather description, and an emoji representing the current weather conditions.

## 🚀 Features

* Search for current weather by city name
* Displays temperature in Celsius
* Displays a description of the current weather
* Displays different weather emojis depending on the weather condition
* Retrieves live weather data using the OpenWeather API
* Handles HTTP errors such as invalid cities and API authentication errors
* Handles connection errors and request timeouts
* Simple graphical user interface built using PyQt5

## 🛠️ Technologies Used

* **Python**
* **PyQt5**
* **Requests**
* **OpenWeather API**
* **Git & GitHub**

## 📸 Example

If the user enters:

```text
London
```

The application may display something similar to:

```text
London

16°C

☁️

overcast clouds
```

The displayed weather will depend on the current weather conditions in London.

## 📦 Installation

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate into the project

```bash
cd WeatherAPI
```

### 3. Install the required packages

```bash
pip install PyQt5 requests
```

## 🔑 OpenWeather API Key

This project requires an API key from OpenWeather.

1. Create an account on the OpenWeather website.
2. Generate your own API key.
3. Open `weather_api.py`.
4. Find the following line:

```python
api_key = "ENTER_YOUR_API_KEY_HERE"
```

5. Replace `ENTER_YOUR_API_KEY_HERE` with your own API key.

For example:

```python
api_key = "YOUR_API_KEY"
```


Then click **Get Weather** to retrieve the current weather information.

## 🌤️ Weather Conditions

The application uses weather condition IDs returned by the OpenWeather API to display different emojis.

Examples include:

* ☀️ Clear weather
* ☁️ Cloudy weather
* 🌧️ Rain
* ⛈️ Thunderstorms
* ❄️ Snow
* 🌬️ Atmospheric conditions
* 🌪️ Tornado
* 🌋 Volcanic ash

## 🧠 What I Learned

Through developing this project, I gained experience with:

* Building graphical user interfaces with **PyQt5**
* Working with **REST APIs**
* Sending HTTP requests using the Python `requests` library
* Processing **JSON** responses
* Using Python classes, methods, and object-oriented programming
* Implementing exception and HTTP error handling
* Converting and displaying weather data
* Styling PyQt5 widgets using stylesheets
* Using Git and GitHub for version control

## 🔮 Future Improvements

Possible future improvements include:

* Add a country selector for cities with the same name
* Add humidity and wind speed
* Add a Celsius/Fahrenheit toggle
* Add multi-day weather forecasts
* Improve the graphical interface
* Store API keys using environment variables
* Add weather icons and dynamic backgrounds




Created as a Python project while studying at university.

