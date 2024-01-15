# Home-Credit-Default-Risk

Overview

This project aims to predict the repayment abilities of potential borrowers using various machine learning techniques. We utilize multiple data sources, including credit bureau data, application histories, and more, to predict whether applicants will likely default on their loans. The primary focus is using tree-based models such as CatBoost, XGBoost, and LightGBM to handle categorical features and efficiently process large datasets.

Data Description
The dataset contains several files representing different sources of data:

Application Records: Information from the loan applications.
Bureau Data: Data from other financial institutions reported to a credit bureau.
Previous Applications: Historical data of previous loan applications at Home Credit.

All data files are in CSV format and can be loaded using Pandas.

Methodology

The project follows these steps:

1. Data Preprocessing: Handling missing values, encoding categorical variables, and data normalization.
2. Exploratory Data Analysis (EDA): Visualizing data distributions, correlations, and other patterns.
3. Feature Engineering: Creating new features and selecting the most relevant ones.
4. Model Training and Evaluation: Training models like CatBoost, XGBoost, and LightGBM, and evaluating their performance using ROC-AUC score, confusion matrix, and other metrics.
5. Fairness and Bias Analysis: Assessing model fairness across different subpopulations.

Results

The models are evaluated based on their ability to predict loan defaults accurately. We use metrics like ROC-AUC, confusion matrices, and fairness indicators to assess performance.
