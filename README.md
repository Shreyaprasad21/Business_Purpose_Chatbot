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
   git clone https://github.com/Shreyaprasad21/Project-3-AI-ML-Series-Multiple-Disease-Detection-system.git

2. Install dependencies:
   ```sh
   pip install -r requirements.txt

3. Run the desired disease prediction script:
- For Parkinson's Disease:
  ```
  parkinsons.ipynb
  ```
- For Diabetes:
  ```
  diabetes.ipynb
  ```
- For Heart Disease:
  ```
  heart.ipynb
  ```
  
4. Follow the prompts to input data for prediction.

## File Structure
- `parkinsons.ipynb`: Script for predicting Parkinson's Disease.
- `diabetes.ipynb`: Script for predicting Diabetes.
- `heart.ipynb`: Script for predicting Heart Disease.
- `Dataset/`: Directory containing the datasets for each disease.
- `parkinsons.csv`: Dataset for Parkinson's Disease.
- `diabetes.csv`: Dataset for Diabetes.
- `heart.csv`: Dataset for Heart Disease.
- `README.md`: Instructions and information about the project.

## Deployment
The project was deployed using Streamlit. To deploy the application locally:

1. Ensure Streamlit is installed:
  ```
  pip install streamlit
  ```

2. Run the Streamlit app:
  ```
  streamlit run app.py
  ```

3. Open your web browser and go to `http://localhost:8501`.

## Notes
- The project was developed using Jupyter Notebook, with separate notebooks (`parkinsons_detection.ipynb`, `diabetes_detection.ipynb`, `heart_disease_detection.ipynb`) for each disease.
- Each notebook contains the code for data preprocessing, model training, and evaluation specific to the respective disease.
- The datasets (`parkinsons.csv`, `diabetes.csv`, `heart_disease.csv`) are provided in the `Dataset/` directory.
- Model deployment, user interface, and interaction were implemented using Streamlit, providing an intuitive web interface for disease prediction.
























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

