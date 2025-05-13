
# Weather App

A simple and responsive weather application that allows users to check the weather of any city around the world. The app fetches weather data from the [OpenWeatherMap API](https://openweathermap.org/api) and displays the current temperature, humidity, wind speed, and weather condition. Additionally, it uses the [Unsplash API](https://unsplash.com/documentation) to fetch a background image related to the city.

## Features
- **Weather Data**: Displays current weather conditions, temperature (in Celsius), humidity, and wind speed.
- **Dynamic Weather Icons**: Displays different weather icons based on the condition (e.g., clear, cloudy, rain, etc.).
- **City Search**: Allows users to search for weather in any city around the world.
- **Background Image**: Fetches and sets a background image related to the searched city from Unsplash.
- **Responsive Design**: The app is designed to be responsive, working well on both desktop and mobile devices.

## Screenshots

![Weather App Screenshot](./screenshots/weather-app.png)

*(Add your own screenshot here, or remove this section if not applicable)*

## Demo

You can try the app live here: [Demo Link](#)  
*(If deployed, add a live link to your app here, such as Netlify, GitHub Pages, etc.)*

## Installation

To run this project locally, follow the steps below:

### 1. Clone the Repository
First, clone the repository to your local machine:
```bash
git clone https://github.com/yourusername/weather-app.git
```

### 2. Navigate to the Project Folder
```bash
cd weather-app
```

### 3. Open `index.html` in Your Browser
After navigating to the folder, you can simply open `index.html` in your browser to see the app in action. Just double-click it, and it will open in your default web browser.

```bash
open index.html  # On MacOS
start index.html # On Windows
```

## Usage

1. Open the app in your browser.
2. Enter the name of a city in the search bar.
3. Click the search button or press Enter.
4. The app will display the weather information for the selected city, including temperature, humidity, wind speed, and weather condition.
5. If the city name is invalid, an error message will appear.
6. The background image related to the city will also be displayed.

## Technologies Used

- **HTML5**: Structure of the app.
- **CSS3**: Styling the app with a responsive design.
- **JavaScript (ES6+)**: Fetching data from external APIs and handling user interactions.
- **OpenWeatherMap API**: Provides weather data (temperature, humidity, wind speed, etc.).
- **Unsplash API**: Fetches background images related to the city.

## API Keys

To use the weather and image services, you need to replace the placeholder API keys in the code with your own API keys.

### OpenWeatherMap API Key
You can sign up for an API key at [OpenWeatherMap API](https://openweathermap.org/appid) and replace it in the JavaScript code.

### Unsplash API Key
You can sign up for an API key at [Unsplash API](https://unsplash.com/documentation) and replace it in the JavaScript code.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

