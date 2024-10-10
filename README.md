# Prediction of Employee Attrition

### Project Overview

Employee attrition, whether voluntary or involuntary, is a significant challenge for organizations, leading to a loss of talent, decreased productivity, and increased costs associated with hiring and training new employees. The departure of employees, whether due to factors like inadequate salary, poor work environment, or other personal reasons, can erode an organization’s human capital, affecting its overall performance and culture. This project aims to predict employee attrition using various machine learning models. By analyzing HR data, the model identifies key factors contributing to employee turnover, helping businesses improve employee retention strategies.

### Business Questions

- Q1: What factors contribute most to employee attrition?
- Q2: How accurate can we predict which employees are at high risk of leaving?
- Q3: What type of measures should the company take in order to reduce employee attrition?

### Dataset

The dataset used in this project is a fictional dataset created by IBM data scientists with the following features:

- Number of Records: 1,470
- Features: 35 attributes such as Age, Department, Monthly Income, Job Satisfaction, etc.
- Target Variable: Attrition (Binary: Yes/No)

You can find the dataset [here](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).

### Key Steps

### Project Structure

- Prediction_of_Employee_Attrition.ipynb: The Jupyter notebook containing the entire workflow for data preprocessing, EDA, model training, and evaluation.
- README.md: This file, providing an overview of the project.

### Findings/Recommendations

Q1: What factors contribute most to employee attrition?

- OverTime: This has the strongest correlation with attrition, indicating that employees working overtime are more likely to leave.
- Single: Single employees have a higher likelihood of attrition compared to married or divorced ones.
- TotalWorkingYears: Employees with fewer years of experience are more prone to leave.
- JobLevel: Employees in lower job levels tend to have higher attrition.
- Age: Younger employees are more likely to leave.

Q2: How accurate can we predict which employees are at high risk of leaving?

Both techniques used (Logistic Regression model and KNN) had an accuracy of ~93%. This suggests that with appropriate features and handling of class imbalance (like using SMOTE), the models can predict high-risk employees with a good degree of accuracy. The classification reports also show balanced precision and recall, making it reliable for practical use.

Q3: What type of measures should the company take in order to reduce employee attrition?

The organization should take the following measures to mitigate attrition:

- Implement a strict overtime policy to ensure that employees aren't overworked.
- Provide more social engagement opportunities within the workplace, such as team-building activities or company-sponsored events, to foster a sense of belonging.
- Provide clear career progression paths and development plans for employees, especially for younger employees and those at lower job levels.

### Future Improvements

There is big room for improvement, as I had to work within time constraints.

- Explore additional features to improve model accuracy.
- Implement more advanced techniques for feature selection and engineering.
- Investigate the use of deep learning models for this task.
