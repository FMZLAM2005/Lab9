# Lab9

# Random Forest Classification Project

## Overview
This project applies Decision Tree and Random Forest classification techniques on LendingClub loan data to predict whether a borrower will fully repay a loan.

The dataset contains financial and credit-related information collected from LendingClub between 2007 and 2010.

## Dataset Features
The dataset includes features such as:
- Credit Policy
- Loan Purpose
- Interest Rate
- Installment
- Annual Income
- Debt-to-Income Ratio
- FICO Score
- Revolving Balance
- Revolving Utilization
- Public Records
- Not Fully Paid (Target Variable)

## Tasks Performed

### 1. Data Exploration
Used:
- head()
- info()
- describe()

to understand the dataset structure and features.

### 2. Exploratory Data Analysis (EDA)
Created several visualizations including:
- FICO score histograms
- Countplots
- Jointplots
- Regression plots (lmplot)

to analyze relationships between variables.

### 3. Handling Categorical Features
- Converted the `purpose` categorical column into dummy variables using `pd.get_dummies()`

### 4. Data Preparation
- Defined feature variables (X) and target variable (y)
- Split the dataset into training and testing sets

### 5. Decision Tree Model
- Trained a DecisionTreeClassifier model
- Evaluated model performance using:
  - Classification Report
  - Confusion Matrix

### 6. Random Forest Model
- Trained a RandomForestClassifier model with 600 estimators
- Generated predictions on testing data
- Evaluated performance using:
  - Classification Report
  - Confusion Matrix

## Results
- The Random Forest model achieved higher overall accuracy compared to the Decision Tree model.
- Random Forest performed better in predicting loan repayment outcomes and reduced overfitting.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
