# Weather-App
A simple weather app made with HTML,CSS and JS



Weather App
Overview
This is a simple Weather App built using HTML, CSS, and JavaScript that allows users to search for the current weather conditions in any city. The app fetches weather data from the OpenWeatherMap API and displays the temperature, humidity, wind speed, and a weather icon based on the conditions.

Features
Search for weather by entering a city name.
Displays current temperature, humidity, and wind speed.
Dynamic weather icons that change based on the weather conditions (e.g., clear, rain, clouds).
Provides error handling for invalid city names.
Tech Stack
HTML
CSS
JavaScript (ES6+)
OpenWeatherMap API
Setup Instructions
Prerequisites
A modern web browser (e.g., Chrome, Firefox, Safari).
Internet connection to fetch weather data from the OpenWeatherMap API.
Steps to Run the Project
Download or clone the repository.


Open the project folder.

Navigate to the folder where the project files are located.

API Key Setup

The app uses OpenWeatherMap API to fetch weather data. You need to add your own API key to use the app.

Sign up at OpenWeatherMap to get your API key.
Replace the value of apikey in the JavaScript file with your own API key.
Open the index.html file in a browser.

You can now search for any city's weather and see the results.

File Structure
graphql
Copy code
- index.html       # The main HTML file containing the structure of the app.
- styles.css       # The CSS file for styling the Weather App.
- script.js        # The JavaScript file that handles the functionality of the app.
- images/          # Folder containing images for weather icons and UI elements.
  - clear.png
  - clouds.png
  - rain.png
  - drizzle.png
  - mist.png
  - humidity.png
  - wind.png
  - search.png
How It Works
The user enters a city name in the search box and clicks the search button.
A request is made to the OpenWeatherMap API with the city name and an API key.
If the city is valid, the weather data is fetched, and the app displays the temperature, humidity, wind speed, and an appropriate weather icon.
If the city name is invalid, an error message is shown to the user.
Contribution
Feel free to fork the repository and contribute by fixing bugs, adding new features, or improving the code. If you have any suggestions or improvements, open an issue or submit a pull request.

License
This project is open-source and available under the MIT License.


