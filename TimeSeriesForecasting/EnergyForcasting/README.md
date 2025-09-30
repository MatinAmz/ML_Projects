# Electricity Demand & Price Forecasting

This project focuses on **multivariate time-series forecasting** of electricity demand and prices for Spain, using four years of hourly energy and weather data.

## 📌 Project Objective
To build machine learning models that predict **electricity demand and price fluctuations** by incorporating historical energy consumption, market data, and weather variables.

## 📊 Data Sources
- **ENTSO-E Transparency Platform** – European electricity data  
- **Red Eléctrica de España (REE/ESIOS)** – Spanish system operator data  
- **OpenWeatherMap API** – Hourly weather features (temperature, wind speed, humidity, etc.)  

## ⚙️ Feature Engineering
- Calendar features (hour-of-day, weekday vs. weekend, holidays)  
- Normalization and scaling  
- Principal Component Analysis (PCA) for dimensionality reduction  
- Correlation analysis of weather and energy variables  

## 🤖 Models Explored
- **XGBoost** – Gradient boosting on structured features  
- **GRU (Gated Recurrent Unit)** – Sequence modeling for time series  
- **Other baselines** – Persistence and naive forecasts  

## 📈 Evaluation
- **Loss:** Mean Absolute Error (MAE)  
- **Metrics:**  
  - MAE: interpretable in real-world units  
  - Compared across normalized test set for fairness  

## 📉 Visualizations
- Correlation plots between energy demand, price, and weather variables  
- Seasonal and distributional plots (hourly, daily, weekend vs. weekday)  
- Comparison of **TSO forecasts vs. realized demand**  

## 🛠️ Tools & Libraries
- Python 3.x  
- Jupyter Notebook  
- NumPy, Pandas, Matplotlib, Seaborn  
- Scikit-learn, XGBoost  
- TensorFlow/Keras (for GRU model)  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
