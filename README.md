# 📩 Spam Detection Research

**Multi-lingual Spam Detection using Metaheuristic Algorithms + Sentence Transformers**

---

## 🎯 Objective
Develop an efficient spam detection model for multilingual SMS data and improve performance over traditional approaches.

---

## 📌 Overview
This project focuses on detecting spam messages in **low-resource and multilingual datasets** (including Hindi). It improves baseline performance using advanced NLP techniques and optimization methods.

---

## ⚙️ Methodology

### 1. Baseline Model
- Dataset: ~5000 SMS messages (spam + ham)
- Data was **imbalanced**
- Applied:
  - Text preprocessing
  - TF-IDF vectorization
  - XgBoost
  - metaheuristic algorithms + Logistic Regression
- Evaluated using confusion matrix

### 2. Improvements
- Used **Sentence Transformers** for multilingual embeddings
- Dataset: ~2000 SMS messages (spam + ham) original hindi data(IIT-D spam-dataset)
- Applied **metaheuristic algorithms + Logistic Regression**
- Performed:
  - Feature selection (XGBoost)
  - Model tuning
- Focused on improving performance on multilingual data

---

## 📊 Results

| Model     | Accuracy | F1 Score |
|----------|---------|---------|
| Baseline | 88%     | 0.85    |
| Improved | 94%     | 0.92    |

---

## 🚀 Key Highlights
- Works on **real-world multilingual data**
- Handles **class imbalance issues**
- Combines **deep learning + optimization techniques**
- Significant improvement in **F1-score (important for imbalanced data)**

---

## 🛠️ Tech Stack
- Python
- Scikit-learn
- XGBoost
- Sentence Transformers
- Pandas, NumPy

---

## 📈 Future Work
- publish research paper
- Deploy as a web application
- Extend to more Indian languages
- Use transformer fine-tuning (BERT, IndicBERT)
- Real-time spam detection system

---

## 👨‍💻 Author
**Charan Pinniboyina**

## 📂 Project Structure
