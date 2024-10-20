# Attrition-Forecast-Analysis-and-Prediction
This project focuses on analyzing employee attrition and building predictive models to forecast future attrition rates. By understanding the factors influencing employee turnover, we aim to provide actionable insights to improve employee retention strategies.
## Project Overview
Employee attrition is a significant concern for many organizations as it impacts productivity, morale, and costs. This project aims to analyze historical employee data to identify key factors influencing attrition and to build predictive models that can help forecast future attrition rates.
## Dataset:
This dataset spans the last five years and includes information on employees who have left the company and those who are still currently employed.
here's a general list of common features you might find in such a dataset:

1-Employee ID: A unique identifier for each employee.

2-Age: The age of the employee.

3-Attrition: A binary variable indicating whether the employee has left the company (1) or is still employed (0).

4-Business Travel: The frequency and nature of business-related travel (e.g., "Travel_Rarely," "Travel_Frequently," "Non-Travel").

5-Department: The department to which the employee belongs (e.g., "Sales," "Research & Development," "Human Resources").

6-Distance From Home: The distance of the employee's residence from the workplace.

7-Education: The employee's level of education (e.g., "1: 'Below College'," "2: 'College'," "3: 'Bachelor'," "4: 'Master'," "5: 'Doctor').

8-Education Field: The field in which the employee's education lies (e.g., "Life Sciences," "Medical," "Marketing").

9-Environment Satisfaction: The level of satisfaction with the work environment on a scale.

10-Gender: The gender of the employee.

11-Job Involvement: The degree to which the employee is involved in their job.

12-Job Level: The level or rank of the employee's position.

13-Job Role: The specific role or title of the employee's job.

14-Job Satisfaction: The level of satisfaction with the job on a scale.

15-Marital Status: The marital status of the employee.

16-Monthly Income: The monthly salary of the employee.

17-Num Companies Worked: The number of companies the employee has worked for.

18-Over Time: Whether the employee works overtime or not.

19-Performance Rating: The performance rating of the employee.

20-Relationship Satisfaction: The level of satisfaction with relationships at the workplace.

21-Stock Option Level: The level of stock options provided to the employee.

22-Total Working Years: The total number of years the employee has been working.

23-Training Times Last Year: The number of training sessions the employee attended last year.

24-Work-Life Balance: The balance between work and personal life.

25-Years At Company: The number of years the employee has been with the current company.

26-Years In Current Role: The number of years the employee has been in their current role.

27-Years Since Last Promotion: The number of years since the last time the employee was promoted.

28-Years With Current Manager: The number of years the employee has been working under the current manager.


## Building Machine Learning Models
1. Perform EDA
 Load the dataset and check for missing values and summary statistics
2. Perform Feature Engineering

-Encoding Categorical Variables
-Scale Numerical Features
-PCA

## Splitting the Data
Train-Test Split: Split the dataset into training and testing sets using train_test_split.
3. Apply Algorithms

Here are some commonly used models for binary classification tasks like attrition prediction:

*Logistic Regression

*Decision Trees

*Random Forest

*Gradient Boosting (e.g., XGBoost or LightGBM)

*Support Vector Machines (SVM)

*Neural Networks

*K-Nearest Neighbors (KNN)

*Ensemble Methods
