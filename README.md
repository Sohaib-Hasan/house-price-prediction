# House Price Prediction

## About This Project

This project focuses on predicting house prices using real-world housing data. The main objective is to understand how different factors such as average income, number of rooms, house age, and area population influence property prices.

The project follows a complete machine learning workflow, starting from data exploration and preprocessing to model training, evaluation, and comparison. Multiple regression techniques have been implemented, including Linear Regression, Ridge, Lasso, and Random Forest models, to identify which method provides the most accurate predictions.

Through this work, I aimed to build a practical understanding of data analysis and predictive modeling, as well as to demonstrate how data-driven insights can be used for better decision-making in real estate and related fields.

---

## Dataset Description

The dataset contains information about housing and demographic factors that may affect property prices.

**Features:**

* Average Area Income
* Average Area House Age
* Average Area Number of Rooms
* Average Area Number of Bedrooms
* Area Population

**Target Variable:**

* Price

---

## Models Implemented

* Linear Regression
* Ridge Regression
* Lasso Regression
* Random Forest Regressor

Each model was trained and evaluated to compare predictive performance using R² and Mean Squared Error (MSE) metrics.

---

## Results Summary

| Model             | R² Score | Cross-Validation Score |
| ----------------- | -------- | ---------------------- |
| Linear Regression | 0.92     | 0.91                   |
| Ridge Regression  | 0.92     | 0.91                   |
| Lasso Regression  | 0.91     | 0.90                   |
| Random Forest     | 0.97     | 0.96                   |

*(Values may vary slightly depending on random state and data split.)*

---

## Key Insights

* Average income and the number of rooms are the most influential factors in predicting house prices.
* Regularized models like Ridge and Lasso help control overfitting, while ensemble methods such as Random Forest provide higher accuracy.
* Proper data preprocessing and feature scaling significantly improve model performance.

---

## Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Author

**Sohaib Hasan**
Machine Learning Enthusiast | Mathematics Lecturer
**LinkedIn:** [https://www.linkedin.com/in/sohaibhassan05/](https://www.linkedin.com/in/sohaibhassan05/)
