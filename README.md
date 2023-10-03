# Wine Review Classification Project

## Project Overview

This project focuses on classifying wine reviews based on their quality, specifically whether they receive a rating of 90 points or higher. The goal is to build and train machine learning models that can automatically classify wine reviews as either "high-quality" or not.

## Dataset Information

The dataset used in this project is stored in the 'wine-reviews.csv' file. It contains wine descriptions, points, prices, and other relevant information. The labels for classification are derived from wine ratings, with reviews receiving 90 points or higher considered as "high-quality."

## Project Description

In this project, we follow several key steps to achieve our goal:

### Data Preprocessing

We begin by loading the dataset and removing unnecessary columns, focusing on essential features like descriptions and labels. The labels are determined based on wine ratings, where reviews with 90 points or more are labeled as "high-quality."

### Data Splitting

The dataset is split into training, validation, and test sets to facilitate model training and evaluation, ensuring a robust assessment of model performance.

### Text Vectorization

Two different approaches to text processing are explored:

1. **Pre-trained Word Embeddings**: We utilize pre-trained word embeddings from TensorFlow Hub (specifically, nnlm-en-dim50/2) to represent text data. This approach leverages pre-trained embeddings to enhance the model's understanding of the textual content.

2. **LSTM-based Neural Network**: We employ an LSTM (Long Short-Term Memory) based neural network for sequence processing. LSTM is well-suited for handling sequential data, making it effective for text classification tasks.

Text vectorization and tokenization are performed to prepare the textual data for modeling.


### Model Building, Training and Evaluation

Both models are trained and evaluated on the training and validation datasets. Training progress, including accuracy and loss, is monitored for each model.

## Acknowledgement

This project drew inspiration from a YouTube video from the Freecodecamp channel. The tutorial provided valuable guidance and insights into the machine learning techniques used in this project.

## Comments and Customization

Throughout the project, I've added comments and explanations to enhance understanding and serve as a learning exercise. Feel free to explore the Jupyter Notebook or scripts for detailed code implementation.

