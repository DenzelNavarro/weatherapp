# Weather App

A simple weather application that provides real-time weather updates based on the city entered by the user. The app fetches data from the OpenWeatherMap API to display current temperature, humidity, and wind speed for the specified city.

## Features

- Fetches real-time weather data for any city around the world.
- Displays temperature, humidity, and wind speed.
- Provides a visual representation of the current weather condition with icons.
- Input validation to handle incorrect or invalid city names.

## How It Works

1. The user enters the name of a city in the search bar.
2. The app fetches weather data using the OpenWeatherMap API.
3. If the city is valid, it displays the temperature, humidity, and wind speed.
4. If the city is invalid, an error message is shown, prompting the user to try again.

### Example:

- If you enter `New York`, it will display:
  - **Temperature**: 22°C
  - **Humidity**: 50%
  - **Wind Speed**: 15 km/h
  - Along with an appropriate weather icon (e.g., clouds, clear, rain).

## Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Styling and layout (color scheme: `#253949`, `#259ed9`, `#c3e4f3`, `#91cfec`).
- **JavaScript**: Fetching data from the API and dynamically updating the UI.
- **OpenWeatherMap API**: Source of real-time weather data.