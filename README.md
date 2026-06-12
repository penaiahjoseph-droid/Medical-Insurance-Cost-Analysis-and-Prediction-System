Medical Insurance Cost Analysis and Prediction System
Overview

The Medical Insurance Cost Analysis and Prediction System is a machine learning project that analyzes factors affecting medical insurance costs and predicts insurance charges using regression and classification techniques. The project generates a synthetic insurance dataset, performs exploratory data analysis (EDA), visualizes trends, and builds predictive models.

Features
Generates a synthetic medical insurance dataset.
Performs data exploration and statistical analysis.
Detects missing values and calculates key averages.
Categorizes insurance costs into risk levels:
Low Cost
Medium Cost
High Cost
Visualizes data using Matplotlib, Seaborn, and Plotly.
Implements:
Simple Linear Regression
Multiple Linear Regression
Logistic Regression
Evaluates model performance using various metrics.
Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Plotly
Scikit-learn
Dataset Attributes
Feature	Description
Age	Age of the individual
Sex	Gender (Male/Female)
BMI	Body Mass Index
Children	Number of dependent children
Smoker	Smoking status
Region	Residential region
Charges	Medical insurance charges
Project Workflow
1. Data Generation

A synthetic dataset containing 1000 insurance records is generated with realistic medical insurance attributes.

2. Data Analysis

The project:

Displays dataset overview
Calculates descriptive statistics
Identifies missing values
Computes average values
3. Risk Classification

Insurance charges are categorized into:

Low Cost
Medium Cost
High Cost

based on charge quantiles.

4. Data Visualization

Visualizations include:

Insurance Charges Distribution
Age vs Charges
BMI vs Charges
Correlation Heatmap
Region-wise Charge Distribution
5. Machine Learning Models
Simple Linear Regression

Predicts insurance charges using age.

Evaluation Metrics

R² Score
MAE
MSE
RMSE
Multiple Linear Regression

Predicts insurance charges using all available features.

Evaluation Metrics

R² Score
MAE
MSE
RMSE
Logistic Regression

Classifies insurance costs into higher or lower cost categories.

Evaluation Metrics

Accuracy Score
Confusion Matrix
Classification Report
Installation
Clone the Repository
git clone https://github.com/your-username/medical-insurance-cost-analysis.git
cd medical-insurance-cost-analysis
Install Dependencies
pip install numpy pandas matplotlib seaborn plotly scikit-learn
Run the Project
python medical_insurance_prediction.py

or run the Jupyter Notebook:

jupyter notebook

Open:

Medical_Insurance_Cost_Analysis_and_Prediction_System.ipynb
Expected Output
Dataset summary
Statistical analysis
Insurance cost visualizations
Regression model performance metrics
Classification results
Interactive Plotly charts
Future Enhancements
Use real-world insurance datasets.
Add advanced machine learning algorithms.
Develop a web application using Flask or Streamlit.
Deploy the prediction model to the cloud.
Implement real-time insurance cost prediction.
Conclusion

This project demonstrates how machine learning can be used to analyze medical insurance data and predict insurance costs. It combines data analysis, visualization, regression, and classification techniques to provide meaningful insights into healthcare insurance pricing.

Author

Penaiah Joseph

Medical Insurance Cost Analysis and Prediction System – Machine Learning Project.
