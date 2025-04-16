# 📍 Crime Forecasting in Tempe, AZ  
**CSE 572 - Data Mining Final Project | Arizona State University**
This project explores the use of predictive modeling and spatial-temporal data analysis to forecast crime patterns in Tempe, Arizona. Using historical service call data, we developed machine learning models to identify high-risk areas and visualize potential crime hotspots. The goal is to assist law enforcement in making proactive, data-driven decisions for public safety and resource allocation.

## Objectives
- Forecast crime counts based on past service call data
- Incorporate both **temporal** and **spatial** features
- Visualize predicted crime hotspots using heatmaps
- Compare multiple machine learning models

## Dataset
- This project uses publicly available crime-related service call data provided by the City of Tempe, Arizona.
- The dataset contains records of non-emergency service calls, including timestamps, location coordinates, and crime categories.
- Data was preprocessed into spatial grids to capture area-level crime density.
- Time-based features such as day, month, weekday, and historical lag values were used to model temporal patterns.

## Methods
- Aggregated crime service call data across a 3-year span
- Created 7x7 spatial grids based on city coordinates
- Engineered features like date, time, and weekday
- Generated interactive maps and animations
- Evaluated model performance using MSE, MAE, RMSE, and R²

## Tools & Libraries Used
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn, XGBoost, Keras, TensorFlow  
- Folium, Selenium, Shapely 
- Geopandas, Plotly  
- Imageio

## 👩‍💻 Team Members: Aishika Rathnala, Teja Naidu Koppineni, Sai Harshith Reddy Muthani, Satya Pranay Manas Nunna, Sai Neeraj Bobba
