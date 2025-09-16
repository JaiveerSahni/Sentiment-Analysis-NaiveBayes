# Sentiment Analysis using Naive Bayes  

This project demonstrates **sentiment analysis** on the [IMDB Movie Reviews dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews), using **Naive Bayes classification**. The goal is to classify reviews as **positive** or **negative** after text preprocessing and model training.  

## 📂 Project Structure  
- **Dataset**: IMDB dataset of 50,000 movie reviews  
- **Notebook**: `sentiment-analysis-using-naive-bayes.ipynb`  
  - Data loading & exploration  
  - Text preprocessing (cleaning, lowercasing, removing HTML, stopwords, punctuation, etc.)  
  - Feature extraction using **Bag-of-Words / TF-IDF**  
  - Training a **Naive Bayes classifier**  
  - Model evaluation using accuracy and confusion matrix  

## 🚀 Steps Implemented  
1. **Data Preprocessing**  
   - Cleaning HTML tags and special characters  
   - Converting text to lowercase  
   - Removing stopwords & punctuation  
   - Tokenization  

2. **Feature Engineering**  
   - Converting text into numerical vectors using **CountVectorizer** / **TF-IDF**  

3. **Model Training**  
   - Training **Multinomial Naive Bayes** classifier  
   - Splitting dataset into train/test sets  

4. **Evaluation**  
   - Accuracy score  
   - Confusion matrix  
   - Classification report (Precision, Recall, F1-score)  


