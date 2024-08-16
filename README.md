## Problem: Context Window

ChatGPT cannot handle text longer than 4097 tokens. What happens if we want to ask questions about a document that exceeds this limit?

## Solution:

- We will divide the document into smaller fragments.
- We will convert the fragments into numbers (called "embeddings"), which are optimized to handle millions of data points in milliseconds.
- We will load the embeddings into a vector database, which is also optimized to handle millions of data points in milliseconds.
- We will create a retrieval system using a predefined chain from LangChain.
