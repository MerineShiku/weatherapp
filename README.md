Weather App
Overview
This Weather App is a simple JavaScript-based web application that fetches and displays current weather information for any city.


 It uses the OpenWeather API to get real-time weather data.

Features

Search Weather by City: Enter a city name to retrieve the current weather.
Weather Details Display: Shows temperature, humidity, wind speed, and weather description with an icon.
Real-Time Data: Fetches live data from the OpenWeather API.
Error Handling: Alerts users if the weather for the requested city is not found.


Project Structure

fetchWeather: Fetches weather data for a given city using OpenWeather API.
displayWeather: Displays the fetched weather details on the page.
search: Reads the city name from the search bar and fetches weather data.
Event Listeners:
click on search button to initiate a weather search.
keyup event on the search bar to allow "Enter" key as a shortcut for searching.



How to Use


Search for Weather: Enter a city name in the search bar and either press "Enter" or click the search button.
View Results: The app will display the city's name, weather icon, temperature, humidity, wind speed, and description.
OpenWeather API: The app relies on OpenWeather API to fetch current weather data.



Setup and Configuration
Clone the repository.
Open index.html in a browser to run the app.
Ensure you have an active internet connection as the app fetches data from external APIs.
Replace the apiKey with your own from OpenWeather to ensure the app functions.
Error Handling
If the city name is not recognized, an alert will pop up indicating that no weather data was found.



API Key
This application requires a valid OpenWeather API key. Replace the placeholder API key  with your own API key from OpenWeather.


