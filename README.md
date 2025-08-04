# Forest-Fires
M. Tech Thesis titled "Evaluating Forest Fire Vulnerability and Climate Drivers in Northeast India using Remote Sensing and  Advanced Machine Learning Techniques" #ML #GEE #Python

The code predicts the no. of forest fire occurrences, based on historical data present from 2012. Data from 2012 to 2023 is used for training the model, and 2024 data is used for testing the model. Once the model is build, all the historical data available from 2012 to 2024 is used, and predicted for 2025. the data is not continuous, as the forest fires occur majorly during the summer. Hence, the models are of seasonal fire occurrence prediction, trained and tested using Mar - May data of each year, predicting for Mar - May 2025.

<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/462cdf53-8b05-40d9-a8ad-1beb20621553" />
### Fig - Seasonal Prediction of forest fire occurrences using Catboost

<img width="1190" height="590" alt="image" src="https://github.com/user-attachments/assets/ecb5494a-52aa-4c64-87b8-a0e63152a9b8" />
### Fig - Seasonal Prediction of forest fire occurrences using LightGBM

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/2593f5a8-3bfe-454f-b0d8-332cff71274e" />
### Fig - Seasonal Prediction of forest fire occurrences using XGBoost
