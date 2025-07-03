# Twitter Sentiment Analysis 🐦🔍

This is a mini project that performs sentiment analysis on Twitter data using Natural Language Processing (NLP) and machine learning techniques.

---

## 📌 Overview

The objective of this project is to classify tweets into three sentiment categories:  
**Positive**, **Neutral**, and **Negative**.

---

## 📂 Dataset

- **Source**: Kaggle Twitter Sentiment Dataset  
- The original dataset had no headers, and some tweets with irrelevant sentiment labels. These were cleaned and removed during preprocessing.

---

## 🧹 Data Preprocessing

- Added column names manually
- Removed rows with irrelevant sentiments
- Text preprocessing included:
  - Lowercasing
  - Removing punctuation and special characters
  - Tokenization
  - Stop word removal 
- Applied **TF-IDF Vectorization** to convert text into numerical format

---

## 🤖 Model Building

- Split the data using `train_test_split`
- Trained a **Logistic Regression** model for classification
- Evaluated performance using a **classification report**

---

## 📈 Results

```
text     precision  recall  f1-score  support
Negative  0.80       0.80    0.80      4509
Neutral   0.71       0.71    0.71      3650
Positive  0.78       0.77    0.78      4180

 accuracy 0.77 12339

 macro avg 0.76 0.76 0.76 12339
 weighted avg 0.77 0.77 0.77 12339
```



---

## 🧪 Sample Prediction

Predicted sentiment of new, custom input tweets using the trained model.

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- scikit-learn
- TF-IDF Vectorizer
- Logistic Regression

