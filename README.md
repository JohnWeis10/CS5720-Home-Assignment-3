# CS5720 Home Assignment 3

Chapter 7 assignment

University of Central MissouriDepartment of Computer Science & Cybersecurity
Course: CS5720 – Neural Networks and Deep Learning
Semester: Summer 2025
Instructor: I Hua, Tsai

Student Name: John Weis
Student Number: 700708245

Assignment Overview

This repository contains the implementation for Home Assignment 3 of CS5720. The assignment explores deeper applications of Recurrent Neural Networks (RNNs), text sentiment analysis, and optimizer performance comparisons using TensorFlow. The tasks emphasize sequential modeling, text generation, and evaluating optimization strategies in deep learning.

## Tasks and Descriptions

1. Implementing an RNN for Text Generation

- Load a character-based text dataset (e.g., Shakespeare or The Little Prince).

- Convert text into sequences using embeddings or one-hot encoding.

- Build an LSTM-based RNN to predict the next character in a sequence.

- Train the model and generate text using temperature-scaled sampling.

- Discuss the role of temperature in controlling randomness during generation.

2. Sentiment Classification Using RNN

- Load the IMDB sentiment dataset.

- Preprocess text using tokenization and padding.

- Train an LSTM-based classifier to predict positive or negative sentiment.

- Evaluate the model using confusion matrix and classification metrics.

- Explain the precision-recall tradeoff in this context.

3. Comparing Optimizers – Adam vs. RMSprop vs. SGD

- Implement a feedforward neural network to classify MNIST digits.

- Train the model using three different optimizers: Adam, RMSprop, and SGD.

- Track training loss and accuracy across epochs.

- Plot training loss curves for comparison.

- Analyze convergence speed and final accuracy of each optimizer.


## How to Run
# Create and activate virtual environment (optional)
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt