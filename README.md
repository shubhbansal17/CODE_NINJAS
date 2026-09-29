Coding Ninjas 10X -- AI/ML Recruitment
Auto MPG Analysis & Linear Regression
This project contains two connected tasks:
- Task 1: Exploratory Data Analysis and data cleaning of the Auto
  MPG dataset.
- Task 2: Linear Regression models to predict mpg using the
  cleaned dataset from Task 1.
Workflow
Task 1 → Clean & analyse data → auto_mpg_cleaned.csv → Task 2 → Linear Regression
Task 1
- Clean missing and inconsistent data
- Perform EDA and visualisations
- Analyse relationships between vehicle features and MPG
- Export auto_mpg_cleaned.csv
Task 2
- Load auto_mpg_cleaned.csv
- One-hot encode origin
- Split data into training and testing sets
- Build:
  - Weight-only Linear Regression
  - Multiple Linear Regression
- Evaluate using MAE, MSE, RMSE and R²
- Analyse predictions, residuals and model limitations
Files
task1_Cn.ipynb
task2_cn.ipynb
auto_mpg_cleaned.csv
README.md
Requirements
pip install numpy pandas matplotlib seaborn scipy scikit-learn jupyter
Run Task 1 first, then run Task 2. The cleaned CSV must be in
the same folder as task2_cn.ipynb.
Author: Shubh Bansal
B.Tech CSE Core -- 1st Year
