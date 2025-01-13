# HR-Attrition-Prediction-Model
Introduction
Employee attrition, or turnover, is a challenge faced by organizations globally. Retaining top talent requires understanding the factors contributing to attrition. This project analyzes employee attrition using a fictional dataset provided by IBM data scientists, implementing advanced data analysis and machine learning techniques.

Project Objectives
Understand employee attrition factors.
Create predictive models to identify high-risk employees.
Generate insights for HR decision-making.
Dataset
Source: IBM fictional HR dataset.
Target Variable: Attrition (Yes/No).
Features: 35+ columns including demographics, job role, salary, and performance metrics.
Prerequisites
Ensure the following libraries are installed:

Workflow
1. Data Preprocessing
Loading Dataset: The dataset is loaded and initial exploration is conducted.

Handling Missing Values: Imputation and handling of null entries.

Encoding Categorical Variables: Using LabelEncoder and mapping for better compatibility.

Feature Engineering: Creating new features to enhance predictive power:

TotalExperience, PromotionFrequency, and interaction terms.

Outlier Detection: Using the IQR method to identify anomalies.

Scaling: StandardScaler is applied for normalization.

3. Balancing Data

SMOTE: Addressing class imbalance in the target variable (Attrition).

4. Exploratory Data Analysis (EDA)

Visualizations:

Histograms for numerical features.

Attrition breakdown by gender.

Correlation Analysis: Identifying relationships among features.

5. Model Building

Models Evaluated:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Model Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

6. Visualization

ROC Curve Comparison: Evaluate model performance.

Confusion Matrix: Analyze classification outcomes.

Results

Best Performing Model: Random Forest Classifier with 93.5% accuracy and 98.07% ROC-AUC score.

Insights:

Employees with frequent overtime and lower satisfaction are at higher risk of attrition.


Career progression and salary relative to peers significantly impact retention.


Future Work

Incorporate deep learning models.

Extend analysis to include sentiment analysis from employee reviews.

Build a dashboard for real-time attrition prediction.

License

This project is licensed under the GNU General Public License v3.0. See LICENSE for details.


Contributors

Mrunal Gangurde

Feel free to reach out for collaboration or queries!

