# 📊 Salary Prediction using Linear Regression

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-blue)
![Python](https://img.shields.io/badge/Python-3.x-yellow)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)

[![Kaggle Notebook](https://img.shields.io/badge/Kaggle-Notebook-blue?logo=kaggle)](https://www.kaggle.com/code/shivani531/salary-prediction-dataset-linearregression)

## 📌 Project Overview

This project focuses on predicting employee salary using **Machine Learning Regression Techniques**.

The main objective of this project is to analyze how different factors such as experience, education, job role, and other employee attributes affect salary prediction.

In this project, I implemented:

- ✅ Simple Linear Regression
- ✅ Multiple Linear Regression

The complete workflow includes:
- Data Understanding
- Data Cleaning
- Handling Missing Values
- Feature Encoding
- Model Training
- Prediction
- Model Evaluation
- Data Visualization


---

# 📂 Dataset Information

The dataset contains employee details:

| Feature | Description |
|---------|-------------|
| Age | Age of employee |
| Gender | Gender category |
| Education Level | Educational qualification |
| Job Title | Employee job role |
| Years of Experience | Total work experience |
| Salary | Employee salary (Target Variable) |


### 🎯 Target Variable

```
Salary
```

### 🔹 Input Features

```
Age
Gender
Education Level
Job Title
Years of Experience
```


---

# 🔄 Project Workflow

## 1️⃣ Data Understanding

- Imported dataset using Pandas.
- Checked dataset structure.
- Performed statistical analysis.

Operations performed:

```python
df.head()
df.info()
df.describe()
```


---

## 2️⃣ Data Preprocessing

Steps performed:

✔ Checked missing values  
✔ Handled missing data  
✔ Converted categorical variables into numerical format  
✔ Applied One-Hot Encoding


Categorical features encoded:

- Gender
- Education Level
- Job Title


---

# 📈 Simple Linear Regression

Simple Linear Regression was implemented to understand the relationship between:

### Independent Variable:

```
Years of Experience
```

### Dependent Variable:

```
Salary
```


### Linear Equation:

```
Salary = m × Years of Experience + b
```

Where:

- **m** → Slope
- **b** → Intercept


---

# 📊 Multiple Linear Regression

Multiple Linear Regression was implemented using multiple features to improve prediction accuracy.


### Features Used:

- Age
- Years of Experience
- Gender
- Education Level
- Job Title


### Target:

```
Salary
```


---

# 🤖 Model Training

The model was trained using Scikit-Learn:

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)
```


---

# 📏 Model Evaluation

The performance of the model was evaluated using:

### MAE (Mean Absolute Error)

Measures the average error between actual and predicted salary.


### MSE (Mean Squared Error)

Measures the squared difference between actual and predicted values.


### RMSE (Root Mean Squared Error)

Shows prediction error in salary units.


### R² Score

Measures how well the model explains salary variations.


---

# 📊 Visualization

The project contains different visualizations:

- Salary distribution analysis
- Regression line visualization
- Actual vs Predicted salary comparison
- 3D visualization of salary relationship


---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Plotly | Interactive Visualization |
| Scikit-Learn | Machine Learning Model |
| Jupyter Notebook | Development Environment |


---

# 📌 Results

The Linear Regression model successfully learned the relationship between employee features and salary.

The model achieved a good **R² Score**, showing that employee experience and other features significantly influence salary prediction.


---

# 🚀 Future Improvements

Future improvements:

- Implement advanced regression algorithms:
  - Random Forest Regression
  - Gradient Boosting Regression
  - XGBoost

- Perform Hyperparameter Tuning
- Deploy the model using Streamlit


---

# 👩‍💻 Author

**Shivani**

🎓 B.Tech Computer Science Engineering


---

⭐ If you find this project helpful, consider giving this repository a star!
