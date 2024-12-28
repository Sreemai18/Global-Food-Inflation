## Overview
Welcome to the Global Food Inflation Analysis project! 🌍📈

This project dives deep into the rising global food prices, exploring the underlying causes and predicting future trends using cutting-edge machine learning techniques. By analyzing economic data from Afghanistan and Burundi spanning from 2007 to 2023, we aim to uncover patterns and provide insights that can help mitigate the impact of food inflation worldwide.
Food price inflation affects economies, cultures, and everyday lives across the globe. Understanding its drivers is crucial for developing strategies to ensure food security and economic stability. This project leverages AI and machine learning to make sense of complex data and predict future trends, offering valuable information for policymakers, businesses, and communities.

## Key Features:
Data Preprocessing & Visualization: Cleaned and visualized data to identify trends and patterns.
Machine Learning Models: Implemented and compared multiple models to predict food inflation:
Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Random Forest Regressor
XGBoost Regressor
Hyperparameter Tuning: Optimized models to achieve the best performance.
Correlation Analysis: Explored relationships between different economic indicators.
## Data Used:
Time Frame: 2007 - 2023
Countries: Afghanistan & Burundi
Variables: Open, High, Low, Close prices, Inflation rates, Country details, Dates
## Technologies
Python: Core programming language.
Pandas & NumPy: For data manipulation and preprocessing.
Scikit-learn: For building and evaluating machine learning models.
XGBoost: Advanced tree-based boosting method.
Matplotlib: For data visualization.
## Results
Random Forest Regressor:
R² Score: 0.964
Mean Squared Error (MSE): 124.12
XGBoost Regressor:
R² Score: 0.884
Mean Squared Error (MSE): 124.13
K-Nearest Neighbors (KNN) Regression:
Test Set R² Score: 0.643
Test Set MSE: 382.66
Support Vector Machine (SVM) Regression:
R² Score: -0.068
Mean Squared Error (MSE): 1144.99
Linear Regression:
Coefficients: [-1.941, 1.241, 1.712]
Intercept: -0.002
## Contributing
We welcome contributions! If you have ideas to improve the project or want to add new features, please open an issue or submit a pull request. Let’s work together to make this project even better! 🤝
