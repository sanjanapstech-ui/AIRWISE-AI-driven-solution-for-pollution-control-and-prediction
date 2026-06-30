# AirWise – Intelligent Air Quality Monitoring & AQI Prediction System

## Overview

AirWise is an AI-powered air quality monitoring and forecasting system that analyzes real-time pollution levels and predicts future Air Quality Index (AQI) values for multiple cities in Karnataka. The system combines live pollution data from the World Air Quality Index (WAQI) API with historical air quality datasets and machine learning models to provide accurate AQI forecasting and interactive visualization.

## Features

- Real-time air pollution monitoring using WAQI API
- CPCB-compliant AQI calculation
- Monitoring of PM2.5, PM10, NO₂, SO₂, CO and O₃ pollutants
- Interactive city-wise AQI dashboard
- Geospatial AQI visualization using maps
- Future AQI prediction using Machine Learning
- City-wise pollution trend analysis
- Feature importance analysis
- Error analysis and model comparison

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- Folium
- WAQI API
- Jupyter Notebook

## System Workflow

1. Collect real-time pollution data from WAQI API.
2. Load historical AQI datasets from multiple Karnataka cities.
3. Clean and preprocess pollutant data.
4. Calculate AQI using CPCB standards.
5. Generate lag and rolling statistical features.
6. Train machine learning models.
7. Predict future AQI values.
8. Display results through an interactive dashboard and map.

## Machine Learning Pipeline

### Data Preprocessing
- Missing value handling
- Date standardization
- AQI calculation
- Data cleaning

### Feature Engineering
- AQI Lag Features
- Rolling Mean Features
- Rolling Standard Deviation
- Seasonal Features
- City Encoding

### Models Evaluated
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- LightGBM Regressor
- CatBoost Regressor

## Dataset

The project uses:
- Historical AQI datasets from Karnataka cities
- Real-time pollution data from the WAQI API

Cities Covered:
- Bengaluru
- Mysuru
- Mangaluru
- Tumakuru
- Dharwad
- Hubballi
- Bagalkot
- Kalaburagi
- Chikkamagaluru
- Chikkaballapur
- Ramanagara
- Yadgir
- Chamarajanagar
- Davanagere
- Madikeri
- Belagavi

## Screenshots

### Real-Time AQI Dashboard
(Add Screenshot)

### Interactive Pollution Map
(Add Screenshot)

### Model Comparison
(Add Screenshot)

### Feature Importance
(Add Screenshot)

### Future AQI Prediction
(Add Screenshot)

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/AirWise.git

cd AirWise

pip install -r requirements.txt
```

## Run Project

```bash
jupyter notebook AirWise.ipynb
```

## Future Enhancements

- Deep Learning models (LSTM, GRU)
- Weather data integration
- Mobile application
- AQI alert notification system
- Expanded coverage to more cities

## Author

Sanjana
