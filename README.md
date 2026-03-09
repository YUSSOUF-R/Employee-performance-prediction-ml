# Employee Performance Prediction Using Machine Learning

## Project Overview

This project builds a machine learning model to predict employee performance levels using HR analytics data.

The objective is to help organizations identify key factors that influence employee performance and assist HR departments in improving workforce productivity.

---

# Problem Statement

Organizations often struggle to evaluate employee performance consistently.

By analyzing historical HR data, we can build a predictive model that classifies employee performance into categories such as:

Low Performance
Medium Performance
High Performance

This allows HR teams to better understand workforce dynamics and improve management strategies.

---

# Dataset

The dataset contains HR-related attributes for employees including:

Demographic information

* Age
* Gender
* Education
* Marital Status

Job-related attributes

* Department
* Job Role
* Job Level
* Work Experience

Work environment factors

* Environment Satisfaction
* Job Satisfaction
* Work-Life Balance
* Relationship Satisfaction

Performance indicators

* Training times
* Salary hike
* Years at company

Target Variable:

Employee Performance Rating

---

# Project Workflow

## 1 Data Exploration

Exploratory Data Analysis (EDA) was performed to understand the dataset.

Key tasks included:

* inspecting feature distributions
* identifying correlations
* detecting class imbalance
* visualizing relationships between features and performance rating

---

## 2 Data Processing

Data preprocessing included:

* handling missing values
* encoding categorical variables
* feature engineering
* scaling numerical features

The processed dataset was saved for model training.

---

## 3 Data Visualization

Visualization notebooks were created to explore:

* employee demographics
* department performance distribution
* satisfaction level trends
* feature importance patterns

These visual insights help understand which factors influence employee performance.

---

## 4 Model Training

Multiple classification models were trained to predict employee performance.

Algorithms tested include:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

These models were evaluated using cross-validation.

---

## 5 Model Prediction

The trained model is used to predict employee performance categories for unseen data.

Predictions help HR teams identify employees who may need additional support or training.

---

# Model Evaluation

Models were evaluated using standard classification metrics:

Accuracy
Precision
Recall
F1 Score

These metrics help measure how well the model predicts employee performance.

---

# Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost

---

# Project Structure

employee-performance-prediction-ml
│

├── data

│   ├── INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls

│   └── employee_performance_processed.csv

├── notebooks

│   ├── data_exploratory_analysis.ipynb

│   ├── data_processing.ipynb

│   ├── visualize.ipynb

│   ├── train_model.ipynb

│   └── predict_model.ipynb

├── requirements.txt

└── README.md

---

# Key Insights

Employee satisfaction and work environment factors strongly influence performance ratings.

Training opportunities and experience level also play an important role in employee productivity.

Machine learning models can effectively identify patterns that influence employee performance.

---

# Author

Yussouf R
Machine Learning Project

