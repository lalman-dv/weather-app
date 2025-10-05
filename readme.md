# 🌦️ Weather App

A sleek, responsive weather application built with HTML, CSS, and JavaScript. Users can search for any city and instantly view real-time weather data including temperature, humidity, wind speed, and a matching weather icon.

## 🔧 Features

- 🔍 City-based weather search
- 🌡️ Live temperature in Celsius
- 💧 Humidity and 🌬️ wind speed display
- 🖼️ Dynamic weather icons (Clear, Clouds, Rain, etc.)
- ⚠️ Error handling for invalid city names
- 🎨 Gradient UI with responsive layout

## 📦 Tech Stack

- **HTML5** – Semantic structure
- **CSS3** – Gradient backgrounds, responsive card layout
- **JavaScript (ES6+)** – API integration, DOM manipulation
- **OpenWeatherMap API** – Real-time weather data

## 🚀 How to Run

1. Clone the repository:
2. Replace the API key in `script.js`:

```js
const apikey = "YOUR_API_KEY";
3.  Open index.html in your browser.

📁 Folder Structure
weather-app/
├── index.html
├── style.css
├── script.js
└── images/
    ├── search.png
    ├── clouds.png
    ├── clear.png
    ├── rain.png
    ├── drizzle.png
    ├── mist.png
    ├── snow.png
    ├── humidity.png
    └── wind.png
    🧠 Developer Notes

•  Input is trimmed to prevent blank searches.
•  Weather icons are mapped dynamically using data.weather[0].main.
•  .weather and .error sections toggle based on API response.
•  Future enhancements may include:
  ⁠◦  🌍 5-day forecast
  ⁠◦  🌗 Dark/light mode toggle
  ⁠◦  🌡️ Celsius ↔ Fahrenheit switch
  ⁠◦  📍 Geolocation-based weather

📸 Preview<img width="763" height="746" alt="Screenshot 2025-10-05 at 12 14 56 PM" src="https://github.com/user-attachments/assets/52ebd8c1-aa22-4a34-80bd-09dad173a263" />

```
