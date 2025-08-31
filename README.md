# Sentiment Analysis on IMDB Movie Reviews

This repository contains a basic end-to-end workflow for sentiment analysis on the IMDB movie reviews dataset.  
The project covers text cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, and vectorization.

---

## 1. Text Cleaning
- Converted text to lowercase  
- Removed leading and trailing spaces  
- Removed HTML tags  
- Removed URLs  
- Expanded common abbreviations  
- Corrected spelling mistakes  
- Removed punctuation  
- Removed special characters  

---

## 2. Text Preprocessing
- Tokenization (while keeping text as strings)  
- Removed stopwords  

---

## 3. Exploratory Data Analysis (EDA) and Feature Engineering

### Review Length Distribution
![Review Length Distribution](images/review_length_distribution.png)

### Word Count Distribution
![Word Count Distribution](images/word_count_distribution.png)

### Common Unigrams
![Top Unigrams](images/top_unigrams.png)

### Common Bigrams
![Top Bigrams](images/top_bigrams.png)

### Common Trigrams
![Top Trigrams](images/top_trigrams.png)

### WordClouds
**Positive Reviews**
![Positive WordCloud](images/positive_wordcloud.png)

**Negative Reviews**
![Negative WordCloud](images/negative_wordcloud.png)

---

## 4. Vectorization
- Applied Bag of Words (BoW) to convert text data into numerical features  
- Example shape of feature matrix: `(n_samples, 5000)`  

---

## 5. Tools and Libraries Used
- **Python**  
- **Pandas, NumPy**  
- **NLTK, re (regex)**  
- **Scikit-learn**  
- **Seaborn, Matplotlib**  
- **WordCloud**  

---

## 6. Project Structure
