An AI-powered tourism analytics system that predicts visitor trends, detects rush levels, and recommends nearby underrated places using Machine Learning, Time Series Forecasting, and Geospatial Analysis.

---

## 🚀 Project Overview

This project provides an intelligent tourism management solution that:

- 📈 Forecasts visitor counts using Facebook Prophet
- 🚦 Detects rush levels using a hybrid statistical scoring model
- 📍 Recommends nearby underrated tourist spots
- 🗺️ Generates interactive maps with crowd status visualization
- 📊 Evaluates forecasting model performance with detailed metrics

It combines **Machine Learning, Data Analytics, and Geospatial Intelligence** into one complete pipeline.

---

## 🧠 Key Features

### 1️⃣ Visitor Forecasting
- Uses **Facebook Prophet** for time series prediction
- Supports yearly and weekly seasonality
- Generates 7-day future forecasts
- Displays prediction intervals (upper & lower bounds)

### 2️⃣ Hybrid Rush Detection System
Combines:
- Relative visitor increase
- Z-score deviation
- Percentile-based crowd threshold

Rush levels:
- 🟢 No Rush
- 🟡 Watch
- 🔴 Rush
- ⚫ Severe Rush

---

### 3️⃣ Nearby Place Recommendation
- Uses Haversine distance formula
- Recommends underrated places within 100 km
- Filters based on popularity and proximity
- Returns Top-K nearest hidden gems

---

### 4️⃣ Model Evaluation
Performance metrics:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)

Includes:
- Actual vs Predicted visualization
- Residual analysis
- Error distribution histogram

---

### 5️⃣ Interactive Map Visualization
Built using **Folium**

Map includes:
- Main searched location
- Rush status indicator
- Recommended nearby places
- Distance connections
- Full-screen and layer controls
- Custom legend

---

## 🛠️ Tech Stack

| Category | Tools Used |
|----------|------------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Forecasting | Facebook Prophet |
| Machine Learning | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Geospatial | Folium |
| Distance Calculation | Haversine Formula |

---

## 📂 Project Workflow

1. Load and clean visitor dataset
2. Generate time series per tourist place
3. Forecast visitor trends
4. Detect rush status using hybrid scoring
5. Recommend nearby underrated places
6. Evaluate model performance
7. Generate interactive map
8. Save map as downloadable HTML file
