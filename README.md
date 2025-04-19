# Simple RNN for IMDB Sentiment Analysis

This project implements a Recurrent Neural Network (RNN) using Keras to perform binary sentiment classification on the IMDB movie reviews dataset. It includes scripts and Jupyter notebooks for training, evaluating, and making predictions with the model, along with visualizing word embeddings.

## Features

- Preprocessing and vectorization of IMDB reviews
- Simple RNN model architecture built using Keras
- Training and evaluation workflows
- Visualization of word embeddings
- Pre-trained model for quick inference

## Project Structure

- `main.py`: Main script for training the RNN model.
- `simplernn.ipynb`: Notebook for building and training the model.
- `embedding.ipynb`: Visualizes learned word embeddings.
- `prediction.ipynb`: Demonstrates predictions on custom input text.
- `simple_rnn_imdb.h5`: Pre-trained model weights.
- `requirements.txt`: List of Python packages required to run the project.

## Getting Started

1. **Install Dependencies**

   Use the following command to install required packages:

   pip install -r requirements.txt

2. **Train the Model**

   You can run the training script via:

   python main.py

3. **Make Predictions**

   Use the prediction.ipynb notebook to perform sentiment analysis on custom text inputs. This notebook loads the pre-trained model and 
   demonstrates how to process and classify new data.

4. **Visualize Embeddings**

   The embedding.ipynb notebook provides an interactive visualization of the learned word embeddings, enabling a better understanding of 
   how the model interprets semantic similarity between words.

## Requirements
- Python 3.7+

- TensorFlow / Keras

- NumPy

- Matplotlib

- Jupyter Notebook   
