# Hate Speech Detection

This NLP project focuses on detecting hate speech using supervised machine learning techniques.  
The dataset, composed of 40,000 English sentences, contains both offensive (“hate”) and non-offensive (“not hate”) examples.

---

## Objective
To build and compare sentiment analysis models able to classify text as hateful or not, and to evaluate how different vectorization methods influence model accuracy.

---

## Methodology

### 1. Preprocessing
- Lowercasing  
- Removing punctuation and stopwords  
- Tokenization and lemmatization using `nltk`  

### 2. Vectorization
Two methods were tested:
- **Bag of Words** using `CountVectorizer`  
- **TF–IDF** using `TfidfVectorizer`

### 3. Machine Learning Models
- **Support Vector Machine (SVM)**  
- **Logistic Regression**

### 4. Evaluation
Accuracy was used as the main metric.  
The best configuration achieved **~0.73 accuracy** using **SVM + Bag of Words**.

---

## Results
Both vectorization methods produced similar results, indicating that for this dataset, model performance is not heavily dependent on the text representation.

---

## Tools & Libraries
- Python  
- scikit-learn  
- nltk  
- pandas, NumPy  
- Jupyter Notebook / Google Colab

---

## Key Skills
Text Preprocessing · Sentiment Analysis · NLP · Machine Learning · Python · TF-IDF · SVM · Logistic Regression

