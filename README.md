# 🚗 Auto MPG Prediction using Polynomial Regression

## 📌 Project Overview
This project predicts a car's fuel efficiency (MPG - Miles Per Gallon) using Polynomial Regression. Unlike linear regression, this model captures non-linear relationships between engine and vehicle features.

---

## 📂 Dataset
Dataset used: Auto MPG Dataset (Kaggle)

Features:
- Cylinders → Number of engine cylinders
- Displacement → Engine size
- Horsepower → Engine power
- Weight → Vehicle weight
- Acceleration → Speed performance
- Model Year → Manufacturing year
- MPG → Fuel efficiency (Target)

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🚀 Steps Performed

### 1. Data Loading
- Loaded dataset using pandas

### 2. Data Exploration
- Checked missing values
- Used descriptive statistics
- Visualized relationships using scatter plots

### 3. Data Preparation
- Selected features:
  - Displacement, Horsepower, Weight, Acceleration
- Target:
  - MPG
- Train-test split (80/20)

### 4. Polynomial Feature Transformation
- Applied PolynomialFeatures (degree = 2)
- Captured non-linear relationships

### 5. Model Building
- Used LinearRegression on transformed features
- Trained model on training data

### 6. Model Evaluation
- Mean Squared Error (MSE)
- R² Score

### 7. Visualization
- Scatter plots for feature relationships
- Actual vs Predicted MPG plot

---

## 📊 Results

- Polynomial regression improves prediction accuracy compared to linear regression
- Captures non-linear relationships between weight, horsepower, and MPG
- Key insight:
  - Higher weight and horsepower → lower MPG

---

## 📈 Sample Output

| Metric | Value |
|------|------|
| MSE | (your output) |
| R² Score | (your output) |

---

## 🖥️ How to Run

### Step 1: Clone Repository
```bash
git clone https://github.com/your-username/auto-mpg-polynomial-regression.git
cd auto-mpg-polynomial-regression
