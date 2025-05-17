# Business Case – OLA | Predicting Driver Attrition Using Ensemble Learning

This project tackles the real-world business problem of high driver churn at OLA, a leading ride-sharing company in India. The goal is to build a predictive model using ensemble learning techniques that can identify drivers likely to leave, enabling OLA to implement effective retention strategies.

---

## 📌 Problem Statement

> Recruiting and retaining drivers is a major challenge for OLA. High attrition increases costs and impacts service quality. Using data from 2019–2020, we aim to predict whether a driver will leave the company based on demographics, performance, income trends, and job history.

---

## 📂 Dataset

The dataset contains monthly-level information for each driver:
- **Demographics**: Age, Gender, City, Education
- **Performance**: Income, Quarterly Ratings, Business Value
- **Tenure**: Date of Joining, Last Working Date
- **Behavioral Signals**: Changes in ratings, income trends, etc.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn**, **XGBoost**, **LightGBM** for modeling
- **KNN Imputation** for missing value treatment
- **SMOTE** for handling class imbalance
- **Jupyter Notebook**

---

## 🧪 Key Steps in the Workflow

1. **Exploratory Data Analysis**
2. **Feature Engineering**
   - Income & rating change trends
   - Target variable creation (based on LastWorkingDate)
3. **Data Cleaning & Imputation**
4. **Class Balancing**
5. **Model Building**
   - Random Forest (Bagging)
   - XGBoost / LightGBM (Boosting)
6. **Evaluation**
   - ROC AUC Score
   - Classification Report

---

## 📊 Results & Insights

- Ensemble models provided significant lift over baseline classifiers
- Drivers with declining income and low ratings were more likely to churn
- Early warning scores can be generated to flag at-risk drivers

---

## 🚀 Getting Started

Clone the repo:
```bash
git clone https://github.com/varshilgandhi/Business-Case-OLA-Driver-Attrition-Prediction.git
cd Business-Case-OLA-Driver-Attrition-Prediction
