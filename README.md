# ML-Assignment
Machine Learning - IT4060 - Programming Assignment

## Temperature Prediction Using Machine Learning  
Forecasting Daily Mean Temperatures Across Sri Lanka

### 📌 Overview  
This project applies supervised machine learning algorithms to forecast daily mean temperatures across various districts in Sri Lanka using historical weather data. The goal is to compare the effectiveness of three regression models—Linear Regression, Random Forest Regressor, and Support Vector Regressor (SVR)—in terms of accuracy and computational efficiency.

### 🧠 Machine Learning Algorithms Used  
- **Linear Regression**  
  A simple baseline model assuming a linear relationship between features and target.

- **Random Forest Regressor**  
  An ensemble learning method using multiple decision trees to improve accuracy and reduce overfitting.

- **Support Vector Regressor (SVR)**  
  A kernel-based algorithm capable of capturing complex, nonlinear relationships.

### 📊 Dataset  
- **Source:** [Kaggle - Sri Lanka Weather Data for All Districts](https://www.kaggle.com/datasets/tharindumadhusanka9/sri-lanka-weather-data-for-all-districts)  
- **Period Covered:** 2010 to June 2024  
- **Size:** 142,372 daily records across multiple districts  
- **Features:**  
  - Temperature, humidity, sunshine duration, precipitation, wind speed, radiation  
  - Geographical information (latitude, longitude, elevation)  
  - Temporal data (date, daylight hours)


### 📈 Evaluation Metrics  
Models were evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) Score

| Model                | MAE     | RMSE    | R² Score |
|---------------------|---------|---------|----------|
| Linear Regression    | 0.3719  | 0.5531  | 0.9511   |
| Random Forest        | 0.1509  | 0.2046  | 0.9952   |
| Support Vector Regressor | 0.3668  | 0.4969  | 0.9724   |

### 🚀 Results & Insights  
- **Best Performance:** Random Forest Regressor
- **Fastest Training Time:** Linear Regression (~1 sec)
- **Most Complex but Generalizable:** SVR

### 👨‍💻 Contributors 
|Contributor | Model                |
|---------|---------------------|
| Jayathilaka A G K D | Linear Regression    | 
| Rathnayake  R M U V | Random Forest        | 
| Gunasekara W M A S | Support Vector Regressor |

## 👍Acknowledgments
- The dataset is provided by Tharindu Madhusanka on Kaggle.
[Sri Lanka Weather Dataset on Kaggle](https://www.kaggle.com/datasets/tharindumadhusanka9/sri-lanka-weather-data-for-all-districts)
- Special thanks to the Kaggle and open-meteo.com teams for making the data publicly available.
