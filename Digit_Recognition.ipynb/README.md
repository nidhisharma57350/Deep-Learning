Digit Recognition using Sequential Model
Project Overview:

This project demonstrates handwritten digit recognition using a Deep Learning Sequential Model. The model is trained on the MNIST dataset to recognize handwritten digits from 0 to 9.

The project covers the complete workflow of a basic deep learning classification problem, including data preprocessing, model building, training, evaluation, and prediction.

Objective:

The main objective of this project is to build a neural network that can accurately classify handwritten digit images into one of the 10 classes (0–9).

Dataset:

The project uses the MNIST handwritten digits dataset.

Training images: 60,000
Testing images: 10,000
Image size: 28 × 28 pixels
Number of classes: 10
Classes: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9

Each image represents a handwritten digit.

Model Architecture:

A Sequential Neural Network is used for digit classification.

The model consists of:

Flatten Layer – Converts the 28×28 image into a 1D vector.
Dense Hidden Layer – Learns important patterns and features from the images.
Output Layer – Contains 10 neurons, one for each digit (0–9).
Softmax Activation – Produces the probability of each digit class.

Technologies Used:
Python
NumPy
Matplotlib
TensorFlow
Keras
Jupyter Notebook
Project Workflow:
Load the MNIST dataset
Explore the dataset
Visualize handwritten digit images
Normalize the pixel values
Build the Sequential Neural Network
Compile the model
Train the model
Evaluate the model on test data
Make predictions
Visualize predicted digits and results
Data Preprocessing:

The pixel values of the images are normalized before training.

Since MNIST pixel values range from 0 to 255, they are scaled to the range 0 to 1.

This helps the neural network train more efficiently.

Model Training:

The model is trained using the training dataset. During training, the model learns patterns from handwritten digits and improves its ability to classify unseen images.

Model Evaluation:

After training, the model is evaluated using the test dataset.

The project also includes visualization of predictions to check whether the model correctly recognizes handwritten digits.
Example:

Actual Digit:4
Predicted Digit:4
Prediction:

The trained model can predict the digit present in an unseen MNIST image.

The model returns probabilities for all 10 classes, and the class with the highest probability is selected as the predicted digit.

Visualizations:

The project includes visualizations such as:

Key Learnings:

Through this project, I learned:

How to work with the MNIST dataset
Image preprocessing for deep learning
How a Sequential model works
How Flatten and Dense layers are used
How to train a neural network
How to evaluate classification performance
How to visualize model predictions
Basics of handwritten digit classification
Conclusion:

This project successfully demonstrates how a Sequential Neural Network can be used for handwritten digit recognition. It provides a practical introduction to Deep Learning, Neural Networks, and Image Classification using TensorFlow and Keras.

Author:
Nidhi Sharma
