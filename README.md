# IMDB Movie Review Sentiment Analysis 

An end-to-end Natural Language Processing (NLP) project that builds and evaluates a machine learning model to classify IMDB movie reviews as either positive or negative.

##  Project Overview

This repository contains the complete workflow for a sentiment analysis project on the popular IMDB Movie Review dataset. The goal is to transform unstructured text data into valuable insights by automatically determining the emotional tone of a review. The project demonstrates a full data science lifecycle, from data cleaning and exploration to model training, hyperparameter tuning, and in-depth performance evaluation.

The final result is a highly accurate and optimized Logistic Regression model capable of predicting sentiment with strong performance on unseen data.

---

##  Key Features

-   **Comprehensive EDA:** In-depth exploratory data analysis with visualizations to understand dataset characteristics.
-   **Advanced Text Preprocessing:** A robust cleaning pipeline using NLTK for lemmatization, stopword removal, and text normalization.
-   **TF-IDF Vectorization:** Feature engineering to convert cleaned text into a meaningful numerical representation.
-   **Comparative Model Training:** Systematic evaluation of multiple classifiers (Naive Bayes, SVM, Logistic Regression) to select the best performer.
-   **Hyperparameter Tuning:** Optimization of the chosen model using `GridSearchCV` to maximize its predictive power.
-   **In-depth Evaluation:** Detailed performance analysis using a classification report, confusion matrix, and ROC curve.
-   **Model Interpretability:** Identification and visualization of the most influential words for positive and negative predictions.
-   **Error Analysis:** A closer look at the model's misclassifications to understand its limitations.

---


## Tech Stack

-   **Python 3.8+**
-   **Core Libraries:**
    -   Pandas & NumPy for data manipulation
    -   Scikit-learn for machine learning
    -   NLTK (Natural Language Toolkit) for text preprocessing
    -   Matplotlib & Seaborn for data visualization
-   **Development Environment:** Jupyter Notebook

---

## Setup and Installation

To run this project on your local machine, follow these steps:

**1. Clone the Repository**
```bash
git clone(https://github.com/zkcode29/IMDB-Movie-Review-Sentiment-Analysis-/tree/main).git
cd(https://github.com/zkcode29/IMDB-Movie-Review-Sentiment-Analysis-/tree/main)
