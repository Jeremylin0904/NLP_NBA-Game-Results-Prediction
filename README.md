# NLP Final Project: Predicting Game Results using Twitter Data and Game Statistics

This repository contains the code and resources for a Natural Language Processing (NLP) final project aimed at predicting game results using tweets from various sources and game statistics from Basketball-Reference.com. The project utilizes a combination of text scraping, word embedding, and deep learning techniques.

## Project Overview

The goal of this project is to predict game results (e.g., win or loss) of the Los Angeles Lakers basketball team using data extracted from Twitter accounts such as Lakersnation, LakersReporter, and wojespn, along with game statistics sourced from Basketball-Reference.com. The prediction model is built upon a deep learning architecture that takes into account both textual information extracted from tweets and numerical game statistics.

## Project Structure

- `twitter.ipynb`: This Jupyter notebook contains the code for scraping tweets using the `snscrape.modules.twitter` library, extracting relevant information from tweets, and preprocessing the text data.
- `NLP_Final.ipynb`: This Jupyter notebook contains the code for building and training the deep learning model. It includes loading word embeddings, processing game statistics data, concatenating latent representations of text and numerical inputs, defining and training the model, and evaluating its performance.
- `GoogleNews-vectors-negative300.bin.gz`: This file contains pre-trained word embeddings used in the project.
- `README.md`: This file, providing an overview of the project, instructions, and usage guidelines.

## Instructions

To replicate the project or use the provided code:

1. Clone this repository to your local machine.
2. Ensure you have the necessary libraries and dependencies installed (e.g., Python, Jupyter Notebook).
3. Download the pre-trained word embeddings file `GoogleNews-vectors-negative300.bin.gz` and place it in the project directory.
4. Run the `twitter.ipynb` notebook to scrape tweets, preprocess the text data, and extract relevant information.
5. Run the `NLP_Final.ipynb` notebook to build, train, and evaluate the deep learning model for predicting game results.
6. Analyze the results and performance metrics provided in the notebook.

## Results

The trained model achieves an accuracy of up to 77.25% in predicting game results based on a combination of tweets and game statistics. The predictions for a given set of statistics and tweets are also demonstrated within the `NLP_Final.ipynb` notebook.

