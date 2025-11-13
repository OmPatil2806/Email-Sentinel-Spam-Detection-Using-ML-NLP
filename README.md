# Email-Sentinel-Spam-Detection-Using-ML-NLP


## 📌 Project Overview
This project implements an **email spam detection system** using Natural Language Processing (NLP) and Machine Learning. It classifies emails as **spam** or **ham (non-spam)** using a combination of text preprocessing, feature engineering, and machine learning models. The workflow includes:

- Text cleaning, tokenization, lemmatization, and stopword removal  
- Feature engineering: total words, message length, capitalized words, spam keywords, rare words   
- Handling class imbalance using **SMOTE**  
- Model training using **Logistic Regression** and **Multinomial Naive Bayes**  
- Model evaluation using **Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC Curve**  
- Saving trained models for future use

---

## 📊 Data Source
The dataset used in this project is publicly available on **Kaggle**:  
[Email Spam Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

The dataset contains word frequencies from emails along with a `Prediction` column indicating spam (1) or non-spam (0).

---

## 🛠️ Tools & Libraries
- **Python 3.x**  
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn, WordCloud  
- **NLP & Text Processing:** NLTK, TextBlob  
- **Machine Learning:** Scikit-learn (Logistic Regression, Multinomial Naive Bayes)  
- **Data Balancing:** Imbalanced-learn (SMOTE)  

---

## 🧰 Models Used
- **Logistic Regression** – predicts spam using TF-IDF and engineered features  
- **Multinomial Naive Bayes** – suitable for count-based text features  

Both models are trained, evaluated, and saved as `.pkl` files for future use.

---


## 📈 Visualization
- Word clouds for spam emails  
- Histograms and boxplots for message length distribution  
- Confusion matrices for model performance  
- ROC curves to compare models  

---

## 👤 Author
**Om Patil**  
📧 *Data Science & Machine Learning Enthusiast*  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)  
👨‍💻 [GitHub Profile](https://github.com/OmPatil2806)
