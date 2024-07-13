# Lyrics Recommender System

This project is a Lyrics Recommender System that aims to provide song recommendations based on the lyrics' content. The project involves data preprocessing, exploratory data analysis, and the implementation of a recommendation system using TF-IDF and cosine similarity.

## Introduction
This project leverages Natural Language Processing (NLP) techniques to recommend songs based on their lyrical content. The core idea is to use TF-IDF to convert the lyrics into numerical vectors and then use cosine similarity to find similar songs.

## Dataset
The dataset used in this project contains song lyrics and metadata such as the artist and song title. The primary focus is on the lyrics for generating recommendations.

### Terminologies
- **TF-IDF (Term Frequency-Inverse Document Frequency):** A statistical measure used to evaluate the importance of a word in a document relative to a collection of documents (corpus).
- **Cosine Similarity:** A metric used to measure how similar two vectors are, by calculating the cosine of the angle between them.
- **Recommender System:** A system that provides suggestions for items to be of use to a user. In this case, the items are song lyrics.

## Data Preprocessing
The preprocessing steps include cleaning the lyrics, removing punctuation, converting text to lowercase, and removing stopwords. This ensures that the data is in a suitable format for analysis and model building.

## Exploratory Data Analysis

### Top 10 Artists by Number of Songs
![Screenshot 2024-07-14 040631](https://github.com/user-attachments/assets/f37190c5-5c73-49d1-9b8b-ba0c1db49788)

This bar chart displays the top 10 artists based on the number of songs they have in the dataset. It shows that artists like America, Loretta Lynn, and Kris Kristofferson have the most songs in the dataset.

### Top 20 Words by TF-IDF Score
<img width="559" alt="image" src="https://github.com/user-attachments/assets/a0fd8086-2942-4045-a91b-f16432eebe29">

This bar chart displays the top 20 words with the highest TF-IDF scores. Words like "love", "don", "know", and "ll" have high scores, suggesting they are significant in the lyrics relative to the corpus.

## Recommender System

### TF-IDF
TF-IDF stands for Term Frequency-Inverse Document Frequency. It is a numerical statistic intended to reflect how important a word is to a document in a collection or corpus. The TF-IDF value increases proportionally to the number of times a word appears in the document but is offset by the frequency of the word in the corpus.

### Cosine Similarity
Cosine similarity is a measure of similarity between two non-zero vectors. It calculates the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is particularly used in high-dimensional positive spaces, where the cosine similarity is a measurement of orientation and not magnitude.

### Types of Recommender Systems
1. **Content-Based Filtering:** Recommends items based on the features of the items and the user's past preferences.
2. **Collaborative Filtering:** Recommends items based on the preferences of similar users.
3. **Hybrid Systems:** Combine content-based and collaborative filtering methods.

In this project, a content-based filtering approach is used, leveraging TF-IDF and cosine similarity to recommend songs based on their lyrical content.

## Results and Analysis
The analysis of the TF-IDF scores and the cosine similarity matrix reveals that certain words and phrases are more significant in the context of song lyrics. The recommender system successfully identifies and suggests songs with similar lyrical themes.

## Conclusion
The Lyrics Recommender System demonstrates the effectiveness of using NLP techniques like TF-IDF and cosine similarity for content-based recommendations. The exploratory data analysis provides insights into the common themes and significant words in song lyrics.


