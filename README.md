# credit-default-prediction

# Predictive Analysis of Credit Card Default Using Machine Learning Techniques

This repository contains the code and documentation for the **Predictive Analysis of Credit Card Default Using Machine Learning Techniques** project, completed as part of **AIT 582-DL1: Applications of Metadata in Complex Big Data Problems** at George Mason University.

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Models Used](#models-used)
- [Results](#results)
- [Challenges](#challenges)
- [Future Work](#future-work)
- [Team](#team)
- [Project Website](#project-website)

---

## 🧠 Project Overview

The objective of this project is to address the growing issue of credit card defaults amid increasing global usage. Accurate prediction of potential defaulters is vital for financial institutions to reduce risk, improve stability, and encourage responsible lending. This project enhances credit risk assessment using machine learning techniques.

---

## 📊 Dataset

We used the **UCI Machine Learning Repository** dataset titled "Default of Credit Card Clients Dataset", containing information about 30,000 credit card users from April to September 2005.

- **Attributes**: 24 variables including demographics, credit data, and repayment history.
- **Target**: `default.payment.next.month` (1 = default, 0 = not default)

### Key Features:
- `LIMIT_BAL`: Credit limit
- `SEX`, `EDUCATION`, `MARRIAGE`, `AGE`: Demographics
- `PAY_0` to `PAY_6`: Past monthly repayment status
- `BILL_AMT1` to `BILL_AMT6`: Monthly bill amounts
- `PAY_AMT1` to `PAY_AMT6`: Monthly payments made

---

## 🔍 Methodology

We followed a structured pipeline:

1. **Data Preprocessing**: Cleaned data and handled missing/inconsistent values.
2. **Exploratory Data Analysis (EDA)**: Identified patterns and correlations.
3. **Class Imbalance Handling**: Used SMOTE to oversample the minority class (defaulters).
4. **Feature Engineering**: Created new features to enhance model performance.
5. **Model Training**: Applied multiple machine learning algorithms.

---

## 🛠️ Models Used

We implemented and evaluated the following models:

- Logistic Regression
- Naïve Bayes
- Random Forest
- XGBoost

---

## 📈 Results

- **Random Forest**: Achieved an accuracy of **80.41%**
- **XGBoost**:
  - Precision (Non-Defaulters): **0.78**
  - Precision (Defaulters): **0.83**

These results show promise in real-world predictive credit risk modeling.

---

## 🚧 Challenges

1. **Handling Class Imbalance**: Few default cases skewed model training.
2. **Model Interpretability**: Translating complex predictions into actionable insights.
3. **Avoiding Overfitting**: Ensuring generalization on unseen data.
4. **Data Complexity**: Managing 30,000 records with 24 attributes.

---

## 🔮 Future Work

- **Deep Learning Models**: Explore neural networks and hybrid ensembles.
- **Expanded Data Sources**: Integrate social and behavioral data.
- **Real-Time Prediction**: Build systems for live credit risk scoring.

---

## 👥 Team

- **Shashank Yelagandula** 
- **Shivani Gangarapollu** 
- **Akhil Reddy Chimmula** 
- **Bhavesh Kurella** 

---

## 🔗 Project Website

👉 [Project Web Page](https://mason.gmu.edu/~bkurella/Team%209)

---

## 📁 License

This project is for academic purposes only and licensed under the MIT License.

