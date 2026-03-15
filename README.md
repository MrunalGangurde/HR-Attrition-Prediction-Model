# 📊 HR Attrition Prediction Model

## Overview
Employee attrition is a major challenge for organizations. This project analyzes employee data to identify the key factors contributing to attrition and builds machine learning models to predict employees at risk of leaving.

The goal is to support **HR teams in making data-driven decisions to improve employee retention.**

---

## Dataset
- **Source:** IBM HR Analytics Dataset  
- **Target Variable:** Attrition (Yes / No)  
- **Features:** 35+ variables including:
  - Demographics
  - Job role
  - Salary
  - Work environment
  - Performance metrics

---

## Project Workflow

### 1️⃣ Data Preprocessing
- Data cleaning and handling missing values  
- Encoding categorical variables  
- Feature engineering (e.g., experience and promotion metrics)  
- Outlier detection using **IQR method**  
- Feature scaling using **StandardScaler**

---

### 2️⃣ Handling Class Imbalance
- Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset.

---

### 3️⃣ Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features  
- Attrition analysis by gender and job role  
- Correlation heatmap to identify feature relationships

---

### 4️⃣ Machine Learning Models
The following models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## Model Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## Results

🏆 **Best Model:** Random Forest Classifier  

- **Accuracy:** 93.5%  
- **ROC-AUC:** 98.07%

---

## Key Insights

- Employees working frequent **overtime** are more likely to leave.  
- **Job satisfaction and career growth opportunities** strongly influence retention.  
- Salary progression relative to peers affects attrition risk.

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- SMOTE

---

## Future Improvements

- Implement **deep learning models** for improved predictions  
- Integrate **employee sentiment analysis** from feedback or reviews  
- Build a **dashboard for real-time attrition monitoring**

---

## Author

**Mrunal Gangurde**  
Data Analyst | MSc Data Science @ University of Leicester

---

⭐ If you found this project useful, feel free to star the repository!
