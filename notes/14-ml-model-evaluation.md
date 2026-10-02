# Machine Learning Model Evaluation

## What is Model Evaluation?

Model evaluation is the process of measuring how well
a machine learning model performs on data.

A model should be evaluated on data that it did not
use to learn its parameters.

## Key Concepts

- Training Data — data used to train the model
- Validation Data — data used to tune the model
- Test Data — data used to evaluate final performance
- Accuracy — percentage of correct predictions
- Precision — how many predicted positives were actually positive
- Recall — how many actual positives were correctly found
- F1 Score — balance between precision and recall
- Overfitting — model performs well on training data but poorly on new data
- Underfitting — model is too simple to capture important patterns

## Example

Suppose an email classifier processes 100 emails.

If it correctly classifies 90 emails:

> Accuracy = 90 / 100 = 90%

However, accuracy alone may not tell the whole story.

For a spam detector, precision and recall can also
be important because different types of mistakes have
different consequences.

## My Takeaway

Model evaluation helps us understand how well a model
generalizes to new data and whether its predictions are useful.
