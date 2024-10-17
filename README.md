# Real-Time Data Processing System for Weather Monitoring with Rollups and Aggregates

## Key Features
1. **Real-Time Data**: Fetch weather data for six Indian metros (Delhi, Mumbai, Chennai, Bangalore, Kolkata, Hyderabad) every 5 minutes.
2. **Weather Parameters**: Includes temperature, feels-like, humidity, wind speed, and pressure.
3. **Daily Aggregates**: Calculates daily averages, maximum, minimum temperatures, and dominant weather condition.
4. **Alerts**: Supports user-defined temperature thresholds with real-time alerts.
5. **SQLite Database**: Stores historical weather data for further analysis.
6. **Visualizations**: Provides colorful real-time graphs for temperature, humidity, wind speed, etc.

## Build Instructions

1. **Install Dependencies**:
   ```bash
   pip install requests plotly pandas
