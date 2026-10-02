# Retrieval-Augmented Generation

## What is RAG?

RAG stands for Retrieval-Augmented Generation.

RAG combines information retrieval with an LLM.

Instead of relying only on the knowledge learned during
training, the system retrieves relevant information
and gives it to the LLM as context.

## Key Concepts

- Retrieval — finding relevant information
- Documents — information stored in a knowledge source
- Embeddings — numerical representations of information
- Vector Database — stores and searches embeddings
- Context — retrieved information given to the LLM
- Generation — answer produced by the LLM

## Example

Suppose a company has thousands of internal documents.

A user asks:

> What is our vacation policy?

The RAG system:

1. Searches the company documents
2. Finds the relevant policy
3. Gives the information to the LLM
4. The LLM generates an answer

## My Takeaway

RAG allows an LLM to retrieve relevant external information
and use it when generating an answer.
