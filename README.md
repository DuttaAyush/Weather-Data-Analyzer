# 🌤️ Weather Data Analyzer

A Streamlit-based web application for analyzing and visualizing weather data with interactive charts, statistics, and insights.

## 🚀 How to Run

1. **Install dependencies:**
```bash
pip install streamlit pandas matplotlib seaborn numpy meteostat
```

2. **Run the application:**
```bash
streamlit run app.py
```

3. **Open your browser:**
The app will automatically open at `http://localhost:8501`

## 📊 Features

- Upload CSV files or fetch real weather data using **Meteostat API**
- View summary statistics and extreme weather days
- Interactive visualizations (temperature trends, monthly averages, correlations)
- Data export and seasonal analysis

## 📁 Project Structure

```
├── weather.py    # Core weather data analyzer class
├── app.py        # Streamlit web application
└── README.md     # This file
```

## 🌍 Supported Cities

Nagpur, New Delhi, Mumbai, Chennai, Bengaluru, Kolkata, Hyderabad

# 🌤️ View Demo

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://weatheranalyser.streamlit.app/)