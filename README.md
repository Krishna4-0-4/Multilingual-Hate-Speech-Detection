# 🌍 Multilingual Hate Speech Detection using Machine Learning

## 📌 Overview

This project presents a multilingual hate speech detection system capable of classifying text into **Hate Speech** and **Non-Hate Speech** categories using classical Machine Learning techniques.

The project combines multilingual datasets consisting of **English, Hindi, and Marathi** text and evaluates multiple machine learning algorithms to identify the best-performing classifier.

---

## 🚀 Features

* Multilingual hate speech classification
* Binary text classification
* Data preprocessing and feature engineering
* TF-IDF and CountVectorizer feature extraction
* Comparison of multiple Machine Learning models
* Hyperparameter tuning using GridSearchCV
* Experimental evaluation using GloVe embeddings
* Manual prediction on unseen text

---

## 📊 Dataset

The dataset was created by combining multilingual hate speech datasets containing English, Hindi, and Marathi text.

Each sample is classified into one of two categories:

* Hate Speech
* Non-Hate Speech

The dataset was cleaned, merged, shuffled, and preprocessed before model training.

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

* Handling missing values
* Label encoding
* Dataset merging
* Text cleaning
* TF-IDF Vectorization
* CountVectorizer representation
* Train-Test Split

---

## 🤖 Models Evaluated

The following machine learning models were implemented and compared:

* Multinomial Naive Bayes (CountVectorizer)
* Multinomial Naive Bayes (TF-IDF)
* Logistic Regression
* Linear Support Vector Machine (Linear SVM)
* XGBoost
* Linear SVM with GloVe Word Embeddings

---

## 📈 Results

Among all evaluated models, **Linear SVM** achieved the best performance with an accuracy of approximately **90.79%** after hyperparameter tuning.

The project also compares the performance of multiple classical machine learning approaches for multilingual hate speech classification.

---

## 🛠️ Technologies Used

* Python
* NumPy
* pandas
* scikit-learn
* XGBoost
* Google Colab
* TF-IDF
* CountVectorizer
* GloVe Word Embeddings

---

## 📂 Repository Structure

```text
Multilingual-Hate-Speech-Detection/
│
├── Multilingual_Hate_Speech_Detection.ipynb
├── Multilingual_Hate_Speech_Dataset.xlsx
├── Project_Presentation.pdf
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/Krishna4-0-4/Multilingual-Hate-Speech-Detection.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook in Google Colab or Jupyter Notebook.

4. Execute all cells sequentially.

---

## 👥 Team

This project was developed as a **team of five members**.

### My Contributions

* Dataset collection and annotation
* Data preprocessing
* Feature engineering
* Training and evaluating machine learning models
* Experimental comparison of different classifiers
* Project documentation and presentation

---

## 🔮 Future Improvements

* Deep Learning based approaches (LSTM/BiLSTM)
* Transformer models such as BERT
* Real-time web application using Streamlit
* REST API deployment
* Support for additional regional languages

---

## 📄 License

This project is intended for educational and research purposes.
