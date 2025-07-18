# 🌦️ Live Weather Report Dashboard

An interactive **Power BI dashboard** that fetches **real-time and 7-day forecast** weather data from **WeatherAPI** for multiple Indian cities including air quality, temperature, humidity, UV index, and more.

---

## 👨‍💻 Developer

**Aaryan M**  
🔗 GitHub: [Aaryan1901](https://github.com/Aaryan1901)  
📁 Project Repo: [Live_Weather_Report_Dashboard](https://github.com/Aaryan1901/Live_Weather_Report_Dashboard)

---

## 📌 Features

- 🌍 Real-time weather updates for Indian cities  
- 📅 7-day forecast with hourly data  
- 🌫️ AQI and UV index visualizations  
- 📊 Interactive cards and charts for:
  - Temperature  
  - Humidity  
  - Wind speed  
  - AQI & UV index  
- 🗺️ City-wise mapping and filtering  
- 🔄 Manual and automatic data refresh capability

---

## ⚙️ How It Works

### 🔗 Data Source
Uses **WeatherAPI**:
https://api.weatherapi.com/v1/forecast.json?q={city}&days=7&aqi=yes&alerts=no


### 🔄 Power BI Query Flow
Each city has a Power Query:
1. API call to WeatherAPI  
2. JSON expansion of location, forecast, and air_quality  
3. Type conversion and transformation  
4. Merged into a `MasterTable` for dashboard visuals

---

## 🧪 Tech Stack

| Component       | Tool / API             |
|----------------|------------------------|
| Visualization  | Power BI               |
| Data Source    | WeatherAPI             |
| Data Format    | JSON                   |
| Data Modeling  | Power Query (M Language) |
| Design         | Custom icons & background images |

---

## 🏁 Getting Started

1. 📥 **Clone the repository**
   ```bash
   git clone https://github.com/Aaryan1901/Live_Weather_Report_Dashboard.git

### 🔄 Power BI Query Flow
Each city has a Power Query:
1. API call to WeatherAPI  
2. JSON expansion of location, forecast, and air_quality  
3. Type conversion and transformation  
4. Merged into a `MasterTable` for dashboard visuals

---

## 🧪 Tech Stack

| Component       | Tool / API             |
|----------------|------------------------|
| Visualization  | Power BI               |
| Data Source    | WeatherAPI             |
| Data Format    | JSON                   |
| Data Modeling  | Power Query (M Language) |
| Design         | Custom icons & background images |

---

## 🏁 Getting Started

📥 **Clone the repository**

   git clone https://github.com/Aaryan1901/Live_Weather_Report_Dashboard.git
🔑 Get a WeatherAPI Key

Sign up at weatherapi.com

Copy your API key

🖥️ Open the PBIX file

Open Weather_Report_Dashboard.pbix using Power BI Desktop

Replace the API key in Manage Parameters

🔄 Refresh the data

Click Refresh to fetch live data

Or schedule refresh using Power BI Service (Pro required)
🌆 Supported Cities
Pondicherry

Chennai

Bengaluru

Thiruvananthapuram

Mumbai

Madurai

(Add more by duplicating a query and changing the city parameter)

📈 Future Improvements
⏰ Add alert and warning info

📱 Mobile optimization in Power BI Service

🔀 Dynamic location filter for users

📊 Historical trend visualizations

📜 License
This project is for educational and demo purposes. Feel free to fork, modify, and use with proper attribution.

🙏 Acknowledgements
WeatherAPI – for free weather and AQI API

Microsoft Power BI Team

⭐ If you found this helpful, feel free to star the repo and share feedback!

Let me know if you want a minimal version or include badges like `![License]`, `![Power BI]`, etc.


