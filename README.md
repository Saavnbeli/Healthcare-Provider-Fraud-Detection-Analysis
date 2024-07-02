# Detecting Healthcare Provider Fraud Using Machine Learning

## Project Overview

This project focuses on identifying and deterring fraudulent activities by healthcare providers using various machine learning techniques. I utilized a historical healthcare-related dataset to train and test models that can accurately classify claims as fraudulent or legitimate. The main aim is to reduce financial losses, improve compliance, and enhance patient care by detecting fraudulent claims efficiently.

## Project Goals and Objectives

- **Fraud Detection:** Develop models to predict potentially fraudulent healthcare claims.
- **Feature Analysis:** Identify significant variables contributing to fraud detection.
- **Pattern Recognition:** Analyze patterns in fraudulent claims to gain insights into provider behavior.
- **Machine Learning Implementation:** Utilize advanced machine learning algorithms to achieve high accuracy in fraud detection.

## Technologies Used

- **Python:** Programming language for data analysis and model implementation.
- **Pandas and NumPy:** Data manipulation and numerical computations.
- **Scikit-Learn:** Machine learning library for model training and evaluation.
- **XGBoost:** Advanced implementation of gradient boosting.
- **Matplotlib and Seaborn:** Data visualization libraries.
- **Google Drive:** Storage for dataset access.

## Dataset

The dataset used in this project consists of healthcare claims data sourced from Kaggle. It includes:
- Inpatient claims
- Outpatient claims
- Beneficiary details

### Data Preprocessing and Transformation

1. **Data Cleaning:** Addressed missing values, outliers, and inconsistencies.
2. **Feature Engineering:** Created new variables and encoded categorical variables.
3. **Normalization:** Ensured consistency and comparability of data by normalizing numerical features.

## CRISP-DM Approach

I followed the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology, which includes:
1. **Business Understanding:** Defined project objectives and goals.
2. **Data Understanding:** Performed exploratory data analysis (EDA) to comprehend data structure and quality.
3. **Data Preparation:** Preprocessed data to make it suitable for model training.
4. **Modeling:** Trained and validated machine learning models.
5. **Evaluation:** Assessed model performance using metrics like accuracy, AUC, and F1 score.
6. **Deployment:** Planned for future deployment in a real-world setting.

## Models Implemented

### Logistic Regression
A common algorithm for binary classification tasks, predicting the probability of fraud based on features.

### Decision Trees
A tree-like model for making predictions by recursively splitting the data based on feature values.

### Random Forest
An ensemble method that combines multiple decision trees to improve performance and robustness.

### XGBoost
An advanced gradient boosting algorithm known for high performance in classification tasks.

## Results

- **Accuracy:** Assessed the overall correctness of the models.
- **F1 Score:** Evaluated the balance between precision and recall.
- **AUC:** Measured the model's ability to distinguish between classes.

### Model Performance

| Model             | Accuracy | F1 Score | AUC   |
|-------------------|----------|----------|-------|
| Logistic Regression | 62.98%   | 48.29%   | 0.5875|
| Decision Tree     | 75.22%   | 69.51%   | 0.8227|
| Random Forest     | 63.87%   | 54.95%   | 0.6576|
| XGBoost           | 76.23%   | 69.29%   | 0.8177|

### Feature Importance

Identified key features contributing to fraud detection, improving model interpretability and performance.

## Conclusion and Future Work

### Conclusion
The machine learning models successfully identified patterns in fraudulent claims, providing valuable insights for developing robust fraud detection systems in healthcare.

### Future Work
- **Enhanced Feature Engineering:** Explore additional features and interactions.
- **Real-time Detection:** Implement models for real-time fraud detection.
- **Deployment:** Operationalize models in a production environment for continuous monitoring and improvement.
