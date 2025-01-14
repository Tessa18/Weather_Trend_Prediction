# Weather_Trend_Prediction
## Overview
This project focuses on analyzing and forecasting global weather trends using advanced data science techniques. By leveraging machine learning models, time-series forecasting, and geospatial analysis, it uncovers critical insights into weather patterns, correlations, and anomalies. The findings aim to support decision-making in climate studies, policy planning, and environmental sustainability.

## 🛠️ Features

**Data Cleaning**: Handled missing values and outliers. Normalized features for effective model training.

**Exploratory Data Analysis (EDA)**: Uncovered trends, seasonality, and correlations in weather metrics.

**Visualizations**: histograms, heatmaps, and boxplots.

**Forecasting Models**: Linear Regression, ARIMA, and LSTM implemented for temperature forecasting. Ensemble approach combining ARIMA and LSTM outputs.

**Advanced Analyses**:Anomaly detection using Z-Score and Isolation Forest. Geospatial mapping of weather patterns using GeoPandas.

**Insights and Recommendations**: Actionable insights on seasonal trends and correlations for policy-making.


## 📂 Dataset
**Source**: Manually downloaded Natural Earth dataset and global weather data repository. 

**Link**: https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/code

**Size**: 46,382 rows, 41 columns.

**Key Features**: Temperature, humidity, air quality (PM2.5), wind speed, and timestamps.

## 🧰 Technologies Used
**Languages**: Python

### Libraries:
**Data Analysis**: pandas, numpy

**Visualization**: matplotlib, seaborn, plotly

**Machine Learning**: scikit-learn, tensorflow

**Time-Series Analysis**: statsmodels, ARIMA

**Geospatial Analysis**: geopandas

**Platforms**: Jupyter Notebook for interactive analysis. GitHub for version control and project sharing.


## 🚀 Models and Performance

### Model	Objective	Metrics

- Linear Regression	Predict temperature using temporal features.	MAE: 0.16, R²: 0.13

- ARIMA	Forecast daily temperatures (30 days).	MAE: 0.21

- LSTM	Time-series forecasting using sequential data.	MAE: 0.12

- Ensemble	Weighted average of ARIMA and LSTM outputs.	MAE: 0.22

## 🔎 Key Insights
**Weather Trends**: Significant seasonal variation in temperature.
Strong correlation between air quality (PM2.5) and temperature.

**Anomaly Detection**:
Identified extreme weather events using Z-Score and Isolation Forest.

**Geospatial Mapping**:
Mapped temperature and humidity variations across continents and countries.

## 📈 Visualizations
- Histograms to explore distributions.
- Correlation heatmaps for relationships between features.
- Geospatial maps for country-level weather patterns.
- Time-series plots comparing historical vs. forecasted trends.
## 📝 Future Work
- Incorporate additional weather features, such as solar radiation and precipitation.
- Explore hybrid models for better forecasting accuracy.
- Extend geospatial analysis to support localized environmental policymaking.
## 💡 How to Run the Project
- Clone this repository: https://github.com/Tessa18/Weather_Trend_Prediction 
- Install required dependencies:
**pip install -r requirements.txt** 
- Download and place the dataset in the data/ folder.
- Run the Jupyter Notebook:
jupyter notebook **weather_trend.ipynb**

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions and improvements.

## 🙌 Acknowledgments
- Natural Earth for geospatial datasets.
- The open-source community for providing amazing tools and libraries.
