This repository contains a Fake News Detection System built using Logistic Regression. The system is designed to classify news articles as either fake or real based on their textual content. It leverages machine learning techniques to analyze and predict the authenticity of news, helping users discern misinformation.

Features:
Preprocessing of text data (removing stopwords, stemming, tokenization)
Vectorization using TF-IDF (Term Frequency-Inverse Document Frequency)
Logistic Regression model for binary classification
Model evaluation using metrics like accuracy, precision, recall, and F1-score
Simple and intuitive interface for classifying news articles

Technologies Used:
Python
Pandas and NumPy for data manipulation
Scikit-learn for machine learning algorithms
NLTK for text preprocessing
Streamlit for creating a web-based interface (if applicable)

Dataset Link - https://www.kaggle.com/c/fake-news/data?select=train.csv

To Run the file following steps should be done -

   1. open terminal and run -> pip install streamlit and if you are using python3 run -> pip3 install streamlit
   2. Check If Streamlit is Installed
Run this command:
pip list | findstr streamlit  # For Windows
pip list | grep streamlit     # For Mac/Linux
If it's not listed, the installation failed.
  3.  Run Your App by : streamlit run app.py





      


