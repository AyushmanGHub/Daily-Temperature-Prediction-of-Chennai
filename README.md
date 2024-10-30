<h1 align="center">Chennai Temperature and Precipitation Forecasting </h1>


The project focuses on predicting daily weather variables for Chennai, including average temperature (`tavg`), minimum temperature (`tmin`), maximum temperature (`tmax`), and precipitation (`prcp`). Using historical weather data, the project employs machine learning techniques, specifically a `MultiOutputRegressor` wrapping around the `LGBMRegressor`, to predict multiple weather parameters simultaneously. The feature set is prepared by excluding the target variables, and the model is trained on the remaining features. The performance of the model is evaluated using Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and Root Mean Squared Error (RMSE) for each weather variable. This approach provides a robust way to predict weather conditions, assisting in better forecasting for the region.

### Final Ressult: Real vs predicted 
<img src="temperature real vs pred.png" alt="Alt Text" width="1000"/>
<img src="precipitation real vs pred.png" alt="Alt Text" width="1000"/>


## Model Evaluation Metrics

### 1. **Average Temperature (`tavg`)**
- **Mean Absolute Error (MAE):** 0.96
- **Mean Absolute Percentage Error (MAPE):** 3.20%
- **Root Mean Squared Error (RMSE):** 1.21

### 2. **Minimum Temperature (`tmin`)**
- **Mean Absolute Error (MAE):** 1.31
- **Mean Absolute Percentage Error (MAPE):** 4%
- **Root Mean Squared Error (RMSE):** 1.58

### 3. **Maximum Temperature (`tmax`)**
- **Mean Absolute Error (MAE):** 1.39
- **Mean Absolute Percentage Error (MAPE):** 4%
- **Root Mean Squared Error (RMSE):** 1.84

### 4. **Precipitation (`prcp`)**
- **Mean Absolute Error (MAE):** 8.86
- **Mean Absolute Percentage Error (MAPE):** 11 %
- **Root Mean Squared Error (RMSE):** 24.33

