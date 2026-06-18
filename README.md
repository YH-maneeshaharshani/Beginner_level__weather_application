
 # 🌦️ Weather App

A simple React-based Weather Application that allows users to search for any city and view real-time weather information using the OpenWeatherMap API.

## 🚀 Features

* Search weather by city name
* Display temperature, humidity, wind speed, and weather conditions
* Responsive and user-friendly interface
* Error handling for invalid city names
* Handles API failures gracefully
* Environment variable support for API key security

---

## 📂 Project Structure

```plaintext
src
└── components
    ├── Weather.jsx
    └── Weather.css
```

---

## 🛠️ Technologies Used

* React.js
* CSS3
* OpenWeatherMap API
* Vite

---

## ⚡ VS Code Shortcut: `rafce`

`rafce` is a popular VS Code snippet provided by the **ES7+ React/Redux/React-Native Snippets** extension.

It automatically generates a React Functional Component with:

* Arrow Function Syntax
* Default Export
* Clean Component Structure

Example:

```jsx
import React from 'react'

const Weather = () => {
  return (
    <div>Weather</div>
  )
}

export default Weather
```

---

## 🔗 Setting Up the OpenWeatherMap API

### Step 1: Create an OpenWeatherMap Account

Visit:

https://openweathermap.org/api

### Step 2: Subscribe to Current Weather Data

1. Scroll down to **Current Weather Data**
2. Click **Subscribe**
3. Complete the registration process

### Step 3: Generate an API Key

1. Navigate to the API Keys section
2. Copy your generated API Key

---

## 🔐 Configure Environment Variables

Create a `.env` file in the root directory of your project.

```env
VITE_API_ID="YOUR_API_KEY"
```

> ⚠️ The `VITE_` prefix is mandatory when using environment variables in Vite projects.

---

## 🌍 Getting Weather Data by City Name

1. Visit OpenWeatherMap
2. Click **API**
3. Open **API Docs**
4. Navigate to:

```plaintext
Product Concepts
    └── Other Features
            └── Built-in Geocoding
```

Use the City Name API endpoint to fetch weather information based on user input.

Example:

```plaintext
https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
```

---

## 🔍 Search Functionality

Users can:

* Enter a city name
* Click the search button or press Enter
* Retrieve real-time weather data instantly

---

## ⚠️ Error Handling

The application handles the following scenarios:

### Invalid City Name

```text
City not found. Please enter a valid city name.
```

### Empty Search Input

```text
Please enter a city name.
```

### API Failure

```text
Unable to fetch weather data. Please try again later.
```

### Network Issues

```text
Check your internet connection and try again.
```

---

## ▶️ Run the Project

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

---

## 📸 Future Improvements

* 5-Day Weather Forecast
* Dark/Light Theme Toggle
* Current Location Weather
* Weather Icons Based on Conditions
* Search History

---

## 👨‍💻 Author

Developed using React and OpenWeatherMap API.

---
  <img width="1428" height="916" alt="image" src="https://github.com/user-attachments/assets/8a39ae92-a207-4dc6-9804-d3c3fb40212b" />

