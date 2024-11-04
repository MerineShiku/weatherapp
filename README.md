Weather App
Overview
This Weather App is a simple JavaScript-based web application that fetches and displays current weather information for any city.

Features

Search Weather by City: Enter a city name to retrieve the current weather.
Weather Details Display: Shows temperature, humidity, wind speed, and weather description with an icon.
Dynamic Background: The background updates to an image relevant to the queried city, using Unsplash images.
Real-Time Data: Fetches live data from the OpenWeather API.
Error Handling: Alerts users if the weather for the requested city is not found.


Project Structure
 . fetchWeather: Fetches weather data for a given city using OpenWeather API.
 . displayWeather: Displays the fetched weather details on the page.
. search: Reads the city name from the search bar and fetches weather data.
. Event Listeners:
. click on search button to initiate a weather search.
. keyup event on the search bar to allow "Enter" key as a shortcut for searching.



API Key
This application requires a valid OpenWeather API key. Replace the placeholder API key  with your own API key from OpenWeather.


