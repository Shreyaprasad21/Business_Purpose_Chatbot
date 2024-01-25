# Project-1-AIML-Project-Series-
# Chatbot Implementation

## Overview
This Python script creates a chatbot that interacts with users, answers pre-defined questions, and stores chat history. It utilizes Natural Language Processing (NLP) techniques for sentiment analysis, TF-IDF word embedding, and visualizes word clouds.

## Features
- **Data Handling:** Loads and analyzes a dataset containing pre-stored questions and responses.
- **Data Cleaning:** Applies text normalization techniques to clean and preprocess the dataset.
- **Sentiment Analysis:** Uses the VADER sentiment analyzer to evaluate the sentiment of user queries.
- **Word Cloud Visualization:** Generates word clouds to visualize frequent words in user queries and responses.
- **TF-IDF Word Embedding:** Implements TF-IDF vectorization for word embedding.
- **Chatbot Functionality:** Provides a chatbot interface that matches user queries with stored questions and returns informative responses.
- **Chat History:** Maintains a chat history and displays relevant information.

## How to Use
1. **Installation:** Install required libraries using `pip install -r requirements.txt`.
2. **Run the Script:** Execute the script `chatbot_script.py` in a Python environment.
3. **Chat with the Bot:** Enter queries to interact with the chatbot. Type 'exit' to end the conversation.

## Dependencies
- pandas
- nltk
- matplotlib
- wordcloud
- scikit-learn

## Files
- `chatbot_script.py`: Main script implementing the chatbot functionality.
- `dialogs_new.txt`: Dataset containing pre-stored questions and responses.
- `nlp_utils.py`: Utility functions for text normalization.

## Author
[Shreya Prasad]

Feel free to enhance and customize the code based on your needs. Happy chatting!

