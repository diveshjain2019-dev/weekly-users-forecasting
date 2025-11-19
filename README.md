# Weekly Active Users Forecasting with SARIMA

A time series forecasting project to predict weekly active users using SARIMA (Seasonal Autoregressive Integrated Moving Average) model.

## 🎯 Project Overview

This project forecasts weekly active users (specifically returning users) using historical data and accounts for strong seasonal patterns observed in the business cycle.

## 📊 Key Features

- **SARIMA Model**: (1,1,1)(1,1,0,52) configuration
- **52-week Seasonality**: Captures annual patterns
- **Custom Seasonal Multipliers**: 
  - March (post-22nd): 3.0x
  - April: 3.25x
  - May (pre-25th): 4.75x
  - Other periods: 1.75x
- **15-week Forecast Horizon**

## 🔍 Business Insights

The model reveals significant seasonal patterns:
- **Peak Activity**: March-May (3-4.75x baseline)
- **Baseline Activity**: 1.75x regular multiplier
- Perfect for capacity planning, resource allocation, and revenue forecasting

## 🛠️ Technologies Used

- Python 3.x
- pandas
- numpy
- statsmodels (SARIMAX)
- matplotlib


## 🚀 Usage
```python
# Run the Jupyter notebook
jupyter notebook notebooks/Forecasting_mau_sarima.ipynb
```

## 📈 Results

The model generates:
- 15-week forecast of weekly active users
- Visualization of historical vs predicted values
- CSV outputs for further analysis

## 📁 Project Structure
```
forecasting-project/
├── notebooks/         # Jupyter notebooks
├── outputs/           # Generated forecasts and visualizations
├── README.md
├── requirements.txt
└── .gitignore
```



## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📧 Contact

Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/divesh-jain/)

---

⭐ Star this repo if you found it helpful!
