# KNN from Scratch Flower and News Classification with Custom Evaluation Metrics
This repository contains a Python implementation of the **K-Nearest Neighbors (KNN)** classification algorithm from scratch. It also includes custom implementations of key evaluation metrics and applies the classifier to both the Iris flower dataset and a custom News dataset (sports vs. politics).

---

## Features

- KNN algorithm implemented without using machine learning libraries.
- Custom evaluation metrics:
  - Accuracy
  - Confusion Matrix
  - Precision
  - Recall
  - F1-Score
- Text vectorization using TF-IDF for the News dataset.
- Parameter tuning for the optimal number of neighbors (*k*) and train-test split ratio.
- Performance comparison with Scikit-learn's KNN classifier.

---

## Datasets

- **Iris Dataset:** Classic machine learning dataset with 150 flower samples classified into 3 species.
- **News Dataset:** Custom dataset containing 50 sports and 50 politics news article sentences labeled accordingly.

---

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/knn-from-scratch.git
cd knn-from-scratch
