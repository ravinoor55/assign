# 🌟 weather app

## 📌 Description
This is a weather forecast web app built using HTML, CSS, and JavaScript. It fetches real-time weather data using the OpenWeather API and displays the temperature, weather conditions, and location details.

## 🎨 Demo Preview (HTML & CSS)
Here is a simple **HTML & CSS** snippet from the project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="weather-container">
        <h1>🌤️ Weather App</h1>
        <input type="text" id="cityInput" placeholder="Enter city name">
        <button id="getWeatherBtn">Get Weather</button>
        <div id="weatherResult"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
