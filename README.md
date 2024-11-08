#Weather App
A simple weather application that fetches and displays current weather data for any city in the world. This app was built using HTML, CSS, and JavaScript, with data sourced from a weather API.

##Features
Search Functionality: Users can search for weather information by entering the city name.
Weather Details: Displays current temperature, weather description, humidity, and wind speed.
Responsive Design: Optimized for various screen sizes, making it accessible on both desktop and mobile devices.

##Technologies Used
HTML: Structure of the application
CSS: Styling and layout
JavaScript: Fetches data from the weather API and dynamically updates the UI
Setup


##API
This app uses the OpenWeatherMap API to fetch weather data. To set up:

Sign up on OpenWeatherMap to get an API key.
Replace YOUR_API_KEY in your JavaScript file with your actual API key:
javascript
Copy code
const apiKey = 'YOUR_API_KEY';
##Usage
Enter the city name in the search box and press Enter.
The app will display the current weather details for the specified city.
##Project Structure
graphql
Copy code
weather-app/
├── index.html         # Main HTML file
├── style.css          # Styling for the app
├── script.js          # JavaScript logic and API calls
└── README.md          # Project documentation
