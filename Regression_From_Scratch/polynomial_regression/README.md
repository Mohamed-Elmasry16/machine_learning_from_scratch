# 📊 Polynomial Regression from Scratch — Stock Price Prediction

This project demonstrates how to build a **Polynomial Regression model from scratch** using only NumPy. We use real-world stock price data to model and predict closing prices based on the number of days since trading began.

---

## 🚀 Objectives

- Understand the theory behind polynomial regression
- Implement the normal equation manually without any ML libraries
- Create polynomial features (feature expansion)
- Make predictions using matrix multiplication
- Evaluate the model with Mean Squared Error (MSE)
- Compare results with scikit-learn's `PolynomialFeatures` + `LinearRegression`

---

## 🧠 Concepts Covered

- Polynomial feature expansion
- Normal equation:  
  $$\theta = (X^T X)^{-1} X^T y$$
- Manual prediction using matrix dot product
- Overfitting and underfitting analysis
- Performance comparison with scikit-learn
- Data visualization and residual analysis

---

## 📂 Project Structure

```
📦 polynomial-regression
 ┣ 📄 README.md
 ┣ 📊 stock_data.csv          # Real dataset used
 ┣ 📓 polynomial_model.ipynb  # Main notebook (code + analysis)
```

---

## 📈 Dataset

The dataset includes:
- **X**: Day (integer)
- **y**: Stock closing price (float)
- Size: ~1000 samples  
Used to simulate a real-world regression problem with non-linear trends.

---



## 📊 Visualizations

- Data fit on training and test sets
- Custom model vs scikit-learn
- Residual plot

---

## ✅ Conclusion

- Successfully implemented polynomial regression from scratch
- Confirmed correctness by comparing with scikit-learn
- Learned the impact of model complexity (degree) on performance

---

## 🛠️ Tools Used

- Python
- NumPy
- Matplotlib / Seaborn (for visualization)
- Pandas (for data loading)
- scikit-learn (for comparison only)

---


## 🧑‍💻 Author

Mohamed Elmasry  
Feel free to connect or explore more on [GitHub](https://github.com/Mohamed-Elmasry16)

