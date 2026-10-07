# Employee Attrition Prediction

An end-to-end Machine Learning project that predicts whether an employee is likely to leave a company.

## 📌 Project Overview

Employee attrition is an important business problem. The goal of this project is to build a machine learning model that can predict employee attrition based on factors such as:

- Age
- Monthly Income
- Job Level
- Job Satisfaction
- Overtime
- Years at Company
- Years in Current Role
- Distance From Home
- and other employee-related features

## 🎯 Objective

Build a machine learning classification model to predict:

- `0` → Employee stays
- `1` → Employee leaves

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Joblib

## 🔍 Project Workflow

```text
Dataset
   ↓
Exploratory Data Analysis
   ↓
Data Cleaning
   ↓
Feature Selection
   ↓
Train/Test Split
   ↓
Preprocessing Pipeline
   ↓
Logistic Regression
   ↓
Random Forest
   ↓
Model Evaluation
   ↓
Cross Validation
   ↓
Hyperparameter Tuning
   ↓
Feature Importance
   ↓
Employee Prediction
```

## 🤖 Models Used

### Logistic Regression

Used as a baseline classification model.

### Random Forest

Used as a more powerful ensemble model and tuned using GridSearchCV.

## 📊 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

Because employee attrition is an imbalanced classification problem, accuracy alone was not used to evaluate the models.

## 🔧 Hyperparameter Tuning

Random Forest was tuned using 5-fold cross-validation.

Parameters considered included:

- `n_estimators`
- `max_depth`
- `min_samples_split`

## 📈 Feature Importance

Random Forest feature importance was used to identify which employee characteristics were most useful for predicting attrition.

## 📁 Project Structure

```text
employee-attrition-prediction/
│
├── employee_attrition.ipynb
└── README.md
```

## 🚀 Future Improvements

- Build a web interface for predictions
- Deploy the model using FastAPI
- Add more advanced models
- Improve handling of class imbalance
- Create an interactive dashboard

## 👨‍💻 Author

Machine Learning project built as part of my AI / Data Science learning journey.
