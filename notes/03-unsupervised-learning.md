# Unsupervised Learning

## What is Unsupervised Learning?

Unsupervised Learning is a type of machine learning where
the model learns patterns from data without being given
the correct answers or labels.

The model tries to discover hidden patterns, groups,
or relationships in the data.

## Key Concepts

- Unlabeled Data — data without predefined answers
- Clustering — grouping similar data points together
- Pattern — relationship discovered in the data
- Similarity — how alike two data points are
- Group — collection of similar data points
- Dimensionality Reduction — reducing the number of features
- Anomaly Detection — finding unusual data points

## Example

Suppose a store has information about its customers:

- Customer A → spends $500, visits frequently
- Customer B → spends $450, visits frequently
- Customer C → spends $50, visits rarely
- Customer D → spends $70, visits rarely

We don't tell the model which customers belong together.

The model may discover two groups:

- Group 1 → Customers who spend a lot and visit frequently
- Group 2 → Customers who spend less and visit rarely

The model discovered these groups by looking for
similarities in the data.

## Common Algorithms

- K-Means Clustering
- Hierarchical Clustering
- DBSCAN
- Principal Component Analysis (PCA)

## Supervised vs Unsupervised Learning

### Supervised Learning

The data has labels:

- Email → Spam
- Email → Not Spam

The model learns to predict the labels.

### Unsupervised Learning

The data has no labels:

- Customer A
- Customer B
- Customer C
- Customer D

The model tries to discover groups or patterns by itself.

## My Takeaway

Unsupervised learning finds patterns, groups, or relationships
in data without being given the correct answers.


## NOTE:- 

### The easiest way to remember it
Think about students in a classroom:

##### Supervised learning:
Teacher says: "These students are beginners, and these students are advanced."
The model learns from the labels.

##### Unsupervised learning:
Teacher gives the model information about all students but doesn't say who is beginner or advanced.
The model looks at the information and discovers groups itself.

In one sentence:
Supervised = learn from labeled examples.
Unsupervised = find patterns in unlabeled data.
