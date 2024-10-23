<h1 align="center">Daily Temperature Prediction of Chennai </h1>


The project focuses on predicting daily weather variables for Chennai, including average temperature (`tavg`), minimum temperature (`tmin`), maximum temperature (`tmax`), and precipitation (`prcp`). Using historical weather data, the project employs machine learning techniques, specifically a `MultiOutputRegressor` wrapping around the `LGBMRegressor`, to predict multiple weather parameters simultaneously. The feature set is prepared by excluding the target variables, and the model is trained on the remaining features. The performance of the model is evaluated using Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and Root Mean Squared Error (RMSE) for each weather variable. This approach provides a robust way to predict weather conditions, assisting in better forecasting for the region.

### Final Ressult: Real vs predicted 
<img src="Pred vs real.png" alt="Alt Text" width="1000"/>
