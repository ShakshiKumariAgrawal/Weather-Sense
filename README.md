## 🌦️ Weather-Sense Web App

📽️ **Demo Video of Application:**  
<div align="center">
  <img src="./demo.gif" alt="Weather Forecast Banner" height="300" width="500" />
</div>
---

## 🌟 Overview
Ever wondered what the weather is like in any city? Our **Weather-Sense** provides real-time updates with a sleek and modern UI. ☁️🌍

## LIVE DEMO LINK : https://weather-sense11.netlify.app/

_"Your go-to app for checking live weather conditions!"_ - Happy User 🌟

---

## ✨ Features
🔹 **Live Weather Updates** – Get instant weather data for any city.  
🔹 **Detailed Weather Info:**
   - 🌍 City Name
   - 🌡️ Temperature (°C)
   - ⛅ Weather Condition (Sunny, Rainy, etc.)
   - 💧 Humidity (%)
   - 🌬️ Wind Speed (km/h)
   - 🖼️ Weather Icon from API  
🔹 **Search-on-Enter Functionality** – No need to press a button!  
🔹 **Loader Animation** – Displays a spinner while fetching data.  
🔹 **Error Handling** – User-friendly messages for invalid city names or API errors.  
🔹 **Recent Search History** – Saves and displays the last 5 searched cities.  
🔹 **5-Day Weather Forecast** – View upcoming weather trends.  
🔹 **Dark/Light Theme Toggle** – Switch between modes effortlessly.  
🔹 **Refresh Button** – Instantly update weather data for the current city.  
🔹 **Smooth Animations** – Using Framer Motion or CSS transitions.  

---

## 🚀 Quick Start Guide

### 📦 Prerequisites
Ensure you have the following installed before running the project:
```sh
node -v  # Should be v16+
npm -v   # Latest is best!
```

### 🎮 Installation
🔹 Clone the repository
```sh
git clone https://github.com/ShakshiKumariAgrawal/Weather-Sense.git
cd weather-dashboard
```

🔹 Install dependencies
```sh
npm install  # Installing all necessary packages
```

🔹 Configure API Key
1. Get a free API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up)
2. Create a `.env` file in the root folder and add:
   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

🔹 Run the app
```sh
npm start  # Opens the app on http://localhost:3000/
```

---

## 🌐 API Integration
This project fetches real-time weather data from **OpenWeatherMap API**.

### 🔗 API Endpoint
```sh
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
```

## 🛠️ Tech Stack
🚀 **React.js** – The backbone of the app  
🎨 **Tailwind CSS / MUI** – For a beautiful and responsive UI  
⚡ **Axios / Fetch API** – Making real-time API requests  
💾 **Local Storage** – Saves recent search history  
🎭 **Framer Motion** – For smooth animations  

---

## 📁 Folder Structure
```
weather-dashboard/
│── public/
│── src/
│   ├── components/  # Reusable UI components
│   ├── pages/       # Page components (Home, Forecast)
│   ├── hooks/       # Custom React Hooks
│   ├── utils/       # Utility functions
│   ├── App.js       # Main App Component
│   ├── index.js     # Entry Point
│── .env             # API Key Configuration
│── package.json
│── README.md
```

---

## 🔧 Known Issues & Future Enhancements
### 🔴 Known Issues
- Some cities with special characters may not be recognized.
- API rate limits may restrict the number of searches per hour.

### 🚀 Future Enhancements
- 📍 **Geolocation Support** – Automatically detect user location for weather updates.
- 📅 **Hourly Forecast** – Add hourly weather breakdown.
- 📊 **Charts & Graphs** – Display weather trends using visual graphs.
- 🔔 **Weather Alerts** – Notify users about severe weather conditions.

---

## 🤝 How to Contribute
Want to contribute? Awesome! Follow these steps:

🍴 **Fork it**  
🌟 **Create a feature branch** (`git checkout -b feature/AmazingFeature`)  
💫 **Commit your changes** (`git commit -m '✨ Add some magic'`)  
🚀 **Push to the branch** (`git push origin feature/AmazingFeature`)  
🎉 **Open a Pull Request**

---

## 📜 License
This project is licensed under the **MIT License** - spread the magic! ✨

---

## 📬 Connect with Me
📧 **Email:** shakshiagrawal4221@gmail.com  
🚀 **Happy Coding!** 🚀

