Restaurant Demand Prediction Using Machine Learning and the KDD Process

Project Overview

This project applies the Knowledge Discovery in Databases (KDD) process to analyze restaurant-related data and develop machine learning models.

The project explores two datasets:

1. Restaurant Visitor Forecasting: Predicts the number of visitors using historical restaurant data, calendar features, and visitor trends.
2. Restaurant Operations Dataset: Contains restaurant orders, customers, payments, order items, and customer feedback.

The goal is to investigate how data preprocessing, feature engineering, and machine learning can support restaurant analytics and decision-making.

Objectives

* Understand and preprocess restaurant datasets.
* Perform exploratory data analysis and feature engineering.
* Apply suitable machine learning techniques.
* Evaluate predictive performance using appropriate metrics.
* Compare results and identify useful insights for restaurant operations.

Datasets

Dataset 1: Restaurant Visitor Forecasting

Contains historical restaurant visitor counts, restaurant information, and calendar features.

Target variable: visitors

Approach: CatBoost Regression

Dataset 2: Restaurant Operations Dataset

Contains information about orders, order items, customers, payments, and feedback.

Potential applications include:

* Restaurant order-demand prediction.
* Order-volume analysis.
* Customer satisfaction analysis.

Note: The current notebook uses this dataset for customer satisfaction classification. The pipeline must be revised if the objective is to compare demand prediction across both datasets.

Technologies Used

* Python
* Google Colab
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn
* CatBoost
* XGBoost

KDD Methodology

1. Data Selection: Select relevant restaurant visitor and operational data.
2. Data Preprocessing: Handle missing values, convert data types, and prepare the datasets.
3. Data Transformation: Create calendar features, historical visitor features, and other relevant predictors.
4. Data Mining: Train machine learning models suited to the prediction task.
5. Evaluation: Assess model performance using appropriate evaluation metrics and interpret the results.

Evaluation Metrics

For regression models:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

For classification models:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

Project Structure

Restaurant-Demand-Prediction/
├── restaurant_demand_prediction.ipynb
├── README.md
└── datasets/
    ├── Dataset_1/
    └── Dataset_2/

The datasets may need to be downloaded separately. Update the notebook’s file paths according to your environment.

How to Run

1. Clone or download this repository.
2. Download the required datasets from their original sources.
3. Open restaurant_demand_prediction.ipynb in Google Colab.
4. Upload the required CSV files.
5. Run the notebook cells in order.
6. Review the model evaluation results and visualizations.

Expected Outcome

The project aims to demonstrate the KDD process, develop suitable machine learning models, evaluate their performance, and derive insights that may help with restaurant demand planning.

Project Information

Domain: Predictive Analytics and Machine Learning
Methodology: Knowledge Discovery in Databases (KDD)
Environment: Google Colab
