## 🌦️ Weather Dashboard Web App

📽️ **Demo Video of Application:**  
<div align="center">
  <img src="./demo.gif" alt="Weather Forecast Banner" height="300" width="500" />
</div>
---

## 🌟 About Weather Dashboard
Ever wanted instant weather updates for any city? Our **Weather Dashboard** does just that! ☁️🌍

_"Your go-to app for real-time weather tracking!"_ - Happy User 🌟

---

## ✨ Magic Features
✅ **Live Weather Updates** – Search for any city and get instant results.  
✅ **Detailed Weather Info** – Get insights into:
   - 🌍 City Name
   - 🌡️ Temperature (°C)
   - ⛅ Weather Condition (Sunny, Rainy, etc.)
   - 💧 Humidity (%)
   - 🌬️ Wind Speed (km/h)
   - 🖼️ Weather Icon  
✅ **Search-on-Enter Functionality** – Faster and easier searches.  
✅ **Loading Animation** – Shows a spinner while fetching data.  
✅ **Error Handling** – Displays friendly messages for invalid city names or API failures.  
✅ **Recent Search History** – Saves and shows the last 5 searched cities.  
✅ **5-Day Weather Forecast** – View weather trends for upcoming days.  
✅ **Dark/Light Theme Toggle** – Choose your preferred mode.  
✅ **Refresh Button** – Instantly update the weather for the current city.  
✅ **Smooth Animations** – Using Framer Motion / CSS for an interactive experience.  

---

## 🚀 Quick Start

### 📦 Prerequisites
Before running the project, ensure you have:
```sh
node -v  # Should be v16+
npm -v   # Latest is best!
```

### 🎮 Installation
🔹 Clone the project
```sh
git clone https://github.com/ShakshiKumariAgrawal/Weather-Sense.git
cd weather-dashboard
```

🔹 Install dependencies
```sh
npm install  # Let the magic begin!
```

🔹 Configure API Key
1. Get a free API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up)
2. Create a `.env` file in the root folder and add:
   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

🔹 Launch the app
```sh
npm start  # Opens the app on http://localhost:3000/
```

---

## 🌐 API Integration
This project fetches weather data from the **OpenWeatherMap API**.

### 🔗 API Endpoint
```sh
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
```

## 🛠️ Tech Magic Stack
🚀 **React.js** – The power behind the UI  
🎨 **Tailwind CSS / MUI** – For a sleek and responsive design  
⚡ **Axios / Fetch API** – Making real-time API requests  
💾 **Local Storage** – Saving search history  
🎭 **Framer Motion** – Adding smooth animations  

---

## 🚀 Deployment


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
- Sometimes, city names with special characters may not be recognized.
- API rate limits may restrict the number of searches per hour.

### 🚀 Future Enhancements
- 📍 **Geolocation Support** – Automatically fetch weather based on user location.
- 📅 **Hourly Forecast** – Add detailed hourly breakdown.
- 📊 **Charts & Graphs** – Display temperature trends using visual graphs.
- 🔔 **Weather Alerts** – Notify users of extreme weather conditions.

---

## 🤝 Join the Magic
Want to contribute? Amazing! Here’s how:

🍴 **Fork it**  
🌟 **Create a feature branch** (`git checkout -b feature/AmazingFeature`)  
💫 **Commit your changes** (`git commit -m '✨ Add some magic'`)  
🚀 **Push to the branch** (`git push origin feature/AmazingFeature`)  
🎉 **Open a magical Pull Request**

---

## 📜 License
This magical project is under the **MIT License** - spread the magic! ✨

---

## 📬 Stay Connected
📧 **Email:** shakshiagrawal4221@gmai.com 

✨ **Enjoy coding!** ✨

