## Spam Detection using RNN, LSTM & GRU:

This project focuses on Spam Message Detection using Deep Learning.
The same text classification problem is solved using three different recurrent neural network architectures:

Simple RNN

LSTM (Long Short-Term Memory)

GRU (Gated Recurrent Unit)

The purpose of this project is to understand how different recurrent neural network architectures perform on a text classification task.

Project Overview:

Spam detection is a binary text classification problem where messages are classified into two categories:

Spam – Unwanted, promotional, or suspicious messages
Ham – Normal or legitimate messages

In this project, the same dataset and preprocessing approach are used to train three different deep learning models. This makes it easier to understand and compare the behavior of Simple RNN, LSTM, and GRU.

# Models Used:
1. Simple RNN

A Simple Recurrent Neural Network processes text sequentially and learns patterns from previous words/tokens.

Input Text
    ↓
Text Preprocessing
    ↓
Tokenization & Padding
    ↓
Embedding
    ↓
Simple RNN
    ↓
Dense (Sigmoid)
    ↓
Spam / Ham
2. LSTM

Long Short-Term Memory (LSTM) is an advanced form of RNN designed to handle long-term dependencies more effectively using memory cells and gates.

Input Text
    ↓
Text Preprocessing
    ↓
Tokenization & Padding
    ↓
Embedding
    ↓
LSTM
    ↓
Dense (Sigmoid)
    ↓
Spam / Ham
3. GRU

Gated Recurrent Unit (GRU) is another recurrent architecture that uses gates to control the flow of information while having a simpler structure than LSTM.

Input Text
    ↓
Text Preprocessing
    ↓
Tokenization & Padding
    ↓
Embedding
    ↓
GRU
    ↓
Dense (Sigmoid)
    ↓
Spam / Ham

Common Workflow

All three models follow a similar machine learning workflow:

Dataset
   ↓
Data Cleaning
   ↓
Text Preprocessing
   ↓
Tokenization
   ↓
Sequence Conversion
   ↓
Padding
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Spam / Ham Prediction

The main difference between the three implementations is the recurrent layer used in the neural network.

# Technologies & Libraries:
Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

Scikit-learn

# Model Evaluation:

Each model is evaluated on unseen test data using metrics such as:

Accuracy
Loss
Confusion Matrix
Classification Report

The results can be compared to understand the performance differences between Simple RNN, LSTM, and GRU.

Model Comparison

Model	Architecture	Main Advantage

Simple RNN	Basic recurrent network	Simple and easy to understand

LSTM	Recurrent network with memory cells and gates	Handles long-term dependencies better

GRU	Gated recurrent network	Simpler and often faster than LSTM

The actual performance of each model depends on the dataset, preprocessing, hyperparameters, and training configuration.

Example Predictions
Spam:
"Congratulations! You have won a free prize. Claim now!"

Prediction: Spam

Ham:
"Hey, are we meeting tomorrow?"

Prediction: Not Spam / Ham

Key Learning Outcomes:

This project helps in understanding:

How NLP data is prepared for deep learning

Text tokenization and sequence conversion

Why padding is required

How an Embedding Layer represents text numerically

How Simple RNN processes sequential data

How LSTM handles long-term dependencies

How GRU uses gates to control information flow

Binary classification using Sigmoid activation

Model evaluation and comparison

RNN vs LSTM vs GRU:

Simple RNN:

Easy to understand and implement

Suitable for learning basic sequential patterns

Can struggle with long-term dependencies

LSTM:
Uses memory cells and multiple gates

Better at learning long-term dependencies

More complex than Simple RNN

GRU:
Uses fewer gates than LSTM

Simpler architecture

Can provide good performance with fewer parameters

Conclusion:

This project demonstrates how Simple RNN, LSTM, and GRU can be applied to the same spam detection problem.

Author:

Nidhi Sharma
