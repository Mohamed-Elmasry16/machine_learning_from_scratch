# 📊 Multivariate Linear Regression from Scratch

This project implements a multivariate linear regression model from scratch using Python, avoiding high-level libraries like scikit-learn for core logic. It predicts **Performance Index** based on multiple features from the `Student_Performance.csv` dataset, offering a hands-on understanding of the algorithm’s mechanics.

---

## 🧠 What This Project Covers

- **Data Preprocessing**
  - Loaded dataset with features: `Hours Studied`, `Previous Scores`, `Extracurricular Activities`, `Sleep Hours`, `Sample Question Papers Practiced`
  - Converted `Extracurricular Activities` (Yes/No) to binary (1/0)
  - Verified no missing values

- **Pearson Correlation Analysis**  
  - Computed correlation between each feature and `Performance Index`

- **Multivariate Linear Regression**
  - Manual computation of model weights (slopes and intercept)
  - Prediction using the regression equation:  
    \( y = w_1x_1 + w_2x_2 + \dots + b \)
  - Cost function: Mean Squared Error (MSE)
  - Gradient computation
  - Gradient Descent for optimizing parameters

- **Performance Evaluation**
  - Metrics: MSE, MAE, and R² Score

- **Visualization**
  - Scatter plot: Actual vs. Predicted (custom vs. scikit-learn)
  - Training loss over iterations to visualize convergence

---

## 🎯 Goal

To understand multivariate linear regression by building it from scratch, focusing on the underlying math and logic, and applying it to predict **Performance Index** using multiple student-related features.

---

## 📊 Technologies Used

- Python  
- NumPy – for numerical operations  
- Pandas – for data handling  
- Matplotlib & Seaborn – for data visualization  
- Scikit-learn – for benchmarking only

---

## 📁 Project Structure

- `multi_regression.ipynb` – Jupyter Notebook with full implementation including preprocessing, correlation, regression, and training  
- `Student_Performance.csv` – Dataset with student features and Performance Index

---

## 👨‍💻 Author

**Mohamed Waleed (Elmasry)**  
Aspiring Data Scientist

[GitHub](https://github.com/Mohamed-Elmasry16) • [LinkedIn](https://www.linkedin.com/in/mohamedwaleed16)

