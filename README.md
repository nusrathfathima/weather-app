# 🌤️ Weather App

A real-time weather application that fetches live weather data for any city in the world.

🔗 **[Live Demo](https://nusrathfathima.github.io/weather-app)** | 🌐 **[Portfolio](https://nusrathfathima.com)**

---

## Features

- 🌐 Real-time weather data via Open-Meteo API (no API key required)
- 🔍 Search any city in the world by name
- 🌡️ Shows temperature, humidity, wind speed, and feels like
- ⚠️ Graceful error handling for unknown cities
- 📱 Fully responsive — works on mobile, tablet, and desktop

## Tech Stack

- HTML5
- CSS3 (Flexbox, CSS Grid, Custom Properties)
- JavaScript (ES6+, async/await, fetch API)
- [Open-Meteo API](https://open-meteo.com/) — free weather API
- [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api) — city search

## How It Works

1. User types a city name and hits Search
2. App calls the Open-Meteo Geocoding API to get the city's coordinates
3. Coordinates are passed to the Open-Meteo Forecast API to get live weather
4. Weather data is displayed with icon, temperature, and stats

## Getting Started

No installation needed! Just open `index.html` in your browser or visit the live demo.

```bash
git clone https://github.com/nusrathfathima/weather-app.git
cd weather-app
open index.html
```

## Screenshot

> Live demo: https://nusrathfathima.github.io/weather-app

---

Built by [Nusrath Fathima](https://nusrathfathima.com)
