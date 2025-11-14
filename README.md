# 📧 Email Sentinel: Spam Detection Using Machine Learning & NLP

A complete end-to-end machine learning project that detects spam emails using text preprocessing, feature extraction, and classification algorithms.  
This project includes exploratory data analysis (EDA), text cleaning, TF-IDF vectorization, model training, evaluation, and model export.

---

## 🚀 Project Overview

Spam emails continue to be a serious cybersecurity threat, containing scams, phishing attempts, and malicious links.  
This project builds a robust **spam detection pipeline** capable of classifying email messages as **Spam** or **Not Spam** using Machine Learning + Natural Language Processing (NLP).

---

## 🎯 Project Objectives

- Clean and preprocess raw email text data  
- Extract meaningful numerical features using **TF-IDF**  
- Handle class imbalance with **SMOTE**  
- Train and compare multiple ML models  
- Evaluate performance using accuracy, confusion matrix & ROC-AUC  
- Save trained models for deployment  

---

## 🧭 Workflow Summary

### **1. Data Loading & Cleaning**

### **2. Text Preprocessing (NLP):**
- Lowercasing  
- Stopword removal  
- Tokenization  
- Lemmatization  

### **3. Feature Engineering**
- TF-IDF vectorization  
- SMOTE oversampling for imbalance  

### **4. Model Training**
- Logistic Regression  
- Multinomial Naive Bayes  

### **5. Evaluation Metrics**
- Accuracy  
- Precision, Recall, F1  
- Confusion Matrix  
- ROC Curve & AUC Score  

### **6. Model Export**
- Exported using **Joblib** (`.pkl` files)

---

## 🤖 Machine Learning Models Used

### **1️⃣ Logistic Regression**
- Solver: `liblinear`  
- Max Iterations: 2000  
- Stable, interpretable, highly effective for high-dimensional sparse text data  

### **2️⃣ Multinomial Naive Bayes**
- Excellent for text classification  
- Extremely fast  
- Works best with TF-IDF and word frequency data  

---

## 📊 Model Performance (Results)

### **Logistic Regression**
- ✔ High Accuracy  
- ✔ Strong ROC-AUC Score  
- ✔ Balanced learning after SMOTE  

### **Multinomial Naive Bayes**
- ✔ Fastest training  
- ✔ High performance on TF-IDF data  
- ✔ Competitive AUC score  

### **Visual Results**
- Confusion Matrix for both models  
- ROC Curve comparing LR vs NB  
- AUC values displayed on plots  

### **Exported Models**

| Model                | File Name                         |
|---------------------|-----------------------------------|
| Logistic Regression | `logistic_regression_model.pkl`   |
| Naive Bayes         | `naive_bayes_model.pkl`           |

---

## 🛠 Tools & Technologies

### **Programming Language**
- Python

### **Core Libraries**
- **pandas** – Data handling  
- **numpy** – Numerical operations  
- **matplotlib / seaborn** – Visualization  
- **sklearn** – ML models, evaluation, vectorization  
- **SMOTE (imblearn)** – Class balancing  
- **joblib** – Saving models  

---

## 🔮 Future Improvements

- Add more NLP features (bigrams, trigrams)  
- Integrate Deep Learning models (LSTM, BERT)  
- Build a REST API for deployment  
- Create a Streamlit UI for live email classification  

---

## 🙌 Contributions

Contributions are welcome!  
Feel free to open issues, fork the repo, and submit pull requests.

---



## 👤 Author
**Om Patil**  
📧 *Data Science & Machine Learning Enthusiast*  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)  
👨‍💻 [GitHub Profile](https://github.com/OmPatil2806)
