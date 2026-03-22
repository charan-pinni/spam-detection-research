# 📩 Multilingual Spam Detection using Transformer Embeddings and Metaheuristic Optimization

---

## 🎯 Objective

To develop a robust and generalizable spam detection system for **multilingual SMS data**, and to evaluate the effectiveness of **transformer-based embeddings** compared to traditional **TF-IDF features**.

---

## 📌 Overview

This project focuses on spam detection in **multilingual and low-resource environments**, with a special emphasis on **Hindi and mixed-language datasets**.

We extend traditional machine learning pipelines by integrating **multilingual sentence embeddings** and **metaheuristic optimization techniques**, and evaluate performance using **rigorous cross-validation and multiple metrics**.

---

## ⚙️ Methodology

### 🔹 1. Baseline Model (Traditional Approach)

* Feature Extraction: **TF-IDF**
* Feature Selection: **XGBoost**
* Classifier: **Logistic Regression**
* Optimization: **Metaheuristic Algorithms (CSA + ABC inspired tuning)**
* Evaluation:

  * 10-Fold Stratified Cross-Validation
  * Metrics: Accuracy, Precision, Recall, F1-score

---

### 🔹 2. Proposed Model (Multilingual Approach)

* Feature Extraction: **Sentence Transformers**

  * Model: `paraphrase-multilingual-MiniLM-L12-v2`
* Feature Selection: **XGBoost**
* Classifier: **Logistic Regression**
* Optimization: **Metaheuristic Algorithms**
* Key Advantage:

  * Captures **semantic meaning across multiple languages**
  * Supports **cross-lingual generalization**

---

## 🔬 Experimental Setup

* Dataset:

  1. IIIT-D Multilingual Spam Dataset (Hindi + English)
     * ~2000–5000 SMS samples
  2. reatiny/chinese-spam-10000
     * contains 10000 spam records in mandarin
     * it is balanced
* Evaluation Strategy:

  * **10-Fold Stratified Cross-Validation**
* Metrics:

  ```text
  Accuracy
  Precision
  Recall
  F1-score
  ```

---

## 📊 Results

| Model                     | Accuracy | Precision | Recall | F1 Score |
| ------------------------- | -------- | --------- | ------ | -------- |
| TF-IDF + LR (Baseline)    | ~0.88    | ~0.86     | ~0.84  | ~0.85    |
| Embedding + LR (Proposed) | ~0.94    | ~0.93     | ~0.91  | ~0.92    |

---

## 📈 Key Findings

* TF-IDF performs well on **monolingual or translated datasets**
* Multilingual embeddings provide:

  * Better **semantic understanding**
  * Improved **F1-score (important for imbalanced data)**
* Transformer-based embeddings are more suitable for:

  * **Low-resource languages**
  * **Cross-lingual spam detection**

---

## 🔍 Ablation Study

We evaluated the impact of different components:

* TF-IDF vs Multilingual Embeddings
* Feature size variations (50, 200, 500)
* Model performance under cross-validation

Results show that **embeddings consistently improve robustness and generalization**.

---

## 🧠 Research Contribution

* Comparative analysis of:

  * Traditional NLP (TF-IDF)
  * Modern NLP (Transformer embeddings)
* Integration of:

  * **Metaheuristic optimization**
  * **Feature selection (XGBoost)**
* Evaluation using:

  * **Cross-validation + multi-metric analysis**

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* XGBoost
* Sentence Transformers
* NumPy, Pandas
* Matplotlib, Seaborn

---

## 📊 Visualizations

* Model comparison graphs
* Confusion matrices
* Cross-validation performance plots

---

## 🚀 Future Work

* Cross-lingual evaluation:

  * Train in English → Test in Hindi
* Use advanced models:

  * XLM-RoBERTa, IndicBERT
* Fine-tuning transformer models
* Deployment:

  * Web-based spam detection system
* Extend to:

  * Telugu, Tamil, and other Indian languages

---

## 👨‍💻 Author

**Charan Pinniboyina**

---

## 📂 Project Structure

```text
├── data/
├── notebooks/
├── results/
├── README.md
```

---

## ⭐ Status

✔ Completed implementation
✔ Comparative analysis done
✔ Ready for research paper writing
