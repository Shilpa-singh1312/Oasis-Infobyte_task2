# Sales Prediction using Python
## Overview
This project aims to predict future sales based on various factors such as advertising expenditure, target segments, and advertising platforms. Predicting sales accurately is crucial for businesses to optimize their marketing strategies and allocate resources effectively. This project utilizes machine learning techniques to model and forecast sales.

Dataset: https://www.kaggle.com/datasets/bumba5341/advertisingcsv
### Table of Contents
- Features
- Data Preprocessing
- Comparison of Models
- Conclusion
- Requirements
### Features
- Advertising Expenditure: Amount spent on advertising.
- Target Segment: Segment of people targeted by the advertisement.
- Platform: Platform where the advertisement is placed (e.g., social media, TV, etc.).
### Data Preprocessing
- Load Data: The dataset should be loaded from a CSV file or any other format you prefer.
- Feature Engineering: Create features relevant to sales prediction.
- Train-Test Split: Divide the data into training and testing sets for model evaluation.
- Feature Scaling: Scale features if necessary to improve model performance.
### Comparison of Models
Various models were trained to predict sales, including:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- Model Performance
#### XGBoost Regressor:

- Training MSE: 0.000003
- Testing MSE: 0.868933
- Training R² Score: 1.000000
- Testing R² Score: 0.972470
- Random Forest Regressor:

- Training MSE: 2.705129
- Testing MSE: 3.174097
- Training R² Score: 0.895701
- Testing R² Score: 0.899438
### Conclusion
General Performance: XGBoost and Random Forest are the top-performing models, showing very low MSE and high R² scores, indicating excellent predictive power and generalization.
Overfitting: The Decision Tree model exhibits significant overfitting, performing well on training data but poorly on testing data.
Model Choice: XGBoost is preferred due to its high performance and generalization ability, followed closely by Random Forest. Linear Regression performs well but does not match the performance of ensemble methods. Decision Trees should be used cautiously or tuned to avoid overfitting.
### Requirements
Python 3.x
pandas
numpy
scikit-learn
xgboost
Install the required packages using pip: 

pip install pandas numpy scikit-learn xgboost
