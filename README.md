# KNN from Scratch Flower and News Classification with Custom Evaluation Metrics

This project demonstrates a custom implementation of the **K-Nearest Neighbors (KNN)** algorithm using Python. It includes performance evaluation with metrics such as **accuracy**, **precision**, **recall**, **F1-score**, and **confusion matrix**, applied to:

- 🌸 The Iris Dataset
- 📰 A custom News Dataset (Sports vs Politics)

---

## 📌 Project Objectives

- Implement KNN from scratch (no external ML libraries).
- Apply it to real-world datasets.
- Evaluate model performance using custom metric functions.
- Compare results with scikit-learn's implementation.

---

## 📊 Datasets Used

### 🌸 Iris Dataset
- Classic dataset with 150 flower samples (Setosa, Versicolor, Virginica).
- Features: Petal length, petal width, etc.
- Multiclass classification.

### 📰 News Dataset
- Custom dataset with 50 sports and 50 politics article snippets.
- Preprocessed using TF-IDF vectorization.
- Binary classification.

---

## ⚙️ Implementation Details

- Distance Metric: **Euclidean Distance**
- Parameters:
  - `k`: Number of neighbors
  - `train-test split`: Adjustable
- Vectorization: `TfidfVectorizer` for text data
- All metrics implemented from scratch.

---

## 📏 Evaluation Metrics

### ✅ Accuracy
Proportion of correct predictions.

(TP+TN)/(TP+TN+FP+FN)

---

### 🎯 Precision
How many predicted positives are actual positives.

TP/(TP+ FP)

---

### 🔁 Recall
How many actual positives were correctly predicted.

TP/(TP+ FP)

---

### 🎯 F1 Score
Harmonic mean of precision and recall.

2{(Precision ×Recall)/(Precision+Recall)}

---

### 📉 Confusion Matrix
Summarizes prediction results.
A table layout that visualizes the performance of the classification model by displaying counts of TP, TN, FP, and FN.

Where:
- TP: True Positive
- TN: True Negative
- FP: False Positive
- FN: False Negative

---
