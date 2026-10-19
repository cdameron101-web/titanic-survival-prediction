# Titanic Survival Prediction — Logistic Regression

## Project Overview

A machine learning project developed by **Blacksheep Labs** to predict whether passengers survived the Titanic disaster using Python and logistic regression.

The project includes exploratory data analysis, data preparation, model training, and performance evaluation.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab

## Dataset

The Titanic dataset contains 887 passenger records with information about:

- Passenger class
- Sex
- Age
- Number of siblings and spouses aboard
- Number of parents and children aboard
- Ticket fare
- Survival status

## Project Workflow

1. Loaded and explored the Titanic dataset.
2. Checked for missing values and potential outliers.
3. Analyzed survival rates by sex and passenger class.
4. Converted categorical data into numerical features.
5. Split the dataset into 80% training and 20% testing.
6. Trained a logistic regression model using a Scikit-learn pipeline.
7. Evaluated the model using classification metrics and a confusion matrix.

## Model Performance

| Metric | Result |
|---|---|
| Accuracy | 76.97% |
| Precision | 71.21% |
| Recall | 68.12% |
| F1-score | 69.63% |

The model correctly classified approximately 77% of passengers in the held-out test dataset.

## Key Findings

- Female passengers had a higher survival rate (74.20%) than male passengers (19.02%).
- First-class passengers had the highest survival rate (62.96%).
- Third-class passengers had the lowest survival rate (24.44%).
- Passenger sex and class were useful features to investigate when predicting survival.

## Limitations and Future Improvements

This project is an initial logistic regression model rather than a production-ready prediction system.

Future improvements could include cross-validation, hyperparameter tuning, additional feature engineering, and comparisons with other classification algorithms.

## Author

**Blacksheep Labs**

Python | Machine Learning | Data Analysis
