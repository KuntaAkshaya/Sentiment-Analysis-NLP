# 🧠 Sentiment Analysis using NLP Pipeline & Machine Learning

## 📌 Project Overview
This project demonstrates a complete Natural Language Processing (NLP) pipeline to perform sentiment analysis on text data. The objective is to classify reviews as positive or negative using machine learning models.

---

## 📂 Dataset
The dataset contains:
- `text` → Review text  
- `label` → Sentiment (0 = Negative, 1 = Positive)

---

## 🧹 Data Preprocessing
The following preprocessing steps were applied:
- Converted text to lowercase  
- Removed punctuation and special characters  
- Removed stopwords  
- Applied stemming  

---

## 🔢 Feature Engineering
- Used **TF-IDF Vectorization** to convert text into numerical format  
- Reduced dimensionality using `max_features=5000` for better performance  

---

## 🔀 Train-Test Split
- 80% data used for training  
- 20% data used for testing  

---

## 🤖 Models Used
- Logistic Regression  
- Naive Bayes  
- Decision Tree  

---

## 📊 Model Evaluation

### 🔹 Logistic Regression
**Accuracy: 88.4%**

| Class | Precision | Recall | F1-Score | Support |
|------|----------|--------|---------|--------|
| 0 (Negative) | 0.89 | 0.87 | 0.88 | 3966 |
| 1 (Positive) | 0.88 | 0.89 | 0.89 | 4034 |

---

### 🔹 Naive Bayes
**Accuracy: 84.9%**

| Class | Precision | Recall | F1-Score | Support |
|------|----------|--------|---------|--------|
| 0 (Negative) | 0.85 | 0.84 | 0.85 | 3966 |
| 1 (Positive) | 0.85 | 0.85 | 0.85 | 4034 |

---

### 🔹 Decision Tree
**Accuracy: 71.9%**

| Class | Precision | Recall | F1-Score | Support |
|------|----------|--------|---------|--------|
| 0 (Negative) | 0.72 | 0.72 | 0.72 | 3966 |
| 1 (Positive) | 0.72 | 0.72 | 0.72 | 4034 |

---

## 🧠 Insights
- Logistic Regression achieved the highest accuracy (**88.4%**) and performed best for this dataset.  
- Naive Bayes performed well but assumes feature independence.  
- Decision Tree showed lower performance due to overfitting and difficulty handling high-dimensional data.  
- TF-IDF improved model performance by assigning importance to meaningful words.  
- Preprocessing helped reduce noise and improve overall accuracy.  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NLTK  
- Scikit-learn  

---

## 🚀 Future Improvements
- Hyperparameter tuning  
- Use deep learning models like LSTM or BERT  
- Deploy as a web application  

---

## 👩‍💻 Author
**K. Akshaya**
