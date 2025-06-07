# Weather Data Analysis Project

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 🌤️ Project Overview

This project provides comprehensive analysis of multi-city weather data through interactive visualizations and statistical insights. Built with Python and Streamlit, it offers a user-friendly dashboard for exploring weather patterns, trends, and correlations across different cities and time periods.

The project combines data cleaning, exploratory data analysis, and interactive visualization to deliver actionable insights about weather conditions, seasonal patterns, and climate trends.

## ✨ Features

- **Interactive Dashboard**: Real-time weather data exploration through Streamlit web interface
- **Multi-City Analysis**: Compare weather patterns across different cities
- **Comprehensive Visualizations**: 
  - Time series plots for temperature, humidity, and precipitation
  - Correlation heatmaps
  - Seasonal trend analysis
  - Statistical distribution plots
- **Data Filtering**: Filter data by date range, city, and weather parameters
- **Statistical Insights**: Summary statistics and trend analysis
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Export Capabilities**: Download filtered data and visualizations

## 🛠️ Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rudra15102004/Weather-Data-Analysis-kaggle.git
   cd Weather-Data-Analysis-kaggle
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv weather_env
   
   # On Windows
   weather_env\Scripts\activate
   
   # On macOS/Linux
   source weather_env/bin/activate
   ```

3. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit application**
   ```bash
   streamlit run app.py
   ```

5. **Open your browser** and navigate to `http://localhost:8501`

### Dependencies

The project requires the following Python packages:

```
streamlit>=1.28.0
pandas>=1.5.0
numpy>=1.24.0
matplotlib>=3.6.0
seaborn>=0.12.0
plotly>=5.15.0
scikit-learn>=1.3.0
```

## 📁 Project Structure

```
Weather-Data-Analysis-kaggle/
├── data/
│   ├── raw/                    # Original Kaggle dataset (CSV, untouched)
│   └── processed/              # Cleaned CSV used for plotting
├── notebooks/
│   ├── weather_analysis.ipynb  # EDA, charts, correlation, trends, Plotly/Dash/Altair visualizations
├── images/
│   ├── temperature_trends.png
│   ├── precipitation_analysis.png
│   ├── correlation_heatmap.png
│   └── interactive_plot.html   # Interactive HTML saved from Plotly
├── app/
│   └── WeatherAnalysis_Extended.py                  # Streamlit dashboard 
├── requirements.txt
└── README.md


## 🚀 Usage

### Running the Dashboard

1. **Start the application**:
   ```bash
   streamlit run WeatherAnalysis_Extended.py
   ```

2. **Navigate the interface**:
   - Use the sidebar to select cities and date ranges
   - Choose different visualization types from the main panel
   - Apply filters to focus on specific weather parameters
   - Download results using the export buttons

### Outputs of Dashboards and plot and graphs 
## 📊 Dashboard Screenshot

![Dashboard Preview](C:\Users\RUDRA\OneDrive\Pictures\Screenshots\Screenshot 2025-06-07 141233.png" "Streamlit Dashboard)

## 📊 Interactive Graphs and plots 

![image](C:\Users\RUDRA\OneDrive\Documents\GitHub\weather-data-analysis\images\Temperature Overtime (inter active).png)




### Key Features Guide

- **Data Overview**: View summary statistics and data quality metrics
- **Time Series Analysis**: Explore weather trends over time
- **Comparative Analysis**: Compare weather patterns between cities
- **Correlation Analysis**: Discover relationships between weather variables
- **Seasonal Patterns**: Analyze seasonal weather variations

### Jupyter Notebooks

For detailed analysis and methodology:
WeatherAnalysis_Extended.ipynb

## 📊 Data Sources

The project uses weather data from multiple sources:
- Historical weather records from major cities
- Meteorological station data
- Climate databases

*Note: Ensure you have the proper permissions and licenses for any external data sources.*

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Rudra** - [GitHub Profile](https://github.com/Rudra15102004)

## 🙏 Acknowledgments

- Weather data providers and meteorological organizations
- Open-source Python community
- Streamlit team for the amazing framework

---

**⭐ If you find this project helpful, please consider giving it a star!**