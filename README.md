# PredictiveMaitenanceProject

## Overview
This repository contains code and data for a predictive maintenance classification task. The goal is to predict whether a piece of equipment will fail in the future based on historical data. The dataset has been cleaned, visualized, and used for feature engineering and modeling with various machine learning algorithms.

### Dataset
The dataset used for this task consists of historical maintenance records and sensor readings from various equipment. Each instance in the dataset represents a snapshot of the equipment's state at a given time. The target variable is binary, indicating whether the equipment failed within a certain time period after the snapshot.

### Data Cleaning
The data underwent preprocessing to handle missing values, outliers, and irrelevant features. Cleaning steps included imputation, outlier removal, and feature selection to ensure data quality for modeling.

### Data Visualization
Visualizations were created to explore the relationships between features and the target variable. Heatmaps were used to visualize correlations between features, while histograms, boxplots, and line plots were employed to understand the distributions and trends in the data.

### Feature Engineering
Feature engineering techniques were applied to create new features or transform existing ones to improve the predictive power of the models. Time-based features, rolling statistics, and interaction terms were among the engineered features.

### Modeling
Three machine learning algorithms were employed for modeling: Gradient Boosting, Logistic Regression, and a Neural Network. Each model was trained using cross-validation, and hyperparameters were tuned to optimize performance. StandardScaler was used to normalize features, and oversampling techniques were applied to address class imbalance.

### Evaluation Metrics
The models were evaluated using various metrics, including precision, accuracy, ROC AUC, ROC PR, and F1 score. These metrics were chosen to assess the models' performance in predicting equipment failure accurately and efficiently.

### Results
After extensive modeling and evaluation, the following results were achieved:

* Gradient Boosting: Precision of 0.1667, Specificity of 0.9996
* Logistic Regression: AUC-ROC of  0.7696, ROC AUC of 0.32
* Neural Network: AUC-ROC of 0.5252

## Conclusion
The predictive maintenance classification task demonstrated the effectiveness of Gradient Boosting in accurately predicting equipment failure. Further improvements could be made by exploring more advanced neural network architectures or refining feature engineering techniques.

