![nexus_software_pvt_ltd_cover](https://github.com/Shreyaprasad21/Project-3-AI-ML-Series-Multiple-Disease-Detection-system/assets/142075353/1e542e0d-2db0-41cb-99b7-d8f61c9da7cb)

# PROJECT 1 - BUSINESS PURPOSE CHATBOT
This project has been done as a part of my internship program at Nexus Info. This is the first project of my internship, where I utilized Natural Language Processing (NLP) techniques to create a robust chatbot for answering general queries. The internship was conducted remotely, allowing me to collaborate with professionals and enhance my skills in a virtual environment.      

## Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Dependencies](#dependencies)            
4. [Usage](#usage)           
5. [File Structure](#file-structure)                             
6. [Deployment](#deployment)
7. [Notes](#notes)          
            
## Introduction
This project, developed during my internship at Nexus Info, creates a chatbot using NLP techniques for user interaction and sentiment analysis. It utilizes TF-IDF word embedding and word cloud visualization for enhanced engagement.

## Features
- **Data Handling:** Loads and analyzes a dataset containing pre-stored questions and responses.
- **Data Cleaning:** Applies text normalization techniques to clean and preprocess the dataset.
- **Sentiment Analysis:** Uses the VADER sentiment analyzer to evaluate the sentiment of user queries.
- **Word Cloud Visualization:** Generates word clouds to visualize frequent words in user queries and responses.
- **TF-IDF Word Embedding:** Implements TF-IDF vectorization for word embedding.
- **Chatbot Functionality:** Provides a chatbot interface that matches user queries with stored questions and returns informative responses.
- **Chat History:** Maintains a chat history and displays relevant information.

## Dependencies
- pandas
- nltk
- matplotlib
- wordcloud
- scikit-learn

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/Shreyaprasad21/Business_Purpose_Chatbot.git

2. Run the Script: Execute the script chatbot_script.py in a Python environment:
   ```sh
   Chatbot_project1.ipynb

3. Chat with the Bot: Enter queries to interact with the chatbot. Type 'exit' to end the conversation.
  
## File Structure
- `Chatbot_project1.ipynb`: Main script implementing the chatbot functionality.
- `dialogs_new.txt`: Dataset containing pre-stored questions and responses.
- `nlp_utils.py`: Utility functions for text normalization.

## Deployment

1. Start the chatbot by running:
  ```
  Chatbot_project1.ipynb
  ```

2. Interact with the chatbot in the console. Type 'exit' to end the conversation.

## Notes
- The project was developed using Python, with the main chatbot functionality implemented in `Chatbot_project1.ipynb`.
- `nlp_utils.py` contains helper functions for text normalization.
- The dataset (`dialogs_new.txt`) is provided and contains sample questions and responses.
- Sentiment analysis and word cloud visualization are integrated into the chatbot.
- TF-IDF vectorization is used to match user queries with stored questions.
- The project can be extended to cover more queries and provide more detailed responses.
