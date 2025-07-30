# TASK-3-HOUSEHOLD-POWER-
# 🔋 Time Series Forecasting – Energy Consumption

This project focuses on forecasting household energy usage using time series models such as ARIMA, Prophet, and XGBoost.

---

## 📁 Dataset

- **File:** `household_power_consumption.csv`
- **Description:** Contains minute-level data of electricity consumption.
- **Target Column:** `Global_active_power`

---

## 🧠 Task Objectives

- Parse and resample the time series data
- Engineer time-based features (hour, weekday, weekend)
- Train forecasting models (ARIMA, Prophet, XGBoost)
- Compare forecast performance
- Visualize actual vs. predicted energy usage

---

## 🧾 Steps Performed

1. **Import Required Libraries**
2. **Load and Clean Data**
3. **Resample to Hourly Frequency**
4. **Feature Engineering**
   - Hour of day
   - Day of week
   - Weekend flag
5. **Train Models**
   - ARIMA (classical model)
   - Prophet (additive time series)
   - XGBoost (machine learning approach)
6. **Visualize**
   - Actual vs. Forecasted plot

---

## 📊 Models Compared

| Model     | Approach        |
|-----------|-----------------|
| ARIMA     | Statistical     |
| Prophet   | Additive model  |
| XGBoost   | ML-based        |

---

## 📈 Output

A combined plot showing actual energy usage and predictions from all three models for the final 7 days.

---

## 🛠️ Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `statsmodels` (ARIMA)
- `prophet`
- `xgboost`
- `scikit-learn`

---

## 📥 How to Run

```bash
pip install -r requirements.txt
