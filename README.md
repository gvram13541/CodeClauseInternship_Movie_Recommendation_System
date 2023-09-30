# CodeClauseInternship_Movie_Recommendation_System
My CodeClause Internship Movie Recommender System Project

## Movie Recommender System:
A content-based movie recommender system that provides personalized movie recommendations based on user preferences and movie features.

## Dataset:
The dataset was imported from Kaggle datasets.
dataset link: https://www.kaggle.com/datasets/ashishjangra27/imdb-movies-dataset

## About the Model:
1. The model was built with 'Term Frequency-Inverse Document Frequency' since this vectorizer counts the frequency of words and gives most related recomendations.
2. TF-IDF (Term Frequency-Inverse Document Frequency) is a numerical statistic that reflects the importance of a word within a document relative to a collection of documents (corpus). It is commonly used in various natural language processing tasks, such as text classification, information retrieval, and text mining. The TF-IDF Vectorizer is a tool that converts a collection of text documents into numerical feature vectors based on TF-IDF values.
3. I limited the training dataset to 10,000 rows due to computational constraints, as processing larger datasets resulted in significant increases in training time.
