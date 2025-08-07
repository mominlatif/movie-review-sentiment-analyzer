# 🎬 Movie Review Sentiment Analyzer

## 📝 Objective
This project is an intermediate-level Sentiment Analysis tool that classifies movie reviews as either **Positive** or **Negative** using machine learning techniques. It leverages real-world datasets and evaluates model performance using accuracy and other metrics.

---

## ✅ Features

- Uses **IMDb movie reviews dataset** from **NLTK**
- Text pre-processing and TF-IDF vectorization
- Trains a **Naive Bayes classifier**
- Displays model **accuracy** and **sample predictions**
- ✅ Bonus:
  - Shows a **confusion matrix**
  - Saves trained model using **joblib**

---

## 📁 Dataset

We use the built-in IMDb dataset from NLTK:
```python
from nltk.corpus import movie_reviews
