# Sentiment Analysis of Book Reviews

This project uses Natural Language Processing (NLP) and Machine Learning to classify customer reviews as **positive** or **negative** based on their content.

## Tools Used
- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn (Logistic Regression, TF-IDF)
- NLTK for text preprocessing
- WordCloud for visualization

## Key Features
- Full EDA on review scores, helpfulness, and review length
- Text preprocessing and TF-IDF vectorization
- Logistic Regression for sentiment classification
- Model accuracy: **93%**
- Confusion matrix and classification report for performance insight
- WordClouds for visualizing frequent terms in positive and negative reviews

## Dataset
The dataset contains Amazon-style product reviews with `Score`, `Text`, and `Summary`. Due to size, only a small sample is included.
Here's the link to full dataset: https://www.kaggle.com/code/gpayen/building-a-prediction-model/input

## Files
- `sentiment_analysis.ipynb` — Main notebook
- `reviews_sample.csv` — Sample data
- `positive_vs_negative.png` — Dominant words for positive & negative reviews
- `sentiment_confusion_matrix.png` — Confusion matrix for this model
- `README.md` — This file

---
