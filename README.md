**🌫️ Air Quality Prediction using Machine Learning**

**📌 Project Overview**

This project predicts air quality levels using machine learning. By analyzing environmental factors such as temperature, humidity, and wind speed, the model forecasts air pollutants like CO, NO2, O3, and PM2.5, helping to understand and predict air quality trends.

**🚀 Features**

Data Preprocessing: Cleans and prepares the dataset by handling missing values and scaling features.

Machine Learning Models: Uses regression models (e.g., Linear Regression, Random Forest) for air quality prediction.

Performance Metrics: Evaluates model performance using MAE, MSE, R², and feature importance.

Visualizations: Includes plots like feature importance, prediction vs actual values, and AQI distribution.

**📂 Project Structure**

📦 Air-Quality-Prediction
│── 📂 data/ # Dataset files
│── 📂 src/  # Source code
│── 📜 air_quality_model.py    # Main script for model training and prediction
│── 📜 requirements.txt     # Dependencies
│── 📜 README.md            # Project documentation

**📊 Dataset Information**

Dataset Used: air_quality.csv

Columns:

Date: Date of observation

Temperature: Temperature in °C

Humidity: Relative humidity in percentage

Wind Speed: Wind speed in km/h

CO: Carbon monoxide concentration (ppm)

NO2: Nitrogen dioxide concentration (ppb)

O3: Ozone concentration (ppb)

PM2.5: Particulate matter concentration (µg/m³)

AQI: Air Quality Index (target variable for prediction)

**🔍 Model Training & Evaluation**

Algorithm Used: Multiple regression algorithms including Linear Regression, Decision Trees, and Random Forest.

Train-Test Split: 70% training, 30% testing

Performance Metrics:

✅ Mean Absolute Error (MAE)

✅ Mean Squared Error (MSE)

✅ R² Score

✅ Feature Importance Visualization

**📊 Results & Visualizations**

1. **✅ Correlation Heatmap**
   
Visualizes the correlations between key features, highlighting relationships that influence CO(GT) concentration.
![image](https://github.com/user-attachments/assets/f7990e47-3f74-4a4d-bf7e-ad189ad50592)
2. **✅ Actual vs Predicted Plot**

Compares actual vs predicted CO(GT) values to assess prediction accuracy. Points closer to the red line indicate better predictions.
![image](https://github.com/user-attachments/assets/e542315a-43b9-46b5-b697-dae679c91707)
3. **✅ Residuals Distribution**

Shows the distribution of residuals (prediction errors). Ideally, residuals should be centered around zero, indicating good model fit.
![image](https://github.com/user-attachments/assets/94be0848-3c38-41c5-8b47-46db0632f8da)
4. **✅ Residuals vs Predictions**

Examines if residuals are randomly distributed. A random spread suggests the model captured all patterns in the data.
![image](https://github.com/user-attachments/assets/49c377f3-80c5-4ad1-88d9-81d98b74a43e)
5.**✅ Feature Coefficients**

Displays feature importance based on regression coefficients, showing which variables most influence CO(GT) predictions.
![image](https://github.com/user-attachments/assets/b512788f-79af-444d-b206-e1b617b1c36d)





