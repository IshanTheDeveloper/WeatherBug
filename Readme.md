Overview
WeatherBug is a simple web application that allows users to get real-time weather information for any location around the world. The application fetches weather data using an external weather API and provides detailed information such as temperature, humidity, wind speed, and more. Users can enter a location or use their current geolocation to retrieve weather updates.

Features

Search for Weather: Users can input a city name to get current weather data.
Current Location: The app can automatically fetch weather data based on the user's geolocation.
Recent Searches: The app saves and displays recent searches for easy access.
Detailed Weather Information: Users can view various weather metrics including temperature, pressure, humidity, and more.
Responsive Design: The application is designed to work on multiple device sizes.

Technologies Used
HTML: For the structure of the web page.
CSS: For styling the application.
JavaScript: For handling user interactions and fetching weather data from the API.
Font Awesome: For utilizing various icons in the UI.

Getting Started

Prerequisites
A web browser to run the application.
Internet access to fetch weather data from the API.

Installation
Clone or download the repository.
Open index.html in your web browser.

API Key
The application uses the WeatherAPI for fetching weather data. You need to replace the apiKey variable in the JavaScript code with your own API key.

const apiKey = "YOUR_API_KEY_HERE";

Usage

Open the application in your web browser.
Enter a city name in the input field and click "Get Weather" to view the weather information.
Click "Use Current Location" to fetch weather data based on your current location.
Recent searches will be stored and displayed for future reference.

File Structure

/WeatherBug
│
├── index.html # Main HTML file
├── style.css # CSS styles for the application
├── index.js # JavaScript file for functionality
└── README.md # Documentation

Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

License :
This project is open-source and available under the MIT License.

Acknowledgments : WeatherAPI for the weather data.
Font Awesome for the icons used in the application.
