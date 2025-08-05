# 👨‍💼 Employee Attrition Prediction

This project analyzes employee data to explore the factors that influence employee attrition (i.e., leaving the company). It includes data exploration, visualizations, and machine learning model training to predict whether an employee is likely to leave or stay.

---

## 📌 Problem Statement

The goal of this project is to understand the key factors that contribute to employee attrition using real-world HR data. The project involves analyzing trends, creating visualizations, and building classification models to predict employee attrition.

---

## 🎯 Project Objectives

- Explore the dataset and identify patterns related to employee turnover.
- Visualize important trends using graphs and statistical summaries.
- Build and evaluate machine learning models to predict attrition.

---

## 📂 Dataset

- 📥 **Source**: [IBM HR Analytics Attrition Dataset on Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- 🎯 **Target Column**: `Attrition` (Yes = Employee Left, No = Employee Stayed)

The dataset contains various features such as:
- Age, Gender, Department, DistanceFromHome
- MonthlyIncome, JobSatisfaction, OverTime
- YearsAtCompany, JobRole, and more

---

## 📊 Exploratory Data Analysis (EDA)

This part of the project answers the following questions:

1. Total number of employees and those who left.
2. Average age comparison (left vs stayed).
3. Attrition rate by department.
4. Correlation between distance from home and attrition.
5. Relationship between overtime and attrition.
6. Impact of monthly income on attrition.
7. Any missing values in the dataset.

---

## 📈 Visualizations

- ✅ Bar chart: Count of employees by Attrition
- ✅ Boxplot: Monthly Income vs Attrition
- ✅ Histogram: Age distribution by Attrition
- ✅ Stacked bar chart: Department vs Attrition
- ✅ Countplot: Job Satisfaction by Attrition
- ✅ Heatmap: Correlation matrix for numerical features

---

## 🤖 Machine Learning

### ✅ Process:
1. Encoded categorical variables using OneHotEncoding.
2. Defined features (X) and target variable (y).
3. Performed an 80/20 Train-Test split.
4. Trained two models:
   - Logistic Regression
   - Random Forest Classifier
5. Evaluated the models using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
   - ROC Curve and AUC

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📁 Project Structure

Employee_Attrition_Prediction/
│
├── Employee_Attrition_prediction.ipynb # Main Jupyter Notebook
├── README.md # Project documentation

---

## ✅ Key Insights

- Overtime, low monthly income, and low job satisfaction are major indicators of attrition.
- Employees with longer tenure and higher satisfaction tend to stay longer.
- Random Forest slightly outperformed Logistic Regression in prediction accuracy.

---

## 📘 Conclusion

This project provides insight into the causes of employee attrition using data analysis and predictive modeling. The results can help HR departments make informed decisions about employee engagement and retention strategies.

---

## 🙋‍♀️ Author

**Zuha M. Ismail**  
BS Software Engineering Student
