# titanic-survival-prediction
Titanic Survival Prediction
Project Overview
This project tackles the classic Kaggle Titanic competition challenge: predicting whether a passenger survived the Titanic shipwreck based on various features such as age, sex, passenger class, and more. The goal is to build machine learning models that effectively classify passengers' survival chances, aiming to maximize prediction accuracy.

Dataset
The dataset consists of two CSV files:

train.csv: Contains labeled data with features and survival outcomes.

test.csv: Contains passenger features without survival labels, used for prediction submission.

Key features include:

PassengerId

Pclass (Ticket class)

Name

Sex

Age

SibSp (Number of siblings/spouses aboard)

Parch (Number of parents/children aboard)

Ticket

Fare

Cabin

Embarked (Port of Embarkation)

Data Preprocessing
Combined training and test datasets to streamline preprocessing.

Handled missing values (e.g., Age, Embarked).

Dropped irrelevant columns like Name and Cabin for model efficiency.

Encoded categorical variables (Sex, Ticket, Embarked) using label encoding.

Created new features such as Family_Size to capture family-related survival patterns.

Modeling
Implemented multiple classification algorithms:

Logistic Regression

Random Forest Classifier

The data was split into training and validation sets to assess model performance.

Results
Achieved approximately 80% accuracy on validation data.

Evaluated models based on accuracy score and confusion matrix.

Usage
Clone the repository.

Install required libraries (pandas, numpy, scikit-learn, seaborn, matplotlib).

Run the preprocessing script to clean and prepare data.

Train models using the provided scripts.

Generate predictions on test data for Kaggle submission.

Future Work
Experiment with hyperparameter tuning to improve accuracy.

Try advanced models like Gradient Boosting, XGBoost, or neural networks.

Perform feature importance analysis and additional feature engineering.

Handle missing data with imputation techniques.

Resources
Kaggle Titanic competition: https://www.kaggle.com/c/titanic

Documentation for scikit-learn and seaborn for modeling and visualization.

