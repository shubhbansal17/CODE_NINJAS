# Coding Ninjas 10X – AI/ML Recruitment

## Auto MPG Analysis & Linear Regression

This project contains two connected tasks:

- **Task 1:** Exploratory Data Analysis and data cleaning of the Auto MPG dataset.
- **Task 2:** Linear Regression models to predict `mpg` using the cleaned dataset from Task 1.

### Workflow

```text
Task 1 → Clean & Analyse Data → auto_mpg_cleaned.csv → Task 2 → Linear Regression
```

---

## Task 1 – Data Analysis & Cleaning

- Clean missing and inconsistent data
- Perform Exploratory Data Analysis (EDA)
- Visualise relationships between vehicle features and MPG
- Analyse correlations and outliers
- Export the cleaned dataset as `auto_mpg_cleaned.csv`

---

## Task 2 – Linear Regression

- Load `auto_mpg_cleaned.csv`
- One-hot encode the `origin` feature
- Split data into training and testing sets
- Build a **Weight-only Linear Regression** model
- Build a **Multiple Linear Regression** model
- Evaluate models using:
  - MAE
  - MSE
  - RMSE
  - R²
- Analyse predictions and residuals
- Discuss model limitations and possible improvements

---

## Files

```text
task1_Cn.ipynb
task2_cn.ipynb
auto_mpg_cleaned.csv
README.md
```

---

## Requirements

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn jupyter
```

---

## How to Run

Run **Task 1 first**:

```text
task1_Cn.ipynb
```

This generates:

```text
auto_mpg_cleaned.csv
```

Then run **Task 2**:

```text
task2_cn.ipynb
```

Make sure `auto_mpg_cleaned.csv` is in the same folder as the Task 2 notebook.

---

## Author

**Shubh Bansal**  
B.Tech CSE Core – 1st Year
