# 📊 Cambodia Tourism Forecasting 🌍

## Overview 🌟

This project forecasts Cambodia's tourism trends for the next **6 months** using cutting-edge modeling techniques. We combine **XGBoost** 🧠 (a powerful machine learning model) and **ARIMA** 📈 (a time series statistical model) through an **ensemble method** 🤝 to provide **accurate and actionable predictions**.

---

## Objectives 🎯

1. **📉 Analyze Tourism Trends**: Identify seasonal patterns and key influencing factors.  
2. **🔮 Predict Future Tourism**: Generate reliable forecasts to support strategic planning.  
3. **🚀 Enhance Model Performance**: Use an ensemble approach to boost accuracy and minimize errors.  

---

## Features ✨

- **XGBoost Model** 🧠:
  - Captures complex relationships between features.  
  - Incorporates external variables like holidays, weather, and global events.

- **ARIMA Model** 📈:
  - Handles time-series data with trends and seasonality.
  - Focuses on the statistical patterns in historical data.

- **Ensemble Method** 🤝:
  - Combines strengths of XGBoost and ARIMA to deliver robust forecasts.

---

## Project Structure 🗂️

```
Cambodia_Tourism_Forecasting/
├── data/                   # 📂 Raw and processed datasets
├── notebooks/              # 📓 Jupyter notebooks for analysis and modeling
├── scripts/                # 🛠️ Python scripts for automation
├── models/                 # 🧠 Saved models (XGBoost, ARIMA, and ensemble)
├── results/                # 📊 Outputs: forecasts, plots, and metrics
├── requirements.txt        # 📋 Required Python packages
├── README.md               # 📖 Project documentation
└── main.py                 # 🚀 Main script to run the pipeline
```

---

## Data Requirements 📑

The forecasting models rely on **historical tourism data**, such as:  
- 🏨 **Visitor Statistics**: Monthly arrival data by region and demographics.  
- 🎉 **Seasonal Indicators**: Public holidays, festivals, and vacation seasons.  
- 📊 **Economic Factors**: GDP, exchange rates, and inflation.  
- 🌐 **Global Trends**: Travel restrictions, global events, or disruptions (e.g., COVID-19).  

Ensure the data is cleaned, formatted, and split into training and testing sets.

---

## Methodology 🔬

1. **🔧 Data Preprocessing**:
   - Handle missing data and outliers.  
   - Engineer features for XGBoost (e.g., lag values, holiday indicators).  
   - Transform data to stationarity for ARIMA.

2. **📘 Model Training**:
   - **XGBoost**: Optimize hyperparameters and train on explanatory features.  
   - **ARIMA**: Use statistical techniques to identify the best configuration.  

3. **🤝 Ensemble Combination**:
   - Blend predictions using:  
     - **Weighted Averaging**: Combine based on model accuracy.  
     - **Stacking**: Train a meta-model on outputs of XGBoost and ARIMA.

4. **📏 Evaluation**:
   - Metrics: **RMSE**, **MAE**, and **MAPE**.  
   - Backtesting for robust validation.

5. **📅 Forecasting**:
   - Generate **6-month predictions** with confidence intervals.  
   - Visualize trends and insights.

---

## Installation ⚙️

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/Cambodia_Tourism_Forecasting.git
   cd Cambodia_Tourism_Forecasting
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the pipeline:  
   ```bash
   python main.py
   ```

---

## Results 🎉

- **📈 Forecasts**: Saved in the `results/` directory as `.csv` files.  
- **📊 Visualizations**: Plots of historical trends and future predictions.  
- Example output:  
  - "Total Visitors Prediction: 📅 Jan-June 2024"  
  - Confidence intervals for decision-making.  

---

## Future Improvements 🚀

- **🔗 Integrate Real-Time Data**: Flight bookings, hotel reservations, or online searches.  
- **📘 Explore New Models**: Use deep learning methods like LSTM or Prophet.  
- **⏳ Extend Time Horizon**: Forecast for 12 months or more.

---

## Authors & Acknowledgements 🙌

This project was developed by **RITHY VIRA** with inspiration from Cambodia’s vibrant tourism sector 🌺.  

📬 **Contact**: [rithyvira021@gmail.com]  

---

**Let’s shape the future of tourism in Cambodia together!** 🌍✈️
