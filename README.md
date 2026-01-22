## Project 
Credit Card Fraud Dectection Using Machine Learning
## Description
This project focuses on detecting fraudulent credit card transactions using machine learning algorithms. 
The goal is to classify transactions as **fraudulent** or **legitimate** based on historical transaction data.
## Project Workflow

#### a. Data Cleaning & Preprocessing:

Checked for missing values and handled them (e.g., imputed with mean/median if numeric).

Removed irrelevant columns and addressed outliers to avoid skewing the analysis.

Converted categorical columns (like payment type, location) to numeric values using encoding (One-hot, Label Encoding).

#### b. Exploratory Data Analysis (EDA):

Univariate analysis → Looked at individual variables (histograms, value counts).

Bivariate analysis → Checked relationships between two variables (fraud vs amount, fraud vs region).

Multivariate analysis → Identified correlations and patterns across multiple variables.

#### c. Model Building:

Split data into training and testing sets.

Built classification models: Logistic Regression, Random Forest, XGBoost.

Chose these because they are commonly used for binary classification problems.

#### d. Model Evaluation:

Evaluated models using Accuracy, Precision, Recall, F1-score, ROC-AUC to ensure reliability.

Checked confusion matrix to compare predicted vs actual transactions.

e. Visualization & Insights:

Visualized fraud patterns and trends.

Highlighted anomalies and transaction characteristics that indicate fraud.

Created dashboards summarizing key insights.
