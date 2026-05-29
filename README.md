# 🌦️ Weather App

A simple and responsive Weather Application built using **HTML, CSS, and JavaScript** that fetches real-time weather data from the OpenWeatherMap API.

## 🚀 Features

* Search weather by city name
* Real-time weather information
* Temperature in Celsius (°C)
* Humidity percentage display
* Wind speed information
* Dynamic weather icons based on weather conditions
* Error handling for invalid city names
* Responsive and user-friendly interface

## 📂 Project Structure

```text
weather-app/
│
├── weather.html
├── weather.css
├── images/
│   ├── search.png
│   ├── clear.png
│   ├── clouds.png
│   ├── rain.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── humidity.png
│   └── wind.png
└── README.md
```

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* OpenWeatherMap API

## 📸 Preview

The application displays:

* City Name
* Current Temperature
* Humidity Level
* Wind Speed
* Weather Condition Icon

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/weather-app.git
```

### 2. Navigate to the Project Folder

```bash
cd weather-app
```

### 3. Open the Application

Simply open `index.html` in your browser.

## 🔑 API Configuration

This project uses the OpenWeatherMap API.

1. Create a free account on OpenWeatherMap.
2. Generate your API key.
3. Replace the existing API key in the JavaScript code:

```javascript
const apikey = "YOUR_API_KEY";
```

## 🎮 How to Use

1. Enter a city name in the search box.
2. Click the search button.
3. The app fetches and displays current weather information.
4. If the city name is invalid, an error message will be shown.

## 🌤️ Supported Weather Conditions

The app currently displays different icons for:

* Clear
* Clouds
* Rain
* Drizzle
* Mist

Additional weather conditions can be added easily.

## 📱 Responsive Design

The application works across:

* Desktop Computers
* Laptops
* Tablets
* Mobile Devices

## 🔮 Future Improvements

* Search using Enter key
* Weather forecast for upcoming days
* Current location weather
* Sunrise and sunset times
* Atmospheric pressure details
* Dark mode support
* Loading animation while fetching data

## 👨‍💻 Learning Concepts

This project helps in understanding:

* Fetch API
* Async/Await
* API Integration
* DOM Manipulation
* Event Handling
* Error Handling in JavaScript

## ⚠️ Security Note

Avoid exposing your API key in public repositories. Store API keys in environment variables or backend services when deploying production applications.

## 📄 License

This project is open-source and available under the MIT License.

## ⭐ Acknowledgements

Weather data provided by OpenWeatherMap.
