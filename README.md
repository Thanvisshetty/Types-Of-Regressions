# Types Of Regressions
## ✅ 1. Linear Regression
🔍 What It Is:
Linear Regression is the most basic type of regression. It models a linear relationship between an independent variable (X) and a dependent variable (y).

🧠 How It Works:
It finds the best-fitting straight line through the data points by minimizing the sum of squared differences (errors) between actual and predicted values (Least Squares Method).

📊 Use Case Example:
Predicting salary based on years of experience.

✅ Pros:
Easy to interpret

Fast to train

Works well with linearly related data

❌ Cons:
Not suitable for nonlinear relationships

Sensitive to outliers

## ✅ 2. Multiple Linear Regression
🔍 What It Is:
It’s an extension of Linear Regression where more than one feature (X₁, X₂, ..., Xₙ) is used to predict the target variable.
 
🧠 How It Works:
It fits a hyperplane in n-dimensional space using multiple predictors.

📊 Use Case Example:
Predicting house prices based on area, number of bedrooms, and age.

✅ Pros:
Can handle more complex problems

Better predictive power with multiple relevant inputs

❌ Cons:
Needs more data

Multicollinearity can reduce performance

## ✅ 3. Polynomial Regression
🔍 What It Is:
Polynomial Regression models nonlinear relationships between input and output by adding polynomial terms.

🧠 How It Works:
Transforms input features into polynomial features and fits a linear model to them.

📊 Use Case Example:
Predicting the square of a number (nonlinear growth like y = x²).

✅ Pros:
Captures curved trends

Simple to implement

❌ Cons:
Can overfit if degree is too high

Less interpretable

## ✅ 4. Ridge Regression (L2 Regularization)
🔍 What It Is:
It’s a regularized version of Linear Regression that adds a penalty to the loss function to reduce overfitting.
​
 
🧠 How It Works:
It penalizes large coefficients and reduces their magnitude while keeping all features.

📊 Use Case Example:
Predicting target where features are highly correlated (multicollinearity problem).

✅ Pros:
Handles multicollinearity well

Reduces overfitting

❌ Cons:
Doesn’t eliminate features (all are kept)

## ✅ 5. Lasso Regression (L1 Regularization)
🔍 What It Is:
Similar to Ridge, but Lasso can shrink some coefficients to zero, effectively selecting important features.

 ∣
🧠 How It Works:
Adds a penalty equal to the absolute value of the magnitude of coefficients.

📊 Use Case Example:
Predicting with many features, some of which are irrelevant.

✅ Pros:
Performs feature selection

Prevents overfitting

❌ Cons:
Can discard useful features

## ✅ 6. Logistic Regression
🔍 What It Is:
Used for classification, not regression. Despite the name, it predicts probabilities for binary classes (0 or 1).
 
🧠 How It Works:
Applies a logistic (sigmoid) function to model the probability that y belongs to class 1.

📊 Use Case Example:
Predicting pass/fail based on marks.

✅ Pros:
Works well for binary classification

Outputs probabilities

❌ Cons:
Doesn’t handle non-linearity unless transformed

## ✅ 7. ElasticNet Regression
🔍 What It Is:
A hybrid of Ridge and Lasso that combines both L1 and L2 penalties.

🧠 How It Works:
Balances the strengths of Ridge and Lasso, controlling shrinkage and feature selection.

📊 Use Case Example:
When some features are highly correlated, and you also want feature selection.

✅ Pros:
Balanced regularization

Feature selection + shrinkage

❌ Cons:
Slightly more complex to tune

