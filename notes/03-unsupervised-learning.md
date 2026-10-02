Linear Regression
What is Linear Regression?

Linear regression is a supervised learning algorithm used to predict a continuous numerical value.

It tries to find a relationship between input features and a target.

Basic Formula

For one feature:

y = mx + b


Where:

y = predicted value

x = input

m = slope

b = intercept

Example

Suppose we predict salary from years of experience.

Years of Experience → Salary
1                  → $50,000
3                  → $70,000
5                  → $90,000


The model tries to find a line that represents the relationship.

For example:

salary = 10,000 × experience + 40,000


For 4 years:

salary = 10,000 × 4 + 40,000
       = $80,000

Python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)

prediction = model.predict(X_test)

Key Terms

Feature

Target

Slope

Intercept

Prediction

Regression

My Takeaway

Linear regression learns a mathematical relationship between input features and a continuous target.
