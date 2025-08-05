# 👨‍💼 Employee Attrition Prediction

This project explores employee attrition using the IBM HR Analytics dataset. The aim is to identify patterns and factors influencing employees' decisions to leave the company, and to build predictive models that help HR teams anticipate and reduce turnover.

---

## 📌 Problem Statement

As a data analyst, your task is to analyze employee data and uncover the key reasons behind attrition. After the exploratory analysis, you will develop machine learning models to predict whether an employee is likely to leave or stay.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) to understand attrition drivers.
- Visualize important trends using charts and heatmaps.
- Build and evaluate classification models to predict employee attrition.

---

## 📂 Dataset

- 📥 **Source**: [IBM HR Analytics Attrition Dataset on Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- 🎯 **Target Variable**: `Attrition` (Yes = Employee Left, No = Employee Stayed)

Each row represents an individual employee with details such as:
- Age, Gender, Department, MonthlyIncome
- JobSatisfaction, OverTime, DistanceFromHome
- YearsAtCompany, JobRole, and more

---

## 📊 Part 1: Exploratory Data Analysis (EDA)

Questions answered:
1. Total number of employees and those who left.
2. Average age comparison between leavers and stayers.
3. Attrition rate across departments.
4. Correlation between distance from home and attrition.
5. Impact of overtime on attrition.
6. Relationship between income and attrition.
7. Missing values analysis.

---

## 📈 Part 2: Visualizations

The following plots were created to visualize trends:
- ✅ Bar chart: Employee count by Attrition
- ✅ Boxplot: Monthly Income vs Attrition
- ✅ Histogram: Age distribution by Attrition
- ✅ Stacked bar chart: Department vs Attrition
- ✅ Countplot: Job Satisfaction by Attrition
- ✅ Heatmap: Correlation between numeric variables

---

## 🤖 Part 3: Machine Learning

### ✅ Steps:
1. Encoded categorical variables (OneHotEncoder)
2. Prepared features (X) and target (y)
3. Split the data into training and test sets (80/20)
4. Trained two classification models:
   - Logistic Regression
   - Random Forest
5. Evaluated models using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
   - ROC Curve and AUC

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**

---

## 📁 Project Structure

Employee_Attrition_Prediction/
│
├── Employee_Attrition_prediction.ipynb # Main Jupyter Notebook
├── README.md # Project documentation


---

## ✅ Key Insights

- Employees who work **overtime** and earn **lower income** are more likely to leave.
- **JobSatisfaction**, **YearsAtCompany**, and **WorkLifeBalance** also impact attrition.
- Random Forest provided slightly better predictive performance than Logistic Regression.

---

## 🧾 Conclusion

This project demonstrates how data analysis and machine learning can be used to tackle real-world HR problems. Predicting employee attrition can help companies retain top talent by identifying at-risk employees early.

---

## 🙋‍♀️ Author

**Zuha M. Ismail**  
BS Software Engineering Student
## 📁 Project Structure

