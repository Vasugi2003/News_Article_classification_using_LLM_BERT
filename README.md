**News Category Classification with BERT**

This repository contains a PyTorch implementation of a BERT-based model for classifying news articles into various categories. The model is fine-tuned on a dataset of news headlines and categories and includes TPU/GPU support for efficient training.


**Objective**

The goal of this project is to build a news category classifier using the BERT (Bidirectional Encoder Representations from Transformers) model. BERT is fine-tuned on a news dataset to predict the category of a news headline.

**Dataset**

The dataset used is the "News Category Dataset" from Kaggle, which consists of various news headlines and their corresponding categories. The dataset can be downloaded using the Kaggle API.


**Key Features**

TPU/GPU Support: The code is optimized to run on TPU or GPU using TensorFlow and PyTorch.
Fine-Tuning BERT: The BERT model (bert-base-uncased) is fine-tuned on the news dataset.
Early Stopping: The model training includes an early stopping mechanism to prevent overfitting.
Evaluation: The model is evaluated on a test set with metrics including accuracy, a classification report, and a confusion matrix.
Getting Started
Prerequisites
Python 3.x
TensorFlow
PyTorch
Hugging Face Transformers
Kaggle API
Other dependencies as specified in requirements.txt
