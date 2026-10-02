Attention
What is Attention?

Attention is a mechanism that allows a neural network to determine which parts of the input are relevant when processing a particular token.

Core Idea

Not every word in a sentence is equally important for understanding every other word.

Attention allows the model to assign different levels of importance to different tokens.

Example

Consider:

The animal didn't cross the road because it was tired.


When processing:

"it"


the model needs to consider the surrounding words to understand what "it" refers to.

Attention helps represent these relationships.

Query, Key, and Value

Self-attention uses three important concepts:

Query — what information am I looking for?

Key — what information does each token represent?

Value — what information should be passed forward?

These are used to calculate attention scores.

Simplified Process
Tokens
  ↓
Queries, Keys, Values
  ↓
Attention Scores
  ↓
Weighted Information
  ↓
Updated Representations

My Takeaway

Attention allows a model to focus on relevant parts of the context when processing each token.
