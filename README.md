# German Credit Risk Analysis

## Overview

This project predicts whether a customer is a **Good Credit Risk** or **Bad Credit Risk** using Machine Learning algorithms. The German Credit Dataset is analyzed through data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and model evaluation.

---

## Project Objectives

- Analyze customer credit data.
- Perform data cleaning and preprocessing.
- Explore the dataset using visualizations.
- Build and compare multiple Machine Learning models.
- Evaluate model performance using different metrics.
- Predict customer credit risk accurately.

---

## Dataset

**Dataset:** German Credit Dataset

**Target Variable:** Credit Risk (Good / Bad)

### Features

- Age
- Sex
- Job
- Housing
- Saving Accounts
- Checking Account
- Credit Amount
- Duration
- Purpose

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Tkinter

---

## Machine Learning Models

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- AdaBoost Classifier

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning & Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Feature Encoding & Scaling
7. Train-Test Split
8. Model Training
9. Hyperparameter Tuning
10. Model Evaluation
11. Credit Risk Prediction
12. Tkinter GUI Application

---

## Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross Validation Score

---

## Results

Among the implemented machine learning models, the **Random Forest Classifier** achieved the best overall performance for predicting customer credit risk.

---

## Application Preview

### Tkinter Desktop Application

A simple desktop application was developed using **Tkinter** to provide an interactive interface for predicting customer credit risk. Users can enter customer information and receive an instant prediction of whether the customer is a **Good Credit Risk** or **Bad Credit Risk** using the trained Machine Learning model.

![Tkinter Application](screenshots/Credit_Risk.png)
---

## Project Structure

```text
German-Credit-Risk-Analysis/
│
├── German_Credit_Risk_Analysis.ipynb
├── german_credit_data.csv
├── README.md
└── screenshots/
    └── Credit_Risk.png

---

## Installation

Clone the repository:

```bash
git clone https://github.com/fasnafaizal777-crypto/German-Credit-Risk-Analysis.git
```

Move to the project folder:

```bash
cd German-Credit-Risk-Analysis
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- Improve model prediction accuracy.
- Add ROC Curve and AUC Score.
- Save the trained model using Joblib.
- Deploy the application using Streamlit or Flask.
- Improve the graphical user interface.

---

## Author

**Fathimathul Fasna**

**B.Voc Data Science & Analytics**

**Aspiring Data Analyst | Machine Learning Enthusiast**

GitHub: https://github.com/fasnafaizal777-crypto

---

## License

This project is developed for educational and learning purposes.
