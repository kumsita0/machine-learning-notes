Classification
What is Classification?

Classification is a supervised learning task where the model predicts a category or class.

Unlike regression, the output is usually a discrete label.

Examples

Spam / Not Spam

Cat / Dog

Fraud / Not Fraud

Positive / Negative

Example

Suppose we build a spam detector.

Email
  ↓
Classification Model
  ↓
Spam / Not Spam


The model learns from previously labeled emails.

Common Algorithms

Logistic Regression

Decision Trees

Random Forest

Support Vector Machines

Neural Networks

Evaluation

Common classification metrics include:

Accuracy

Precision

Recall

F1 score

Python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression()

model.fit(X_train, y_train)

prediction = model.predict(X_test)

My Takeaway

Classification predicts categories. It is commonly used when the answer belongs to a finite set of classes.
