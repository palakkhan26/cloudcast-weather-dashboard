# ☁️ CloudCast — Cloud-Based Weather Dashboard

A responsive, cloud-hosted weather monitoring and forecasting web application that displays live weather information, a five-day forecast, temperature visualizations, and a sample weather dataset.

## 🌐 Live Demo

**Live Website:** [Open CloudCast](https://palakkhan26.github.io/cloudcast-weather-dashboard/)

**GitHub Repository:** [CloudCast Weather Dashboard](https://github.com/palakkhan26/cloudcast-weather-dashboard)

## 📌 Project Overview

CloudCast is a Cloud Computing mini project designed to demonstrate how web technologies, external APIs, data visualization, and cloud hosting can be combined to create an interactive weather dashboard.

Users can search for a city and view its current weather conditions, humidity, wind speed, apparent temperature, and upcoming five-day forecast.

The application is hosted using GitHub Pages, making it accessible through a public URL without requiring users to install any software.

## ✨ Features

- 🌍 **City Search:** Search for weather information by city name.
- 🌡️ **Current Weather:** Display temperature and weather conditions.
- 💧 **Humidity Monitoring:** View the current relative humidity.
- 💨 **Wind Speed:** Display wind speed in km/h.
- 📅 **Five-Day Forecast:** View forecasted weather conditions and daily minimum and maximum temperatures.
- 📈 **Temperature Visualization:** Compare maximum and minimum forecast temperatures using a line chart.
- 🗂️ **Weather Dataset:** Display illustrative sample weather records for multiple cities.
- 🌙 **Dark Navy Blue Theme:** A clean, dark interface with Times New Roman typography.
- 📱 **Responsive Design:** Adapt the layout to desktop and mobile screens.
- ☁️ **Cloud Deployment:** Access the application online through GitHub Pages.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the web application |
| CSS3 | Styling, layout, and responsive design |
| JavaScript | Application logic and API integration |
| Open-Meteo API | Live weather data and forecast |
| Chart.js | Temperature chart visualization |
| Git | Version control |
| GitHub | Source code repository |
| GitHub Pages | Cloud hosting and deployment |

## 🏗️ System Architecture

```text
             User
              |
              v
      CloudCast Web App
       HTML, CSS, JS
              |
       +------+------+
       |             |
       v             v
 Open-Meteo API   Sample Dataset
       |             |
       v             v
 Current Weather  Dataset Table
 and Forecast
       |
       v
 Temperature Chart

       GitHub Repository
              |
              v
        GitHub Pages
              |
              v
       Public Website
```

## 📊 Dataset Description

The project contains a small, illustrative sample dataset with weather records for Pune, Mumbai, and Delhi.

The dataset includes the following fields:

| Field | Description |
|---|---|
| City | Name of the city |
| Date | Date associated with the sample record |
| Temperature | Sample temperature in °C |
| Humidity | Sample relative humidity in % |
| Wind Speed | Sample wind speed in km/h |
| Condition | Sample weather description |

**Note:** These embedded sample records are for demonstration purposes and are not verified historical observations. Current weather and forecast information are fetched separately from the Open-Meteo API.

## ⚙️ How It Works

1. The user enters a city name in the search field.
2. The application uses the Open-Meteo Geocoding API to find the city's coordinates.
3. The coordinates are sent to the Open-Meteo Forecast API.
4. JavaScript processes the returned weather information.
5. The dashboard displays current conditions and the five-day forecast.
6. Chart.js visualizes forecast maximum and minimum temperatures.
7. The sample dataset is displayed in a separate table.
8. GitHub Pages hosts the website and makes it publicly accessible.

## 🚀 Run the Project Locally

### Prerequisites

- A modern web browser
- A code editor such as Visual Studio Code
- An internet connection

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/palakkhan26/cloudcast-weather-dashboard.git
   ```

2. Navigate to the project directory:

   ```bash
   cd cloudcast-weather-dashboard
   ```

3. Open the folder in Visual Studio Code.

4. Run `index.html` using the VS Code Live Server extension, or serve the folder using another local HTTP server.

5. Open the local URL in your browser.

An internet connection is required for the external weather API and Chart.js CDN.

## ☁️ Cloud Deployment

CloudCast is deployed using **GitHub Pages**.

### Deployment Steps

1. Push the project files to the GitHub repository.
2. Open the repository's **Settings**.
3. Select **Pages** under Code and automation.
4. Choose **Deploy from a branch**.
5. Select the `main` branch and the `/(root)` folder.
6. Save the configuration.
7. Open the generated GitHub Pages URL after deployment completes.

### Updating the Website

After making changes to the project, run:

```bash
git add .
git commit -m "Update CloudCast dashboard"
git push
```

GitHub Pages will publish the updated files after the deployment process completes.

## 🎯 Objectives

- To understand the fundamentals of cloud computing and cloud hosting.
- To integrate a third-party weather API into a web application.
- To retrieve and display weather information dynamically.
- To visualize forecast data using charts.
- To demonstrate version control and deployment using Git and GitHub.
- To develop a responsive and user-friendly web interface.

## 🔮 Future Enhancements

- Connect a cloud database to store weather search history.
- Add interactive historical weather charts using a verified dataset.
- Add automatic location detection with user permission.
- Provide severe-weather notifications.
- Add unit conversion between Celsius and Fahrenheit.
- Add weather comparisons between multiple cities.
- Integrate additional meteorological data sources.

## ⚠️ Limitations

- Live weather information depends on the availability of the external API and internet connectivity.
- The included sample dataset is illustrative rather than a verified historical dataset.
- The current version does not use a dedicated cloud database or backend server.
- Forecast availability and accuracy depend on the external data provider.

## 👩‍💻 Project Information

**Project Name:** CloudCast — Cloud-Based Weather Dashboard  
**Project Type:** Cloud Computing Mini Project  
**Frontend:** HTML, CSS, JavaScript  
**Weather Provider:** Open-Meteo  
**Visualization Library:** Chart.js  
**Hosting Platform:** GitHub Pages  
**Version Control:** Git and GitHub

---

Made with ☁️ and 💙 as a Cloud Computing mini project.
