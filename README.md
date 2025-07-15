# SMS Spam Detection using Machine Learning

This project implements a machine learning model to detect spam SMS messages using the Multinomial Naive Bayes algorithm with TF-IDF vectorization. The model classifies messages as either "ham" (not spam) or "spam" based on their text content.

## 📁 Dataset

- Dataset: `spam.csv` (uploaded locally)
- Columns used:
  - `v1`: Label (`ham` or `spam`)
  - `v2`: Text message

## ⚙️ Features

- Text preprocessing using **TF-IDF**
- Label encoding for categorical labels
- Model training with **Multinomial Naive Bayes**
- Evaluation using accuracy, confusion matrix, and classification report

## 🚀 How to Run

1. Clone this repository or download the code.
2. Install required libraries:
   ```bash
   pip install pandas scikit-learn
