
# Sentiment Analysis Classifier for Amazon Customer Reviews

This project is aimed at performing sentiment analysis in Python using two different techniques, NLTK's SentimentIntensityAnalyzer (VADER) and the Roberta Pretrained Model, to analyze the sentiments of Amazon reviews.

# Steps to Run the Project
Environment Setup: It is recommended to set up a virtual environment and install the necessary libraries listed in the "Requirements" section.
Run the Python Script: After setting up the environment, run the provided Python script, which reads the data, performs exploratory data analysis (EDA), and conducts sentiment analysis.

# Requirements: 
Python 3.x
pandas
numpy
matplotlib
seaborn
nltk
tqdm
transformers
You can install the required libraries using pip
pip install pandas numpy matplotlib seaborn nltk tqdm transformers

# Project Structure
Data Reading: The script reads the review data from a CSV file. Adjust the file path as per your local setup.

Quick EDA: A quick Exploratory Data Analysis is performed to understand the data distribution.

VADER Sentiment Analysis: NLTK’s VADER (Valence Aware Dictionary and sEntiment Reasoner) SentimentIntensityAnalyzer is used for sentiment analysis. It provides the polarity scores for the given text data.

Roberta Pretrained Model: A model trained on a large corpus of data (Roberta Model) is also used for sentiment analysis, considering both words and their contextual relation.

Result Visualization: The results from both the VADER and Roberta model are visualized using various plots.

# Quick Start
Adjust the path to your CSV file in the pd.read_csv('path_to_your_file') line.
Run the Python script.

# Output
The script will output several plots visualizing the results of sentiment analysis and will print the sentiment scores calculated by both VADER and the Roberta Model for each review in the dataset.

# Notes
The project currently performs sentiment analysis on the first 500 reviews from the dataset for quick results. You can modify the script to analyze more reviews as needed.
Handle any memory issues carefully when using a larger dataset, especially with the Roberta Model, as it may require significant computational resources.
