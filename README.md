# Amazon Product Review Sentiment & Helpfulness Analysis

## Project Overview
This project uses Python and Machine Learning to analyze Amazon product reviews. It covers the full data science lifecycle, from data cleaning and preprocessing to building predictive models for Sentiment Analysis and Review Helpfulness.

## Key Features
- **Sentiment Classification:** Predicted "Positive" vs. "Negative" reviews with **87% accuracy** using Logistic Regression and TF-IDF vectorization.
- **Helpfulness Prediction:** Addressed extreme class imbalance (98% helpful vs 2% unhelpful) using **undersampling** to build a fair classification pipeline.
- **NLP Pipeline:** Implemented custom text cleaning, stop-word removal, and TF-IDF feature extraction.
- **Comparative Analysis:** Evaluated Logistic Regression vs. Naive Bayes across two different target variables.

## Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## Results
The Logistic Regression model consistently outperformed Naive Bayes, particularly when integrating numerical features (like star ratings) alongside text data using Scikit-Learn Pipelines.