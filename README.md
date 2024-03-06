 # Seoul Public Bike Demand Prediction

[The Seoul Public Bike (Ttareungyi)]([url](https://english.seoul.go.kr/service/movement/seoul-public-bike/1-seoul-public-bike/)) system is a bike-sharing service managed by the Seoul City Government in South Korea. It aims to provide sustainable and convenient transportation options for residents and tourists in Seoul. To optimize bicycle availability and meet user demand, the Seoul City government seeks to predict bicycle demand at different times using historical data on bike rentals.

This project focuses on building machine learning models to predict bicycle demand accurately. Various regression algorithms such as Linear Regression, Decision Tree Regression, Random Forest Regression, Gradient Boosting Regression, Support Vector Regression, K-Nearest Neighbors Regressor, Lasso, Ridge, XGBoost Regressor, and AdaBoost Regressor are evaluated using Mean Absolute Percentage Error (MAPE) as the evaluation metric.

The best-performing model, **XGBoost Regressor**, achieves a MAPE of 39.20% on the test data. However, comparison with the model evaluation MAPE 36.57% suggests potential overfitting, indicating the model's limitations in generalizing to new data.

Key insights from the analysis include identifying factors such as time of day, weather conditions, and seasonality that influence bicycle demand. **Feature importance** analysis highlights "hr," "is_weekend," "season," "tempt," and "weathersit" as the most influential features in predicting demand.

In conclusion, while the prediction model provides valuable insights, further optimization is needed to improve accuracy and generalization. This project serves as a foundation for future research and decision-making processes in managing bicycle inventory and optimizing service delivery for the Seoul Public Bike system.
