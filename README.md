# Information_retrieval_system

This repository contains an information retrieval system program which can be used to search through a database of documents to retrieve the relevant document(s) for a specified query. 

## Feature Engineering API

The built-in API allows for custom feature engineering on the database, e.g. for each "title" generate the BM25 feature, or for each "text body" generate TF-IDF for  each word.

```python



```

## Ranking, and retrieving documents with machine learning models

We can train a model to learn to rank and retrieve documents using the engineered features. The built-in ML model API allows for easy implementation of such methods:

Currently only XGBoost and a simple Feedforward network (implemented with Pytorch) are available. Plans to expand on the available models 


## Performance Metrics
