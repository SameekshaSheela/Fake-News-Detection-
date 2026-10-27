# Fake News Detection

## 📌 Overview

Fake News Detection is a Natural Language Processing (NLP) project that classifies news articles as Real or Fake using Machine Learning and Deep Learning techniques.

The project implements two approaches:
- TF-IDF with Logistic Regression
- Long Short-Term Memory (LSTM)

The models process news text and predict its classification.

## 🎯 Objectives

- Collect and preprocess real and fake news datasets.
- Perform Exploratory Data Analysis (EDA).
- Extract textual features using TF-IDF and tokenization.
- Train and compare Logistic Regression and LSTM models.
- Evaluate model performance using accuracy and training curves.
- Predict the classification of new news articles.

## 📂 Dataset

- **Source:** Kaggle Fake and Real News Dataset
- **Files:** `Fake.csv` and `True.csv`
- **Size:** Approximately 45,000+ news articles
- **Labels:** Fake (0), Real (1)
- **Input Features:** News text and labels

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Environment:** Google Colab
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Natural Language Processing:** NLTK
- **Machine Learning:** Scikit-learn
- **Deep Learning:** TensorFlow, Keras

## ⚙️ Methodology

1. Load, merge, and shuffle the datasets.
2. Clean and preprocess news text.
3. Perform Exploratory Data Analysis.
4. Extract features using TF-IDF and tokenize text for LSTM.
5. Train the Logistic Regression and LSTM models.
6. Evaluate the models using accuracy and training/validation curves.
7. Use the trained models to classify new news articles.

## 🤖 Models Implemented

### 1. TF-IDF + Logistic Regression

TF-IDF converts news text into numerical features. Logistic Regression uses these features to classify articles as fake or real.

### 2. LSTM (Long Short-Term Memory)

The LSTM model processes tokenized text sequences to learn sequential patterns and support news classification.

## 📊 Results

- Logistic Regression provides a baseline for news classification.
- The LSTM model learns patterns from sequential text data.
- Training and validation accuracy and loss curves are used to examine model performance.

*Note: Exact accuracy values are not included because they were not provided in the project documentation.*

## 🌐 Applications

- News verification and analysis
- Social media content moderation
- Misinformation awareness
- Educational and research purposes

## 🚀 Future Enhancements

- Explore BERT and other transformer-based models.
- Develop a web application using Flask or Streamlit.
- Support multilingual fake news detection.
- Experiment with ensemble learning approaches.

## 📝 Conclusion

This project demonstrates the application of Natural Language Processing, traditional Machine Learning, and Deep Learning techniques to fake news classification using TF-IDF, Logistic Regression, and LSTM.

---
