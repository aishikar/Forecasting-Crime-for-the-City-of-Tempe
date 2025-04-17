# 📍 Crime Forecasting in Tempe, AZ  
**CSE 572 - Data Mining Final Project | Arizona State University**
This project explores the use of predictive modeling and spatial-temporal data analysis to forecast crime patterns in Tempe, Arizona. Using historical service call data, we developed machine learning models to identify high-risk areas and visualize potential crime hotspots. The goal is to assist law enforcement in making proactive, data-driven decisions for public safety and resource allocation.

## Objectives
- Forecast crime counts based on past service call data
- Incorporate both temporal and spatial features
- Visualize predicted crime hotspots using heatmaps
- Compare multiple machine learning models

## Dataset
- Used public service call data from the City of Tempe, Arizona
- Included timestamps, locations, and crime categories for non-emergency incidents
- Converted raw data into spatial grids to represent area-wise crime density
- Extracted time-based features like day, month, weekday, and lag values for modeling

## Methods
- Aggregated crime service call data across a 3-year span
- Created 7x7 spatial grids based on city coordinates
- Engineered features like date, time, and weekday
- Generated interactive maps and animations
- Evaluated model performance using MSE, MAE, RMSE, and R²

## Visualizations Used
- Generated choropleth maps to show predicted crime intensity
- Created spatial maps using grid centroids for each day
- Produced a heatmap animation to visualize hotspot changes over time

## Tools & Libraries Used
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn, XGBoost, Keras, TensorFlow  
- Folium, Selenium, Shapely 
- Geopandas, Plotly  
- Imageio

👩‍💻 Team Members: Aishika Rathnala, Teja Naidu Koppineni, Sai Harshith Reddy Muthani, Satya Pranay Manas Nunna, Sai Neeraj Bobba
