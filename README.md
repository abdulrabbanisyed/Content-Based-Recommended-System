# Content-Based-Recommended-System

This is a content-based recommendation system that uses natural language processing and machine learning techniques to recommend movies to users based on their viewing history. 

<img width="1009" alt="image" src="https://github.com/user-attachments/assets/9dd2430d-27e1-4f44-9313-01f03fcfd4f5">

## Features:

- **Text preprocessing:** converting text data into a numerical representation using CountVectorizer.
- **Keyword extraction:** extracting keywords from movie plots using Rake from nltk toolkit.
- **Cosine similarity:** calculating the similarity between movie vectors using cosine similarity.

## Tools:

- **Natural language processing:** using CountVectorizer and Rake to process text data.
- **Machine learning:** using cosine similarity to calculate the similarity between movie vectors.
- **Data preprocessing:** cleaning and preprocessing the data for analysis.
- **Programming:** using Python to implement the recommendation system.

## Text preprocessing code snippet using CountVectorizer

<img width="1064" alt="image" src="https://github.com/user-attachments/assets/9c7fe5c2-f50f-4811-9960-984c488b0ac6">

## Keyword extraction by RAKE(Rapid Action Keyword Extraction) algorithm extracts keywords by splitting text into words, removing stopwords, and calculating the co-occurrence of words.

<img width="1036" alt="image" src="https://github.com/user-attachments/assets/230a9d4c-5c0b-4cc5-b743-ddb6232c32fd">

## Cosine similarity on the vector matrix of the Data
<img width="1020" alt="image" src="https://github.com/user-attachments/assets/5c011e13-2379-4dd8-9757-77cd98ff0465">

## Results:
The output of the project is a list of recommended movies for a given Input similar to the previous movie. The recommended movies are based on the user's viewing history and are ranked by their similarity scores which have the most similarity score that is near to 1.

<img width="1042" alt="image" src="https://github.com/user-attachments/assets/0916e27a-84c4-4e12-a18f-e78c0d760ab4">

