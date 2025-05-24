# Toxic Comment Classification

The goal of this project is to develop a machine learning model for classifying toxic comments. The objective is to detect and categorize various types of toxicity such as threats, profanity, insults, and identity-based hate.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)

## Project Overview

Toxic comments on online platforms can significantly harm users and communities. This project leverages Natural Language Processing (NLP) techniques to build a reliable classifier capable of automatically detecting and flagging toxic comments.

## Dataset

The dataset used in this project consists of comments labeled with different types of toxicity. The dataset is sourced from [Kaggle's Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge).

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/toxic-comments-classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd toxic-comments-classification
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To use the model and reproduce the results, open and run the Jupyter Notebook `toxic comments classify-en.ipynb`.

## Model Training

The model training process includes the following steps:

1. **Data Preprocessing**: Cleaning and preparing the textual data for modeling.
2. **Feature Extraction**: Using techniques such as TF-IDF or word vectorization.
3. **Model Building**: Training a machine learning model using algorithms such as Logistic Regression, SVM, or deep learning models.
4. **Hyperparameter Tuning**: Optimizing model performance using methods like Grid Search or Random Search.

## Evaluation

The model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Evaluation results are provided in the `toxic comments classify-en.ipynb` notebook.

## Results

As a result, linear regression showed the best performance compared to decision trees, achieving an F1-score of 0.75 on the validation set and 0.74 on the test set with 95% accuracy. Detailed results are available in the `toxic comments classify-en.ipynb` notebook.