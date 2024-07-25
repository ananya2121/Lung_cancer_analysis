# Lung_cancer_analysis
## Table of Contents

- [Introduction](#introduction)
- [Loading the Data](#loading-the-data)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Model Interpretation with SHAP](#model-interpretation-with-shap)
- [Conclusion](#conclusion)

# Introduction

This project focuses on analyzing a medical diagnostics dataset to predict the presence of lung cancer. The analysis includes data preprocessing, exploratory data analysis (EDA), model building, hyperparameter tuning, model evaluation, and model interpretation using SHAP (SHapley Additive exPlanations).

- Project Overview
  
- Data Loading
  
- Exploratory Data Analysis (EDA)
  
- Data Preprocessing
  
- Feature Engineering
  
- Model Building and Hyperparameter Tuning
  
- Model Evaluation
  
- Model Interpretation
  
- Conclusions

# Installation

To get started with this project, clone the repository and install the required dependencies.

# Prerequisites

- Python 3.8 or higher

- Anaconda

# Data
The dataset used in this project (dataseter.csv) contains various medical diagnostics features and a target variable indicating the presence of lung cancer.

# Handling Missing Values

- Missing values are filled with the mean for numerical columns and the mode for categorical columns.
  
# Encoding Categorical Variables

- Categorical variables are encoded using LabelEncoder.
  
# Handling Outliers
- Outliers are handled using the Interquartile Range (IQR) method.
  
# Feature Scaling
- Features are scaled using StandardScaler.
  
# Model Building
We built and tuned four models using GridSearchCV and RandomizedSearchCV:

1. Logistic Regression
 
2. Random Forest Classifier
 
3. Support Vector Machine (SVM)
   
4. Gradient Boosting Classifier
 
# Model Evaluation

Each model was evaluated using various metrics such as accuracy, ROC AUC score, and cross-validation scores.

# Example of Evaluation Metrics
- Accuracy

- ROC AUC Score

- Classification Report

# Model Interpretation

SHAP is used to interpret the Random Forest model, providing insights into the feature importance and their impact on the model's predictions.

# Conclusion

The project concludes with a summary of the findings and insights gained from the analysis and model interpretation.

# Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

# License

This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgements

This project utilizes various Python libraries including pandas, numpy, matplotlib, seaborn, scikit-learn, and shap.
Special thanks to the open-source community for providing these tools.

