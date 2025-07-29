# Tweet Preprocessing for Sentiment Analysis

This repository contains a Jupyter Notebook (`tweet_preprocessing.ipynb`) that documents my learning process in Natural Language Processing (NLP). The focus is specifically on the crucial step of text preprocessing for sentiment analysis using the NLTK (Natural Language Toolkit) Python library. The notebook in this repository demonstrates how to clean and prepare raw tweet data. The content is adapted from a lab in the **"Natural Language Processing with Classification and Vector Spaces"** (DeepLearning.AI) course.

---
The `tweet_preprocessing.ipynb` notebook covers the following key preprocessing steps:

1.  **Setup and Library Imports**: Importing all necessary libraries (NLTK, Matplotlib, re, string) at the beginning for clean and organized code.
2.  **Exploring the Dataset**: Loading and understanding the balanced Twitter sentiment dataset provided by NLTK, including a visual representation of its distribution.
3.  **Looking at Raw Tweets**: Inspecting sample raw tweets to identify characteristics like hyperlinks, hashtags, and emoticons that require special handling.
4.  **Preprocessing Pipeline**: Detailed, step-by-step demonstration of:
    * **Removing Hyperlinks, Twitter Marks, and Styles**: Using regular expressions to clean tweet-specific noise.
    * **Tokenization**: Breaking down text into individual words (tokens) using `TweetTokenizer` and converting them to lowercase.
    * **Removing Stop Words and Punctuation**: Eliminating common, less informative words and standard punctuation.
    * **Stemming**: Reducing words to their root form using the `PorterStemmer` to normalize vocabulary.

---
For details, please refer to the [Jupyter Notebook file.](https://github.com/larisanti/tweet-preprocessing-nlp/blob/main/tweet_preprocessing.ipynb)
