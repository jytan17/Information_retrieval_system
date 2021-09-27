# Information Retrieval System

This repository contains an information retrieval system program which can be used to search through a database of documents to retrieve the relevant document(s) for a specified query. 

## Feature Engineering API

The built-in API allows for custom feature engineering on the database, e.g. for each "title" generate the BM25 feature, or for each "text body" generate TF-IDF for  each word.

```python



```

## Machine Learning API

We can train a model to learn to rank and retrieve documents using the engineered features and the built-in ML API allows for easy implementation of such methods:

Currently, only XGBoost and Feedforward networks (implemented with Pytorch) are available (more sophiticated models are planned for the future).


## Performance Metrics

