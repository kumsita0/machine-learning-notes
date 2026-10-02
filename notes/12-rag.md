Retrieval-Augmented Generation
What is RAG?

RAG stands for Retrieval-Augmented Generation.

RAG combines information retrieval with an LLM.

Instead of relying only on what the model learned during training, the system retrieves relevant information and provides it to the model as context.

Basic Architecture
User Question
      ↓
Search / Retrieval
      ↓
Relevant Documents
      ↓
LLM + Retrieved Context
      ↓
Answer

Why Use RAG?

RAG can be useful when an application needs to answer questions about:

Company documents

Internal knowledge bases

Product documentation

Recent information

Large collections of documents

Example

Suppose a company has thousands of internal documents.

A user asks:

What is our vacation policy?


A RAG system can:

Search the company's documents.

Retrieve the relevant policy.

Give the relevant text to the LLM.

Ask the LLM to answer using that context.

Important Components

Documents

Chunking

Embeddings

Vector database

Retrieval

Context

LLM

My Takeaway

RAG gives an LLM relevant external information at inference time so it can generate answers using retrieved context.
