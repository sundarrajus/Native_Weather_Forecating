# Native Weather Forecasting App using HTML, CSS and JavaScript

![HTML](https://img.shields.io/badge/HTML-5-orange?style=flat&logo=html5)
![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat&logo=javascript)
![API](https://img.shields.io/badge/API-OpenWeatherMap-lightblue?style=flat&logo=cloud)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)

---

## Overview

A fully functional **Native Weather Forecasting App** built using **HTML, CSS, and JavaScript** — a browser-based platform that allows users to search any city and instantly view real-time weather conditions through a visually rich and responsive interface.

This project demonstrates front-end web development skills including third-party REST API integration, dynamic DOM manipulation, event handling, and responsive UI design with custom background imagery — all without any frameworks or libraries.

---

## Features

### City Weather Search
- Search weather by entering any **city name**
- Instant results on button click — no page reload
- Handles invalid city names with error feedback

### Real-Time Weather Data
- **Current temperature** in Celsius
- **Weather condition** — Clear, Cloudy, Rainy, etc.
- **Humidity** percentage
- **Wind speed** details
- **Weather description** from live API data

### Visual Design
- Beautiful **custom background images** for an immersive feel
- Clean and minimal card-based UI layout
- Custom **submit/search button** icon

### Responsive Interface
- Works smoothly on **desktop and mobile** browsers
- Fluid layout adapts to different screen sizes

---

## Technologies Used

| Category | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 |
| Logic & API Calls | JavaScript (ES6) |
| Weather Data | OpenWeatherMap API |
| Assets | Custom JPG background images |
| Version Control | Git, GitHub |

---

## Project Structure

```
Native_Weather_Forecating/
│
├── index.html                                      # Main HTML structure and layout
├── index.css                                       # Styling, backgrounds, responsive design
├── index.js                                        # JavaScript logic and API integration
│
├── background.jpg                                  # Background image assets
├── backimage.jpg
├── newbak.jpg
├── yoback.jpg
├── cristofer-maximilian-uQDRDqpYJHI-unsplash.jpg
├── graham-holtshausen-63JKK67yGUE-unsplash.jpg
│
├── submit.png                                      # Search/submit button icon
└── README.md
```

---

## Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Edge, Safari)
- A free API key from [OpenWeatherMap](https://openweathermap.org/api)
- Git (optional, for cloning)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/sundarrajus/Native_Weather_Forecating.git
cd Native_Weather_Forecating
```

2. **Get your free API key**
```
Visit   : https://openweathermap.org/api
Sign up : Create a free account
Copy    : Your unique API key from the dashboard
```

3. **Add your API key in index.js**
```js
const API_KEY = "YOUR_API_KEY_HERE";
```

4. **Open the app in your browser**
```
Simply open index.html in any modern browser
— or double-click index.html from your file explorer
```

---

## Sample Workflow

```
User opens the app
      ↓
Sees a clean search interface with a background image
      ↓
Types a city name (e.g., "Chennai") and clicks Submit
      ↓
JavaScript sends a request to OpenWeatherMap API
      ↓
API returns real-time weather data (JSON)
      ↓
DOM updates dynamically — shows temperature, condition, humidity, wind
      ↓
User searches another city — results update instantly
```

---

## Screenshots

> Add screenshots of your app here
> Example: `![App Screenshot](./background.jpg)`

---

## Key Concepts Demonstrated

| Concept | Implementation |
|---|---|
| API Integration | Fetch API with OpenWeatherMap REST endpoint |
| Async JavaScript | fetch() with .then() / async-await for API calls |
| DOM Manipulation | Dynamic rendering of weather data without page reload |
| Event Handling | Button click and keyboard event listeners |
| Responsive Design | CSS Flexbox and media queries for mobile support |
| UI/UX Design | Custom backgrounds and card layout for visual appeal |
| Error Handling | Feedback for invalid city names or failed API calls |

---

## Future Enhancements

- 5-day / 7-day extended weather forecast view
- Auto-detect user location using the Geolocation API
- Animated weather icons for different conditions
- Toggle between Celsius and Fahrenheit
- Search history / recently searched cities
- Deploy live on GitHub Pages

---

## Author

**Shavala Sundar Raju**
- GitHub: [@sundarrajus](https://github.com/sundarrajus)
- Email: shavalasundarraju@gmail.com
- LinkedIn: [Shavala Sundar Raju](https://linkedin.com/in/shavala-sundar-raju)

---

## License

This project is licensed under the **MIT License** — feel free to use and modify it.

---

> "Built to deliver real-time weather at your fingertips — fast, clean, and framework-free."
