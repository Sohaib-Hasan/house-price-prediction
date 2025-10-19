# House Price Prediction

## About This Project

This project focuses on predicting house prices using real-world housing data. The main objective is to understand how different factors such as average income, number of rooms, house age, and area population influence property prices.

The project follows a complete **machine learning workflow**, starting from data exploration and preprocessing to model training and evaluation.
A **Linear Regression** model has been implemented to establish the relationship between input features and the target variable (house price).

Through this work, I aimed to build a strong foundation in data analysis and regression modeling, and to explore how mathematical ideas can be applied to real-world decision-making in the housing market.

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

## Model Implemented

* **Linear Regression**

The Linear Regression model was trained using Scikit-learn to identify how each feature contributes to the target price. Model performance was evaluated using **R²** and **Mean Squared Error (MSE)** metrics.

---

## Results Summary

| Metric                   | Value                   |
| ------------------------ | ----------------------- |
| R² Score                 | 0.92                    |
| Mean Squared Error (MSE) | (depends on data split) |

*(Values may slightly vary depending on random state and data split.)*

---

## Key Insights

* Average income and number of rooms show strong positive correlation with house prices.
* The Linear Regression model performs well in explaining price variations.
* Data preprocessing and feature selection play a major role in improving model accuracy.

---

## Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Future Improvements

In future updates, I plan to:

* Experiment with **Ridge**, **Lasso**, and **Random Forest** models for performance comparison.
* Add **cross-validation** and **feature scaling** steps.
* Visualize model coefficients and residuals for deeper insights.

---

## Author

**Sohaib Hasan**
Machine Learning Enthusiast | Mathematics Lecturer
**LinkedIn:** [https://www.linkedin.com/in/sohaibhassan05/](https://www.linkedin.com/in/sohaibhassan05/)
