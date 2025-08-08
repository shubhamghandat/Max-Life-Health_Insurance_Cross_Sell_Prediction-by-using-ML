# Max-Life-Health_Insurance_Cross_Sell_Prediction-by-using-ML
![image](https://github.com/user-attachments/assets/2c8bab68-1bb3-4949-a484-c4413e91c6fc)


## Project Overview
The insurance industry heavily relies on statistical models and predictive analytics to optimize business strategies and enhance revenue. This project focuses on a Health Insurance company seeking to expand its offerings by predicting whether their existing health insurance policyholders would be interested in purchasing vehicle insurance. The primary objective is to build a machine learning model capable of accurately classifying customers based on their likelihood of buying vehicle insurance. This enables the company to effectively tailor its marketing and communication strategies.

Insurance policies for health and vehicles operate on the principle of risk sharing and compensation. Customers pay regular premiums in exchange for a guarantee of compensation in the event of specific losses, damages, or illnesses. Calculating premium amounts requires an understanding of the probability of these insured events occurring, making the company's risk assessment capabilities critical. By leveraging demographic data, vehicle information, and policy details, this project aims to uncover patterns and predictors of customer behavior concerning vehicle insurance adoption.

## Key features of the project include:
* Data Exploration : Comprehensive analysis of demographic, vehicle, and policy-related data.
* Model Development : Application of various machine learning algorithms to build a robust classifier.
* Business Insights : Identification of key predictive features to guide business strategies.
* Evaluation Metrics : Focus on recall, F1-score, and precision to address the imbalanced dataset.

## Technologies Used
The following technologies, libraries, and frameworks were employed:
* Languages: Python
## Libraries:
* Data Manipulation: pandas, numpy
* Visualization: matplotlib, seaborn
* Machine Learning:
  1) Models: LogisticRegression, RandomForestClassifier, XGBClassifier, ExtraTreesClassifier
  2) Evaluation: accuracy_score, confusion_matrix, roc_auc_score, f1_score, precision_score, recall_score, classification_report
  3) Preprocessing: LabelEncoder, StandardScaler
  4) Tuning: GridSearchCV, RepeatedStratifiedKFold
  5) Feature Analysis: variance_inflation_factor from statsmodels
  6) To handle imbalanced datd- SMOTE from imblearn


## Key Files and Their Purpose:
### Data Files:
* train.csv: Contains training data with features and the target variable.
* test.csv: Test dataset for validating the model's performance.
### Main Notebook:
1) EDA: Data analysis, handling missing values, and visualizations
2) Data Preprocessing: Label encoding, scaling, handling multicollinearity with VIF, and balancing classes with SMOTE.
3) Model Training and Evaluation: Training models like Logistic Regression, Random Forest, and XGBoost; evaluating performance.
4) Hyperparameter Tuning: Optimization using GridSearchCV and RandomizedSearchCV.
5) Feature Importance: Analysis using RandomForestClassifier and VIF.
### Visualization Outputs:
1) Univariate, bivariate, and multivariate analyses (following the UBM rule).
2) Model performance comparison and feature importance plots.


## Model Performance Comparison
## Model Performance Comparison 📊
![image](https://github.com/user-attachments/assets/2a70a871-61a6-4259-ab3f-e733c41471c9)
