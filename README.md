# 🍽️ Amazon Food Reviews — Sentiment Analysis - using NLP & Deep Learning

## 📌 Project Overview

This project focuses on building an end-to-end **Sentiment Analysis system** using the Amazon Fine Food Reviews dataset.

The project applies **Natural Language Processing (NLP), Text Data Mining (TDM), Machine Learning, and Deep Learning** techniques to classify customer reviews into sentiment categories.

Multiple models are developed and compared to understand the performance of traditional Machine Learning versus Deep Learning approaches for text classification.

---

## 🎯 Objectives

* Analyze customer reviews and identify sentiment patterns.
* Perform text preprocessing and Natural Language Processing.
* Convert textual data into numerical representations using **Text Data Mining (TDM)** techniques.
* Build a traditional Machine Learning sentiment classifier.
* Build and compare multiple Deep Learning architectures.
* Evaluate models using appropriate classification metrics.
* Identify the best-performing model for sentiment classification.

---

## 📊 Dataset

**Dataset:** Amazon Food Reviews

The dataset contains customer reviews of food products purchased on Amazon.

### Important Features

| Feature     | Description                  |
| ----------- | ---------------------------- |
| `Text`      | Customer review text         |
| `Score`     | Rating given by the customer |
| `Summary`   | Short summary of the review  |
| `Time`      | Review timestamp             |
| `ProductId` | Product identifier           |
| `UserId`    | User identifier              |

The **Score** is used to derive sentiment labels from the customer ratings.

---

## 🧠 Project Workflow

```text
Amazon Food Reviews
          ↓
Data Collection & Understanding
          ↓
Data Cleaning
          ↓
Exploratory Data Analysis
          ↓
Sentiment Label Creation
          ↓
Text Preprocessing
          ↓
Tokenization / Vectorization
          ↓
Text Data Mining (TDM)
          ↓
Train-Test Split
          ↓
 ┌─────────────────────────────┐
 │      Model Development      │
 └─────────────────────────────┘
          ↓
 ┌─────────────────────────────┐
 │ Logistic Regression         │
 │ Dense Neural Network        │
 │ Simple RNN                  │
 │ LSTM                        │
 │ Bidirectional LSTM          │
 └─────────────────────────────┘
          ↓
Model Evaluation
          ↓
Model Comparison
          ↓
Best Model Selection
```

---

## 🔧 Technologies & Tools

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### NLP

* NLTK
* Text preprocessing
* Tokenization
* Stopword removal
* Lemmatization/Stemming
* Text Data Mining

### Machine Learning

* Scikit-learn
* Logistic Regression

### Deep Learning

* TensorFlow
* Keras
* Dense Neural Network
* Simple RNN
* LSTM
* Bidirectional LSTM

### Development Environment

* Jupyter Notebook
* GitHub

---

## 🤖 Models Implemented

### 1. Logistic Regression

A traditional Machine Learning classification model is implemented using text features generated through TDM/vectorization techniques.

### 2. Dense Neural Network

A fully connected neural network is developed to learn nonlinear patterns from the numerical representation of the reviews.

### 3. Simple RNN

A Recurrent Neural Network is used to capture sequential dependencies within review text.

### 4. LSTM

Long Short-Term Memory networks are implemented to better capture long-term dependencies in customer reviews.

### 5. Bidirectional LSTM

A Bidirectional LSTM processes text in both forward and backward directions to capture contextual information from both sides of a sequence.

---

## 📈 Model Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

A final comparison is performed to determine which architecture provides the best sentiment classification performance.

### Model Comparison

| Model                | Accuracy | Precision | Recall | F1-Score |
| -------------------- | -------: | --------: | -----: | -------: |
| Logistic Regression  |      88% |      0.74 |   0.67 |     0.70 |
| Dense Neural Network |      90% |      0.74 |   0.79 |     0.75 |
| Simple RNN           |      82% |      0.34 |   0.49 |     0.35 |
| LSTM                 |      91% |      0.70 |   0.82 |     0.74 |
| Bidirectional LSTM   |      90% |      0.74 |   0.77 |     0.75 |

---

## 🔍 Key NLP Steps

The text preprocessing pipeline includes:

1. Handling missing values
2. Removing duplicate reviews
3. Converting text to lowercase
4. Removing unnecessary characters
5. Removing stopwords
6. Tokenization
7. Lemmatization/Stemming
8. Feature extraction
9. Text vectorization
10. Preparing sequences for Deep Learning models

---
## 🏆 Conclusion

Among all the evaluated models, **LSTM achieved the best overall performance
with 91% accuracy and a weighted F1-score of 0.92**.

The results indicate that LSTM was able to capture sequential and contextual
information from customer reviews effectively. Although the Dense Neural
Network and Bidirectional LSTM achieved 90% accuracy, they slightly
underperformed LSTM in terms of overall accuracy and weighted F1-score.

The dataset contains significant class imbalance, with Class 3 having
substantially more observations than the other classes. Therefore, accuracy
was considered along with precision, recall, and F1-score when selecting the
final model.

**Final Model: LSTM**  
**Final Accuracy: 91%**  
**Weighted F1-Score: 0.92**


## 📁 Project Structure

```text
amazon-food-sentiment-analysis-using-NLP-&-Deep-Learning/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── Amazon_Food_Sentiment_Analysis.ipynb
│
├── models/
│   └── README.md
|
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 💡 Key Learning Outcomes

Through this project, I explored:

* End-to-end NLP workflow
* Text Data Mining
* Text preprocessing
* Feature engineering for text
* Traditional Machine Learning for NLP
* Neural Network-based text classification
* Sequence modeling
* RNN and LSTM architectures
* Bidirectional LSTM
* Model evaluation and comparison

---

## 🚀 Future Improvements

Potential improvements include:

* Transformer-based models such as BERT
* Transfer Learning
* Word embeddings such as Word2Vec and GloVe
* Attention mechanisms
* Hyperparameter tuning
* Deployment using Streamlit or Flask
* Real-time sentiment prediction API

---

## 👩‍💻 Author

**Shristi Kumari**

Aspiring Data Analyst / Data Scientist

### Skills

`Python` `SQL` `Excel` `Power BI` `Machine Learning` `NLP` `Deep Learning` `Generative AI`
