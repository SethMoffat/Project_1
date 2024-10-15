# Employee Churn Prediction Model 

## Project Overview
This project focuses on building an AI model to predict employee churn based on factors like **age**, **monthly income**, and **department**. The goal is to analyze historical employee data to determine patterns and key predictors of churn, enabling the company to proactively retain employees who are at risk of leaving. 

## Dataset 
The dataset used contains **1,470 employee records** and **35 features** related to demographics, job roles, satisfaction levels, and churn status. The key columns used in the model include:
- **Age**: Age of the employee.
- **MonthlyIncome**: Employee's monthly salary.
- **Department**: Department in which the employee works.
- **Attrition**: Whether the employee has left the company (Yes/No).

- ## Data Cleaning and Preprocessing
1. **Handling Missing Data**: Ensured that there are no missing values in the dataset.
2. **Feature Engineering**: Created new features such as `AgeGroup` by binning the age into categories: 18-25, 26-35, 36-45, 46-55, 56-65.
3. **Categorical Encoding**: Converted categorical columns (like `Department`) into numerical representations using one-hot encoding.

## Visualizations
The following visualizations were created to better understand the relationships between features and churn:
- **Churn Rate by Age Group and Department**: A bar plot showing the average churn rate across different age groups within each department.
- **Age Distribution vs. Churn**: A histogram showing how churn rates vary across different age groups.
- **Churn Rate by Monthly Income**: A scatter plot visualizing how monthly income influences the likelihood of churn.

- ## Acknowledgements
- Thank you to my partners Seth Moffat, Roger Navarro, and Tahir Pervez. The group used.[this H.R. Analytics Dataset from Kaggle].(https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) 
