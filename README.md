Weather Information App:

This command-line Java application retrieves current weather information for any city entered by the user. It uses APIs to fetch geolocation data and display weather details such as temperature, wind speed, and the current time.


Features:

Retrieve current temperature, wind speed, and time for any city.
Allows checking weather for multiple cities continuously.
Exit the application by typing “No.”


Getting Started:

Java Development Kit (JDK) version 8 or later.
json-simple library for JSON parsing (if not included, download and add to project dependencies).


Setup:

Clone the Project: Download or clone the repository.
Add json-simple Library:
Download the json-simple jar.
Add the .jar file to your project’s build path in your IDE (e.g., IntelliJ, Eclipse).


Usage:

The app will display:
Current Time: Timestamp of the weather data.
Temperature (C): Current temperature in Celsius.
Wind Speed: Wind speed in km/h.


Implementation Details:

Main Loop: The program continuously prompts for a city name until "No" is entered.
Location Data (getLocationData): Calls Open-Meteo’s geocoding API to fetch latitude and longitude using the city name.
Weather Data (displayWeatherData): Calls Open-Meteo’s weather API with latitude and longitude values to display weather information.


Error Handling:

Connection Issues: Displays an error message if unable to connect to the API.
Invalid City Name: Alerts the user if location data is unavailable for the entered city.
Exceptions: Catches and prints exceptions for troubleshooting.
