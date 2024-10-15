# Project 1
## Decision Tree Model
### Overview 
In this project, we will be building a decision tree model that will predict the
probability of an employee churning. This group used the HR Analytics dataset
 found on Kaggle.

 ### Dataset
The dataset used contains **1,470 employee records** and **35 features** related to demographics, job roles, satisfaction levels, and churn status. The key columns used in the model include:
- **Age**: Age of the employee.
- **MonthlyIncome**: Employee's monthly salary.
- **Department**: Department in which the employee works.
- **Attrition**: Whether the employee has left the company (Yes/No).

- The **Churn** column is derived from **Attrition**, where `1` indicates that the employee has left, and `0` means they stayed.

### Data Cleaning and Preprocessing
1. **Handling Missing Data**: Ensured that there are no missing values in the dataset.
2. **Feature Engineering**: Created new features such as `AgeGroup` by binning the age into categories: 18-25, 26-35, 36-45, 46-55, 56-65.
3. **Categorical Encoding**: Converted categorical columns (like `Department`) into numerical representations using one-hot encoding.

### Visualizations
The following visualizations were created to better understand the relationships between features and churn:
- **Churn Rate by Age Group and Department**: A bar plot showing the average churn rate across different age groups within each department.
- **Age Distribution vs. Churn**: A histogram showing how churn rates vary across different age groups.
- **Churn Rate by Monthly Income**: A scatter plot visualizing how monthly income influences the likelihood of churn.

   
    
 ### Getting Started
 To get started, follow these steps:

 Step 1. Install the required dependencies, including pandas, scikit-learn, 
 seaborn, and matpltlib.

 Step 2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/anshika2301/hr-analytics-dataset/data)

 ### Acknowledgments 

 This project was made possible by the contributions of the following individuals: Tahir Pervez, Seth Moffat, Steven Sarvas, and Roger Navarro. A special thanks to Fahad Rehman, Max Polyakov, Zeynel, and the Kaggle community for providing the dataset. We would like to thank Firas Obeid, Kevin Nguyen, Wendell White, and the entire edX Boot Camps team for their support. 
