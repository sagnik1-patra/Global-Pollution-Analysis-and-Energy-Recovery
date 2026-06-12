
# Global Pollution Analysis and Energy Recovery Report

## Objective

The objective of this project is to analyze global pollution data and develop
machine learning models to predict energy recovery from pollution levels.
The project also classifies pollution severity and provides actionable insights
for pollution reduction and energy recovery improvement.

## Dataset

Dataset used:

Global_Pollution_Analysis.csv

Rows: 200
Columns: 15

## Data Preprocessing

The dataset was loaded and column names were cleaned.
Missing numerical values were handled using median imputation.
Missing categorical values were handled using most frequent value imputation.
Categorical columns were encoded using Label Encoding.
Pollution-related numerical features were scaled where required.

## Feature Engineering

The following features were created:

1. Energy Consumption per Capita
2. Pollution Severity Category
3. Total Pollution Score
4. Yearly Trend Summary

## Exploratory Data Analysis

EDA included:

1. Descriptive statistics
2. Missing value analysis
3. Correlation heatmap
4. Average air pollution by country
5. Energy recovery trends over years
6. CO2 emission distribution by pollution severity
7. Air pollution vs energy recovery scatter plot

## Linear Regression Model

Objective:

Predict Energy Recovered in GWh using pollution indicators and other features.

Metrics:

R2 Score: -0.04921760617702886
MSE: 25372.428368539473
MAE: 142.53008043598987
RMSE: 159.28725111740573

## Logistic Regression Model

Objective:

Classify pollution severity into Low, Medium, and High categories.

Metrics:

Accuracy: 1.0
Precision: 1.0
Recall: 1.0
F1 Score: 1.0

## Model Comparison

Linear Regression was used for continuous energy recovery prediction.
Logistic Regression was used for pollution severity classification.

Both models solve different objectives, so their scores are not directly
comparable. Linear Regression performance should be judged using R2, MSE,
MAE, and RMSE. Logistic Regression performance should be judged using
Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.

## Actionable Insights

1. Countries with high pollution and low energy recovery should be prioritized.
2. Industrial waste can be converted into useful energy through waste-to-energy systems.
3. High CO2-emitting countries should increase renewable energy adoption.
4. Countries with poor air pollution scores should improve emission control policies.
5. Energy recovery can be improved by investing in recycling, biomass energy,
   biogas generation, and industrial waste heat recovery.
6. Pollution severity classification can help policymakers identify countries
   requiring urgent intervention.

## Recommendations

1. Adopt waste-to-energy conversion plants.
2. Improve industrial waste segregation and recycling.
3. Increase renewable energy usage.
4. Introduce stricter carbon emission policies.
5. Promote cleaner production technologies.
6. Monitor pollution indices yearly.
7. Use predictive models for future environmental planning.

## Generated Deliverables

1. Cleaned dataset
2. Encoded dataset
3. Feature engineered dataset
4. Descriptive statistics CSV
5. Missing value report
6. Correlation matrix
7. EDA graphs
8. Linear Regression model and metrics
9. Logistic Regression model and metrics
10. Confusion matrix
11. Model comparison file
12. Countries needing improvement file
13. Trained model files
