# 🚗 Car Pricing Prediction using Linear Regression

## Overview

This project analyzes the factors that influence automobile pricing and develops regression models to predict a vehicle's **Manufacturer's Suggested Retail Price (MSRP)**.

Using Python and Scikit-learn, the project walks through the complete data science workflow including:

- Data cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Linear regression modeling
- Feature selection
- Model evaluation

The goal is to understand which vehicle characteristics have the greatest impact on price while building an interpretable predictive model.

---

## Business Problem

Accurately estimating vehicle prices is valuable for:

- Automotive manufacturers
- Dealerships
- Insurance companies
- Consumers
- Online vehicle marketplaces

This project explores how technical specifications such as engine performance and fuel economy influence MSRP and evaluates the effectiveness of linear regression models for price prediction.

---

## Dataset

The dataset contains information for over **10,000 vehicles**, including attributes such as:

- Engine HP
- Highway MPG
- Number of Cylinders
- Driven Wheels
- Vehicle Size
- Engine Fuel Type
- Vehicle Style
- MSRP (target variable)

---

## Project Workflow

### 1. Data Cleaning

- Removed duplicate records
- Handled missing values
- Converted categorical variables into numerical features
- Dropped unused variables

### 2. Feature Engineering

Categorical variables were encoded using:

- **One-Hot Encoding**
  - Driven Wheels

- **Ordinal Encoding**
  - Vehicle Size

### 3. Exploratory Data Analysis

EDA included:

- Distribution plots
- Correlation analysis
- Feature relationship exploration
- Identification of variables associated with MSRP

### 4. Modeling

Three simple regression models were developed:

- Linear Regression using Engine HP
- Linear Regression using Highway MPG
- Log-Linear Regression using Engine HP

Feature selection techniques were also explored:

- Forward Selection
- Backward Selection

### 5. Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## Results

The final simple linear regression model using **Engine HP** produced:

| Metric | Value |
|---------|--------|
| MAE | 20,819.47 |
| MSE | 1,141,173,460.58 |
| R² Score | 0.54 |

While Engine HP explains a substantial portion of price variation, the results indicate that MSRP is influenced by multiple vehicle characteristics. More advanced machine learning models or additional engineered features would likely improve predictive performance.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Future Improvements

Potential enhancements include:

- Multiple Linear Regression
- Ridge and Lasso Regression
- Random Forest Regressor
- Gradient Boosting (XGBoost)
- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
- Interactive visualizations using Plotly

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Regression Modeling
- Feature Selection
- Model Evaluation
- Data Visualization
- Python Programming
- Business Analytics

---
## Repository Structure

```
├── Car_Pricing.ipynb
├── README.md
└── Dataset.csv
```
---
## Author

**Kelly Conard**

MBA Candidate | Clinical Research Professional | Data Analytics & AI

- Python
- SQL
- Tableau
- Power BI
- Machine Learning
- Business Analytics



