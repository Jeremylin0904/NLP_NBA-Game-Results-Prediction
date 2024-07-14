# NLP Project: Predicting Game Results using Twitter Data and Game Statistics

![Results](results.jpg)

This repository contains the code and resources for a Natural Language Processing (NLP) final project aimed at predicting game results using tweets from various sources and game statistics from [Basketball-Reference.com](https://www.basketball-reference.com/). The project utilizes a combination of text scraping, word embedding, and deep learning techniques.

## Project Overview

The goal of this project is to predict game results (e.g., win or loss) of the Los Angeles Lakers basketball team using data extracted from Twitter accounts such as [Lakersnation](https://twitter.com/lakersnation), [LakersReporter](https://twitter.com/LakersReporter), and [wojespn](https://twitter.com/wojespn), along with game statistics sourced from [Basketball-Reference.com](https://www.basketball-reference.com/). The prediction model is built upon a deep learning architecture that takes into account both textual information extracted from tweets and numerical game statistics.

## Project Structure

- [`twitter.ipynb`](twitter.ipynb): This Jupyter notebook contains the code for scraping tweets using the [`snscrape.modules.twitter`](https://github.com/JustAnotherArchivist/snscrape) library, extracting relevant information from tweets, and preprocessing the text data.
- [`NLP_Final.ipynb`](NLP_Final.ipynb): This Jupyter notebook contains the code for building and training the deep learning model. It includes loading word embeddings, processing game statistics data, concatenating latent representations of text and numerical inputs, defining and training the model, and evaluating its performance.
- [`GoogleNews-vectors-negative300.bin.gz`](https://code.google.com/archive/p/word2vec/): This file contains pre-trained word embeddings used in the project.

## Results

The trained model achieves an accuracy of up to 77.25% in predicting game results based on a combination of tweets and game statistics. The predictions for a given set of statistics and tweets are also demonstrated within the [`NLP_Final.ipynb`](NLP_Final.ipynb) notebook.


