# TechWorks-Consulting-Machine-Learning-Model
**Overview**
This project is a part of my Data Science training (Internshala) and aims to help TechWorks Consulting predict the salaries of newly hired employees using machine learning regression techniques. The primary goal is to create a robust predictive model that considers various employee features, such as previous experience, education, job role, and location, to provide accurate salary predictions.

**Problem Statement**
TechWorks Consulting specializes in staffing IT professionals for various businesses. To maintain competitive and fair compensation, they need a model to predict the salary of newly hired employees based on a variety of factors. These factors include the employee's educational background, city, previous job experience, and CTC, among others.

The objective is to develop a regression model that can predict employee salaries based on historical data and provide insights into how various factors affect salary determination.

**Data**
The dataset contains 8 columns:

College name: Coded into three tiers—Tier1, Tier2, and Tier3, with Tier1 having the highest weightage.
City: Categorical feature with two types—metro and non-metro cities, converted to numerical values (0 for non-metro, 1 for metro).
Role: Categorical feature for job role, converted to numerical using dummy variables (e.g., Manager, Executive).
Previous CTC: Salary from the employee’s previous job.
Previous Job Change: Indicates whether the employee has changed jobs previously.
Graduation marks: Marks obtained during the employee's graduation.
Experience in Months: Total work experience in months.
CTC: Current salary (target variable for prediction).
Approach
The project follows these key steps:

**Data Preprocessing:**
Handle missing values and outliers.

Convert categorical variables like College, City, and Role into numerical or dummy variables.

Normalize or scale the data as needed.

**Modeling:**
Multiple regression models are tested, including:

**Linear Regression**

**Decision Tree Regression**

**Random Forest Regression**

**Gradient Boosting and XGBoost**

The final model is selected based on performance metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.

**Feature Selection:**

Feature importance is determined to understand which factors have the greatest impact on salary prediction.

**Model Evaluation:**

Use of statistical techniques like cross-validation to ensure the robustness and reliability of the model.
Tools & Technologies

Python (Jupyter Notebook)

Pandas, NumPy for data manipulation

Scikit-learn for model training and evaluation

Matplotlib/Seaborn for visualizations

**Conclusion**
The selected regression model is chosen based on its accuracy and interpretability. The project demonstrates how machine learning can be applied to predict employee salaries, providing fair and data-driven compensation strategies for TechWorks Consulting.

Author
Omkar Rajpure
