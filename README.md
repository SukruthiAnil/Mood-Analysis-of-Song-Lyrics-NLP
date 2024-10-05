# Mood-Analysis-of-Song-Lyrics-NLP

**Abstract:-**
MelodyMood is a project aimed at classifying the mood of songs based solely on their lyrics. Through natural language processing and machine learning techniques, we analyze whether a song's lyrics evoke a "Happy" or "Sad" mood. This classification has potential applications in enhancing music recommendation systems, creating mood-based playlists, and designing soundtracks for film and other media.

**Project Overview:-**

The goal of this project is to use sentiment analysis and data mining techniques to classify the mood of song lyrics. We utilize the Million Song Dataset in conjunction with the musiXmatch dataset to obtain lyrics and song metadata. Using various machine learning models and feature extraction methods, we aim to predict a song's mood based on its lyrics.

**Dataset:-**

We used a subset of the Million Song Dataset, which includes:

Song metadata such as title, artist, year, and duration.

Audio features like tempo, danceability, and energy.

Lyrics obtained through song lyrics APIs.

**Data Preprocessing:-**

Text Case Lowering

Punctuation Removal

Tokenization

Stop Words Removal

Lemmatization

Feature Extraction: TF-IDF, Count Vectorizer, Word Embeddings.

**Models Used:- **

Random Forest

Decision Tree

Naive Bayes

XGBoost

**Results:- **

The Random Forest model using Sentence BERT vectorizer achieved the highest accuracy of 94.2%. This demonstrates the effectiveness of using advanced NLP techniques for mood analysis of song lyrics.

**Key Features:- **
  **Sentiment Analysis:** Classifying lyrics as "Happy" or "Sad".
  **Manual Labeling:** Songs were manually labeled to create the target classes.
  **Online Web App:** A simple interface for mood prediction based on song lyrics.
