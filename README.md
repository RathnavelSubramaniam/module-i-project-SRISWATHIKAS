# Stock News Analysis based on Sentiments 📊
## Overview

This project develops an AI-powered system to analyze stock-related news articles, determine market sentiment, and generate weekly news summaries. The insights are combined with historical stock market data to support better investment decisions and improve stock price prediction.

## Business Context

Stock prices are influenced by factors such as financial performance, company developments, and market sentiment. Since news articles can significantly impact investor behavior, analyzing large volumes of financial news manually is challenging. This project uses AI and NLP to automate sentiment analysis and news summarization.

## Objective

The project aims to:

- Analyze the sentiment of stock-related news.
- Generate weekly summaries of financial news.
- Provide actionable insights for financial analysts.
- Support stock price prediction using sentiment information.

## Dataset

* `Date` : The date the news was released
* `News` : The content of news articles that could potentially affect the company's stock price
* `Open` : The stock price (in \$) at the beginning of the day
* `High` : The highest stock price (in \$) reached during the day
* `Low` :  The lowest stock price (in \$) reached during the day
* `Close` : The adjusted stock price (in \$) at the end of the day
* `Volume` : The number of shares traded during the day
* `Label` : The sentiment polarity of the news content
    * 1: positive
    * 0: neutral
    * -1: negative
## Packages
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- genism
- sentence_transformers
- tensorflow


## Workflow

1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Data PreProcessing
4. Train , Test split
5. Model Building using Word2Vec, Sentence Transformers, Random Forest, and Neural Networks

## Conclusions
The project successfully compared multiple embedding techniques and machine learning models for stock news sentiment classification. Contextual sentence embeddings generally captured semantic information more effectively than traditional word embeddings. Among the evaluated models, the best-performing model demonstrated superior classification performance and generalization, making it the preferred choice for financial sentiment analysis.
