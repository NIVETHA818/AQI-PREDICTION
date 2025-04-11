# AQI-PREDICTION
# AQI Prediction Using XGBoost

This project predicts the **Air Quality Index (AQI)** for Indian cities using historical air pollution data and a machine learning model. It utilizes the **XGBoost Regressor**, which is known for its performance and accuracy in tabular datasets.

## Dataset
The dataset `aqi data set` contains:
- City names
- AQI values
- Date of recording
## Libraries Used
-pandas
-numpy
-xgboost
-scikit-learn

##  Machine Learning Model

- **Model Used**: XGBoost Regressor
- **Features Used**:
  - Encoded station code
  - Month (to account for seasonal trends)
  - Year (to track time-based progression)

- **Target Variable**: AQI (Air Quality Index)

##  Evaluation Metrics
- **Mean Squared Error (MSE)**
- **R² Score**

##  AQI Prediction Function

You can use the function `predict_aqi(station number, month, year)` to predict AQI for a specific city and time.

### Example:
```python
predict_aqi("Dh0021", 5, 2030)
