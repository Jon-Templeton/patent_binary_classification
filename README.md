# Patent Binary Classification Project

## Overview

This project comprises two Jupyter notebooks demonstrating binary classification of patents using different approaches: Natural Language Processing (NLP) and Logistic Regression. Both models are built and evaluated on the publicly available Google patents dataset, focusing on different feature sets.

### Notebooks:

1. **Patent Binary Classification: NLP**
2. **Patent Binary Classification: Linear Regression**



## 1. Patent Binary Classification: NLP

#### Description
This notebook focuses on classifying patents into binary categories using NLP techniques. It leverages the `distilbert-base-uncased` model from Hugging Face for patent text analysis.

#### File
[patent_nlp_classification.ipynb](project_files/patent_nlp_classification.ipynb)

#### Steps:
- Data Loading & Cleaning
- Downsampling Data
- Data Preparation & Tokenization
- Evaluation Metrics Setup
- Model Initialization & Training Configuration
- Model Training & Evaluation

#### Key Highlights
- **Model**: Pretrained BERT model (`distilbert-base-uncased`).
- **Dataset**: Combination of title and abstract columns from patent dataset.
- **Performance Metrics**: Accuracy, Precision, Recall, F1 Score.


## 2. Patent Binary Classification: Linear Regression

#### Description
This notebook employs logistic regression to classify patents. It focuses on the 'cpc_first_4' column of the dataset to make predictions.

#### File
[patent_linear_regression.ipynb](project_files/patent_linear_regression.ipynb)

#### Steps:
- Data Loading and Cleaning
- Data Preprocessing
- Model Training
- Model Evaluation

#### Key Highlights
- **Model**: Logistic Regression.
- **Dataset**: 'cpc_first_4' and 'labels' columns from patent dataset.
- **Performance Metrics**: Accuracy, Precision, Recall, F1 Score.
