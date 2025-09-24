 Bitcoin & Crypto News Text Analysis
 Project Overview

This project performs Natural Language Processing (NLP) and Text Mining on Bitcoin/Cryptocurrency-related news articles. The goal is to uncover sentiment trends, common topics, frequent phrases, and insights from the text data.

The analysis pipeline includes:

Data Preprocessing (cleaning, tokenization, stopword removal)

Sentiment Analysis using TextBlob

Topic Modeling with TF-IDF & NMF

Visualization (Pie charts, Word Clouds, Topic Distributions)

Collocation Analysis (Bigrams & Trigrams)

 Dataset

Input: Excel file containing news articles (spotify review.xlsx → renamed for crypto news data).

Column used: text (news content).

Preprocessing ensures missing/blank rows are dropped before analysis.

Features & Workflow
1. Data Cleaning & Preprocessing

Convert text to lowercase

Remove special characters

Tokenization

Stopword removal (NLTK)

2. Sentiment Analysis

Polarity score (range: -1 to +1)

Subjectivity score (range: 0 to 1)

Classification: Positive, Negative, Neutral

Results exported as sentiment_analysis_results.xlsx

3. Topic Modeling

TF-IDF Vectorization

NMF for extracting 5 key topics

Top keywords per topic

Visualizations: Bar charts + Word Clouds

4. Collocation Analysis

Frequent Bigrams and Trigrams

Helps discover common word patterns in crypto-related discussions

Visualizations

The project generates:

Pie Chart → Distribution of Positive, Negative, Neutral sentiments

Bar Graphs → Top words for each topic

Word Clouds → Highlighting dominant topic words

Bigram & Trigram frequency tables

Technologies & Libraries

Python 3.x

pandas – Data handling

NLTK – Tokenization, stopwords, collocations

TextBlob – Sentiment Analysis

scikit-learn – TF-IDF, NMF Topic Modeling

matplotlib – Visualization

WordCloud – Word clouds
