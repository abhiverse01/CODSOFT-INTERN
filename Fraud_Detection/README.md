# Credit Card Fraud Detection

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used for this project is highly imbalanced, with a small percentage of fraudulent transactions.

## Dataset
The dataset contains the following features:
- Time: Number of seconds elapsed between this transaction and the first transaction in the dataset.
- V1-V28: Result of a PCA transformation.
- Amount: Transaction amount.
- Class: Class label (1 for fraudulent transactions, 0 otherwise).

## Project Steps
1. Data Preprocessing:
    - Handling missing values.
    - Feature scaling.
    - Balancing the dataset using techniques like SMOTE.

2. Exploratory Data Analysis (EDA):
    - Visualizing the distribution of the data.
    - Analyzing correlations between features.

3. Model Building:
    - Training various machine learning models like Logistic Regression, Decision Trees, and Random Forest.
    - Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.

4. Model Evaluation:
    - Comparing different models.
    - Selecting the best model based on evaluation metrics.

## Usage
To run this project, ensure you have the required packages installed and execute the notebook.

## Requirements
Refer to the `requirements.txt` file for a list of dependencies.
