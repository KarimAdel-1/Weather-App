# 🌤️ Weather-App

Weather App is a simple weather forecast application built using **React**. It fetches weather information based on user input and displays current weather conditions for a specified location using data from the Open-Meteo API.

## 🚀 Features

- **Dynamic Weather Search**: Users can input a location to get current weather data.
- **Geocoding Integration**: Utilizes Open-Meteo's geocoding API to search for the latitude and longitude of the location entered.
- **Weather Forecast**: Displays weather icons and temperature ranges (min & max) for the next few days.
- **Location Persistence**: The application remembers the last searched location, even after refreshing the page (localStorage).
- **Weather Icons**: Uses weather codes to display appropriate icons for different weather conditions (sunny, cloudy, rain, etc.).
  
## 🛠️ Tech Stack

- **React**: For building the UI and handling state.
- **Open-Meteo API**: For fetching geolocation and weather data.
- **JavaScript**: Core logic for handling API requests and responses.

## 📦 Installation

### Prerequisites

- Node.js and npm/yarn installed on your machine.

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KarimAdel-1/Weather-App.git
   cd Weather-App
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

3. **Run the app locally**:
   ```bash
   npm start
   ```
   or
   ```bash
   yarn start
   ```

4. Open your browser and navigate to `http://localhost:3000`.

## 🌍 API

This app uses the [Open-Meteo API](https://open-meteo.com/) to:

- Geocode user-entered locations.
- Fetch weather data (e.g., temperature, weather codes) for the specified location.

## ⚙️ How It Works

1. **User Inputs Location**: The user enters a city or location into the search box.
2. **Geocoding Request**: The app sends a request to the Open-Meteo Geocoding API to get the latitude and longitude for the input location.
3. **Weather Data Fetching**: The app fetches weather data based on the latitude and longitude.
4. **Weather Display**: Weather details, including icons for weather conditions and temperature ranges, are displayed for the location.

## 📂 Project Structure

```bash
src/
│
├── App.js           # Main component handling state and rendering weather
├── Input.js         # Input component for location search
├── Weather.js       # Component for displaying weather data
├── Day.js           # Displays daily weather information
└── index.js         # Entry point for React
```

## 🌟 Future Enhancements

- Add hourly weather forecasts.
- Implement error handling with user-friendly messages.
- Enhance UI with more detailed weather data (humidity, wind speed, etc.).

## 💬 Feedback

If you have any feedback or suggestions, feel free to open an issue or submit a pull request!
