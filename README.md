# Weather App

This is a simple weather application built using HTML, CSS, and JavaScript. It allows users to search for the current weather conditions of a city by entering the city name. The app fetches data from the OpenWeatherMap API and displays the temperature, weather description, humidity, and wind speed.

## Features

- Search for weather conditions by city name
- Display current temperature, weather description, humidity, and wind speed
- Responsive design
- Error handling for invalid city names
- Weather icons downloaded from the 'Icons8' website

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Installation

To use this project, simply clone the repository or download the ZIP file and open the `index.html` file in your web browser.


## Usage

1. Open the `index.html` file in your web browser.
2. Enter a city name in the search box and click the search button (magnifying glass icon).
3. The app will fetch and display the current weather conditions for the entered city.
4. If an invalid city name is entered, an error message will be displayed.

## API Key

This project uses the OpenWeatherMap API to fetch weather data. To use the app, you need to obtain an API key from the OpenWeatherMap website.

1. Go to the [OpenWeatherMap website](https://openweathermap.org/) and sign up for a free account.
2. Once logged in, click on your user name in the top-right corner and select "My API Keys."
3. Generate a new API key by clicking on the "Generate" button.
4. Copy the generated API key.
5. In the `index.js` file, replace `'a30c8e22e6a7035037283bb8671fe877'` on line 9 with your own API key.

Note: Be sure to keep your API key secure and not share it publicly.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
