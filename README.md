#Application 2 : Real-Time Data Processing System for Weather Monitoring with Rollups and Aggregates

Key Features

1.Real-Time Data: Fetch weather data for six Indian metros (Delhi, Mumbai, Chennai, Bangalore, Kolkata, Hyderabad) every 5 minutes.
2.Weather Parameters: Temperature, feels-like, humidity, wind speed, pressure.
3.Daily Aggregates: Average, max, min temperatures, dominant weather condition.
4.Alerts: User-defined temperature thresholds with real-time alerts.
5.SQLite Database: Store historical weather data.
6.Visualizations: Colorful real-time graphs for temperature, humidity, wind speed, etc.

Build Instructions
  Install dependencies:
      pip install requests plotly pandas
  Add your OpenWeatherMap API key in main.py:
      API_KEY = 'your_api_key'
  Run the app:
      python main.py

Design Choices
      SQLite for lightweight data storage.
      Plotly for interactive visualizations.
      Threshold Alerts based on user preferences.
      
Test Cases
      Validate API connection, temperature conversion, daily summaries, and alerting system.
