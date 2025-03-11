# 🌬️ Air Quality Monitoring Dashboard

[![Deployment Status](https://img.shields.io/badge/deployment-live-brightgreen)](https://air-monitoring-dashboard.vercel.app/)
[![GitHub repo](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/Prathaban-G/air-Monitoring-Dashboard)

## 📊 Overview

A comprehensive real-time air quality monitoring system that collects data from IoT sensors and visualizes air quality metrics through an intuitive dashboard. The system evaluates air quality based on standard indices and provides visual indicators for monitoring environmental conditions.

![Dashboard](https://github.com/Prathaban-G/air-Monitoring-Dashboard/blob/main/Sample%20Images/air-dashboard.png))

## ✨ Features

- **Real-time Air Quality Index (AQI)** visualization with status indicators (Excellent, Good, Average, Poor)
- **Environmental Metrics Tracking**:
  - Temperature monitoring
  - Humidity levels
  - Particulate matter (PM2.5, PM10)
  - Harmful gases (CO, NO2, SO2, O3)
- **Interactive Visualizations**:
  - Gauge charts for current readings
  - Line charts for historical trends
  - Color-coded indicators for air quality status
- **Threshold Management**:
  - Customizable alert thresholds
  - Automatic alarm triggering via IoT devices when thresholds are exceeded
- **Historical Data Analysis**:
  - Track air quality trends over time
  - Compare current readings with historical averages

## 🛠️ Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Charts & Visualization**: Chart.js
- **Backend Communication**: Firebase Realtime Database
- **User Authentication**: Firebase Authentication
- **Responsive Design**: Bootstrap
- **Deployment**: Vercel

## 📸 Screenshots

### Main Dashboard
![Main Dashboard](https://github.com/Prathaban-G/air-Monitoring-Dashboard/blob/main/Sample%20Images/air-dash.png)
The primary interface showing real-time air quality metrics, gauge charts, and status indicators.

### Historical Trends
![Historical Trends](https://github.com/Prathaban-G/air-Monitoring-Dashboard/blob/main/Sample%20Images/air-history.png)
Line charts displaying air quality trends over customizable time periods.

### Threshold Configuration
![Threshold Settings](https://github.com/Prathaban-G/air-Monitoring-Dashboard/blob/main/Sample%20Images/air-threshold.png)
Interface for setting and managing alert thresholds for different pollutants.

## 🚀 Live Demo

Experience the dashboard in action: [Air Monitoring Dashboard](https://air-monitoring-dashboard.vercel.app/)

## 💻 Setup & Usage

1. **Access the Application**:
   - Visit [https://air-monitoring-dashboard.vercel.app/](https://air-monitoring-dashboard.vercel.app/)
   - Login with provided credentials or create a new account

2. **View Air Quality Data**:
   - Monitor real-time AQI readings on the main dashboard
   - Check historical trends via line charts
   - View current status (Excellent, Good, Average, Poor)

3. **Configure Thresholds**:
   - Set custom alert thresholds for different pollutants
   - Adjust sensitivity based on your requirements

## 🔄 Integration with IoT Hardware

The dashboard connects with air quality sensors via Firebase Realtime Database:
- Sensors push data to Firebase in real-time
- Dashboard pulls and displays updated readings
- Threshold checks trigger alerts when conditions are met

When air quality metrics exceed configured thresholds, the system:
1. Displays visual alerts on the dashboard
2. Sends trigger signals to connected IoT devices
3. Activates physical alarms or mitigation systems

## 🔮 Future Enhancements

- MQTT protocol implementation for more efficient IoT communication
- Mobile application for on-the-go monitoring
- Machine learning integration for predictive air quality forecasting
- Geospatial mapping to visualize air quality across different locations
- Notification system (email, SMS, push notifications) for critical alerts
- Advanced reporting capabilities with PDF export

## 👥 Contributors

- **Prathaban G** - Full-stack Developer - [GitHub](https://github.com/Prathaban-G)

## 📞 Contact

For questions, feedback, or collaboration opportunities:
- Email: prathabang1234@gmail.com
- LinkedIn: [Prathaban G](https://www.linkedin.com/in/your-profile/)

