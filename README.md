# DistilBERT News Classification with Hugging Face

This project fine-tunes a DistilBERT transformer model for multi-class text classification using the AG News dataset. It demonstrates an end-to-end natural language processing workflow in Python, from data loading and tokenization to model training, evaluation, and sample predictions.

## Overview

Transformer models have become a standard approach for modern NLP tasks because they can capture language context far better than many traditional methods. In this project, I use a pre-trained DistilBERT model from Hugging Face and fine-tune it to classify news articles into one of four categories.

The notebook is designed to show a practical, reproducible workflow for applying transformer-based NLP to a real text classification problem.

## Project Goal

The goal of this project is to build a working text classification pipeline that demonstrates how pre-trained language models can be adapted for downstream business and analytics use cases such as content routing, topic tagging, sentiment workflows, and automated document categorization.

## Dataset

This project uses the **AG News** dataset, a widely used benchmark for text classification.

The model predicts one of four classes:

- World
- Sports
- Business
- Sci/Tech

## Tools and Technologies

- Python
- Hugging Face Transformers
- Hugging Face Datasets
- PyTorch
- Evaluate
- Jupyter Notebook

## What the Notebook Does

This project includes the following steps:

- Loads the AG News dataset from the Hugging Face hub
- Explores label structure and creates label mappings
- Tokenizes article text using a DistilBERT tokenizer
- Prepares the dataset for PyTorch training
- Fine-tunes a DistilBERT sequence classification model
- Evaluates performance using accuracy
- Runs inference on sample news headlines

## Model Summary

The notebook uses:

- **Model checkpoint:** `distilbert-base-uncased`
- **Task:** Multi-class text classification
- **Framework:** Hugging Face Trainer API
- **Metric:** Accuracy

The training process uses configurable hyperparameters such as:

- Number of epochs
- Batch size
- Learning rate
- Warmup ratio
- Weight decay
- Maximum sequence length

## Example Use Cases

A model like this could support practical applications such as:

- Automatically categorizing incoming news or articles
- Routing content to the right teams or business units
- Tagging documents in knowledge systems
- Supporting analytics on media, trends, and topic volume
- Building the foundation for more advanced NLP workflows

## Business Relevance

This project shows how modern NLP tools can be used to turn unstructured text into structured, actionable information. It demonstrates core skills in transformer-based modeling, workflow design, and applied AI implementation using industry-standard tools.

## Next Steps

Potential future improvements include:

- Testing larger transformer checkpoints
- Comparing DistilBERT against traditional ML baselines
- Adding precision, recall, and F1-score evaluation
- Using custom text datasets from business or industry contexts
- Deploying the classifier through an API or lightweight app

## File

- `distilbert_news_classification.ipynb` — notebook containing data loading, tokenization, model fine-tuning, evaluation, and inference

## Note

This project was originally developed as graduate coursework and is being shared as part of my technical portfolio to demonstrate applied NLP, transformer fine-tuning, and practical machine learning workflow development.

## Author

Christopher Paul
