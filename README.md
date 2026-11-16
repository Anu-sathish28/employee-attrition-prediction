# Employee Attrition Predictive Modeling

## Project Overview
This project focuses on predicting employee attrition using Machine Learning techniques. It analyzes employee-related information and predicts whether an employee is likely to leave the organization (Yes) or stay (No).

## Objectives
- Analyze employee data using Exploratory Data Analysis (EDA).
- Identify patterns and factors related to employee attrition.
- Apply machine learning classification algorithms.
- Compare model performance and select the best-performing model.

## Dataset
- Total records: 300
- Target variable: Attrition
- Features include Age, Years of Experience, Education, Department, Monthly Salary, Performance Score, Job Satisfaction, Overtime and Promotion History.
- Dataset: Generated synthetic dataset for educational and project purposes.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

## Machine Learning Models
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Model Evaluation Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 63.33% |
| Decision Tree | 56.67% |
| Random Forest | 56.67% |

Logistic Regression was selected as the best-performing model among the three models based on the test accuracy.

## Project Files
- `predictive_modeling.ipynb` – Complete project implementation, EDA, preprocessing, model training and evaluation.
- `employee_attrition.csv` – Dataset used for the project.
- `best_attrition_model.pkl` – Saved Logistic Regression model.
- `attrition_preprocessor.pkl` – Saved preprocessing transformer.

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `predictive_modeling.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells in order.

## Limitations
The project uses a generated dataset containing 300 records. The reported results are experimental and should not be treated as validated real-world employee attrition predictions.

## Conclusion
This project demonstrates the application of data analysis and machine learning techniques to employee attrition prediction. Three classification models were trained and evaluated, and Logistic Regression achieved the highest test accuracy of 63.33% among the models tested.