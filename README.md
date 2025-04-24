# Telco Customer Churn Analysis

This repository contains an end-to-end data analysis and machine learning project focused on customer churn prediction using the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The project explores customer behavior to determine key factors contributing to churn and builds a model to predict customer retention.

## 📊 Dataset

- **Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Description**: The dataset includes information about a telecom company's customers, such as demographic info, account details, services used, and whether or not the customer has churned.
- **Target Variable**: `Churn` (Yes/No)
- **Size**: 7,043 rows × 21 columns

## 🛠️ Project Structure

- `Telco.ipynb`: The main Jupyter Notebook for data exploration, preprocessing, model building, and evaluation.
- `README.md`: This file.
- `TCC.csv`: The cleaned Telco Customer Churn dataset used for analysis.
- `encoded.pkl`: Serialized version of preprocessed/encoded data.
- `requirements.txt`: Contains a list of required Python packages for running the notebook.
- `.ipynb_checkpoints/`: Auto-generated Jupyter folder for backup checkpoints (can be ignored or added to .gitignore).
  

## 🔍 Key Steps Covered

1. **Data Cleaning**: Handling missing values, converting data types, and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Visualizing churn distributions, service usage, and demographic patterns.
3. **Feature Engineering**: Creating new features and selecting relevant ones.
4. **Modeling**: Building and evaluating classification models (e.g., Logistic Regression, Random Forest, etc.).
5. **Performance Evaluation**: Using accuracy, precision, recall, F1 score, and confusion matrix to assess models.

## 📈 Results

The Random Forest model achieved high accuracy and balanced precision/recall on the test set, making it a reliable predictor for customer churn.

## 🧰 Requirements

To run the notebook, make sure you have the following Python packages installed:

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
