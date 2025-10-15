## 📘 Project 1: Linear Regression

### 🧠 Description

This repository contains a from-scratch implementation of the **Linear Regression** algorithm, developed in a Jupyter Notebook.
The goal is to understand the internal workings of the model **without relying on external libraries** such as scikit-learn.
It covers the theoretical foundations, mathematical derivation, and a step-by-step practical implementation.

`Linear regression` is a statistical method that is used to **predict** a continuous dependent variable i.e target variable based on one or more independent variables.

#### Why Linear Regression is Important?
- **Simplicity and Interpretability**: It’s easy to understand and interpret, making it a starting point for learning about machine learning.
- **Basis for Other Models**: Many advanced algorithms, like logistic regression or neural networks, build on the concepts of linear regression.

#### Assumptions of the Linear Regression
1. Linearity: The relationship between inputs (X) and the output (Y) is a straight line.
2. Independence of Errors: The errors in predictions should not affect each other.
3. Constant Variance (Homoscedasticity): The errors should have equal spread across all values of the input. If the spread changes (like fans out or shrinks), it's called heteroscedasticity and it's a problem for the model.

![homoscedasticity.png](attachment:homoscedasticity.png)

4. Normality of Errors: The errors should follow a normal (bell-shaped) distribution.
5. No Multicollinearity(for multiple regression): Input variables shouldn’t be too closely related to each other.
6. No Autocorrelation: Errors shouldn't show repeating patterns, especially in time-based data.
7. Additivity: The total effect on Y is just the sum of effects from each X, no mixing or interaction between them.'


---

### 📊 Notebook Contents

1. **Theoretical introduction to linear regression.**
2. **Simple Linear Regression:**

   Solved using **three different methods**, explaining how each one works, their advantages and disadvantages,
   along with a **graphical representation** for each.

   * Least Squares (statistical method)
   * Normal Equation (algebraic method)
   * Gradient Descent (machine learning method)

> There are other mathematical methods that we won't cover here. 
>
> OLS: Ordinary Least Squares
> 
> - **Maximum likelihood estimation**: MLE can be used with any parametric distribution $f_θ$ for the errors (not just the normal one) but when $f_θ$ is a normal distribution with zero mean and variance θ, the resulting estimate is identical to the OLS estimate.
> - **Regularized Regression**: 
>   - *Ridge regression*: For scenarios where the independent variables are highly correlated.
>   - *Lasso regression*: For scenarios where the coefficients of the linear model are sparse.
> - **Least Absolute Deviation**: less sensitive to the presence of outliers than OLS.
> - **Adaptive Estimation**: 2-step MLE, the first step non-parametrically estimates the error distribution, and the second step performs MLE using that estimate.
> - **Bayesian linear regression**: produces a posterior distribution for the "best" values of the regression coefficients.
> - **Quantile regression**: focuses on the conditional quantiles of y given X rather than the conditional mean of y given X.
> - **Mixed models**: when the dependencies have a known structure
> - **Principal component regression (PCR)**: when the number of predictor variables is large, or when strong correlations exist among the predictor variables
> - **Least-angle regression**: for high-dimensional covariate vectors
> - **The Theil–Sen estimator**: chooses the median of the slopes of the lines through pairs of sample points. (robust to outliers)
> - Other robust estimation techniques, including the α-trimmed mean approach, and L-, M-, S-, and R-estimators have been introduced.

---

### ⚙️ Technologies Used

* **Python 3.11+**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**

---

### 🧩 Contents

```
├── 01_simple_linear_regression.ipynb          # Notebook with theory and code -> Language: English
├── 02_multiple_linear_regression.ipynb        # Notebook with theory and code -> Language: English
├── README.md           # This file
├── README_ES.md        # This file (spanish version)
```

---

### 📚 References

> * [https://www.geeksforgeeks.org/machine-learning/linear-regression-python-implementation](https://www.geeksforgeeks.org/machine-learning/linear-regression-python-implementation)
> * [https://www.geeksforgeeks.org/machine-learning/ml-linear-regression](https://www.geeksforgeeks.org/machine-learning/ml-linear-regression)
> * [https://www.geeksforgeeks.org/machine-learning/ml-normal-equation-in-linear-regression](https://www.geeksforgeeks.org/machine-learning/ml-normal-equation-in-linear-regression)
> * [https://www.geeksforgeeks.org/machine-learning/gradient-descent-in-linear-regression](https://www.geeksforgeeks.org/machine-learning/gradient-descent-in-linear-regression)
> * [https://www.geeksforgeeks.org/machine-learning/ml-multiple-linear-regression-using-python](https://www.geeksforgeeks.org/machine-learning/ml-multiple-linear-regression-using-python)

---

### 👨‍💻 **Author** : [@RubenGonV](https://github.com/RubenGonV)

> 📬 If you found this project useful, consider leaving a ⭐ on the repository — it’s more motivating than it looks!
