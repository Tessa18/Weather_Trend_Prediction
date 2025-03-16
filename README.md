# Weather_Trend_Prediction
## Overview
This project focuses on analyzing and forecasting global weather trends using advanced data science techniques. By leveraging machine learning models, time-series forecasting, geospatial analysis, and distributed computing with Apache Spark and SQL, it uncovers critical insights into weather patterns, correlations, and anomalies. The findings aim to support decision-making in climate studies, policy planning, and environmental sustainability.

## 🛠️ Features

**Data Cleaning**: Handled missing values and outliers. Normalized features for effective model training.

**Exploratory Data Analysis (EDA)**: Uncovered trends, seasonality, and correlations in weather metrics.

**Visualizations**: Histograms, heatmaps, and boxplots for a detailed look at weather data.

**Spark and SQL**: Used Apache Spark for large-scale data processing and SQL for efficient querying and aggregation of weather data.

**Forecasting Models**: Linear Regression, ARIMA, and LSTM implemented for temperature forecasting. Ensemble approach combining ARIMA and LSTM outputs.

**Advanced Analyses**:Anomaly detection using Z-Score and Isolation Forest. Geospatial mapping of weather patterns using GeoPandas.

**Real-time Data Processing**: Integrated real-time weather data processing using Spark Streaming (planned future work).

**SQL Aggregation**: Applied SQL queries to aggregate and manipulate weather data for better insights.


## 📂 Dataset
**Source**: Manually downloaded Natural Earth dataset and global weather data repository. 

**Link**: https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/code

**Size**: 46,382 rows, 41 columns.

**Key Features**: Temperature, humidity, air quality (PM2.5), wind speed, and timestamps.

## 🧰 Technologies Used
**Languages**: Python

### Libraries:
-  **Data Analysis**: pandas, numpy

-  **Visualization**: matplotlib, seaborn, plotly

-  **Machine Learning**: scikit-learn, tensorflow

-  **Time-Series Analysis**: statsmodels, ARIMA

-  **Geospatial Analysis**: geopandas

-  **Distributed Computing**: Apache Spark

-  **SQL**: PySpark SQL for querying weather data

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
- SQL-driven visualizations using Spark SQL queries.
## 📝 Future Work
-  **Real-Time Data Processing**: Implement a live Spark Streaming pipeline to process weather data in real-time and make predictions.
-  **Additional Weather Features**: Incorporate features like solar radiation and precipitation for better model accuracy.
-  **Hybrid Models**: Explore hybrid models combining ARIMA, LSTM, and other machine learning techniques to improve forecasting accuracy.
-  **Localized Environmental Policy Support**: Extend geospatial analysis to support localized environmental policymaking.
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
