# Text Sentiment Analysis using NLP

## 📌 Overview
This project implements an end-to-end **Text Sentiment Analysis** system using **Natural Language Processing (NLP)** and **Machine Learning**.  
The goal is to classify tweets into **Positive**, **Negative**, or **Neutral** sentiments.

The project follows a complete NLP pipeline including data preprocessing, feature extraction, model training, evaluation, and visualization.

---

## 📊 Dataset
**Twitter US Airline Sentiment Dataset**

- Source: Kaggle  
- Data Type: Tweets related to airline services  
- Classes:
  - Positive
  - Negative
  - Neutral

**Key Columns Used:**
- `text` – Tweet content
- `airline_sentiment` – Sentiment label

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- NLTK  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Removed unnecessary columns
- Converted text to lowercase
- Removed URLs, mentions, punctuation, and stopwords
- Applied lemmatization

### 2. Feature Extraction
- Used **TF-IDF (Term Frequency–Inverse Document Frequency)**
- Converted text data into numerical vectors

### 3. Model Training
Two machine learning models were trained:
- Logistic Regression
- Naive Bayes

### 4. Model Evaluation
Models were evaluated using:
- Accuracy score
- Classification report
- Confusion matrix

### 5. Visualization
- Sentiment distribution
- Model accuracy comparison
- Confusion matrices
- Tweet length vs sentiment analysis

---

## 📈 Results

| Model | Accuracy |
|------|---------|
| Logistic Regression | **78.55%** |
| Naive Bayes | 74.55% |

**Best Model:** Logistic Regression  
(Logistic Regression performed better and was selected as the final model.)

---




