# Income-prediction-census
"A machine learning project predicting income level (>50k) using UCI Census data."

This project aims to predict an individual's income based on various demographic features extracted from census data. The model uses machine learning techniques to classify individuals into income groups (e.g., <=50K or >50K) based on features such as age, education, occupation, and more.

Project Overview
The goal of this project is to build a predictive model that can estimate whether an individual's income exceeds $50K per year based on their demographic information. This is a binary classification problem, where the target variable is the income class (<=50K or >50K).

The project uses the well-known Census Income Dataset from the UCI Machine Learning Repository. The dataset includes attributes like age, workclass, education, marital status, occupation, hours worked per week, and more.

Dataset
The dataset consists of both continuous and categorical features, which are used to predict whether an individual earns more or less than 50K annually. It contains the following columns:

age: Age of the individual
workclass: Type of employment (e.g., private, self-employed)
fnlwgt: Final weight (related to the dataset)
education: Highest level of education
education-num: Number of years of education
marital-status: Marital status of the individual
occupation: Occupation type
relationship: Relationship status
race: Ethnicity
sex: Gender
capital-gain: Capital gain from investments
capital-loss: Capital loss from investments
hours-per-week: Average number of hours worked per week
native-country: Country of origin
income: Income class (<=50K, >50K) – the target variable
Key Features
Machine Learning Models: This project explores several machine learning algorithms such as Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines (SVM).
Data Preprocessing: It includes handling missing values, encoding categorical variables, feature scaling, and splitting the dataset into training and testing sets.
Model Evaluation: The models are evaluated based on metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
Technologies Used
Python
Pandas (for data manipulation)
NumPy (for numerical operations)
Scikit-learn (for machine learning algorithms and evaluation)
Matplotlib and Seaborn (for data visualization)
Jupyter Notebook (for development and documentation)
