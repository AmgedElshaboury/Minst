# MNIST Handwritten Digit Classification

This project is a simple neural network implementation to classify handwritten digits from the MNIST dataset using Keras. The neural network is a fully connected, multi-layer perceptron (MLP) model, which performs image classification with high accuracy.

# Table of Contents
1. Dataset

2. Requirements

3. Code Structure

4. Results

5. How to Run
   
# Dataset
We use the MNIST dataset, which contains 70,000 grayscale images of handwritten digits (0-9) with each image of size 
28×28 pixels:

- 60,000 images for training

- 10,000 images for testing
  # Requirements
  - Keras
  
  - TensorFlow
  
  - NumPy
  
  - Matplotlib
 
   # Code Structure
     1. Loading the Data: Loads MNIST dataset and explores a random subset of images.
     2. Data Preprocessing: Reshapes and normalizes the images to be used in the neural network.
     3. Building the Model: Sets up a fully connected neural network with three hidden layers.
     4. Compiling the Model: Configures the model with the Adam optimizer, sparse categorical cross-entropy loss, and accuracy metric.
     5. Training the Model: Trains the model over 5 epochs with a batch size of 360.
     6. Evaluating the Model: Evaluates model performance on the test set and prints the final loss and accuracy.

     # Results
After training for 5 epochs, the model achieves the following results on the test set:

- Loss: 0.0827
- Accuracy: 97.57%
  # How to run
1. Clone or download this repository.
2. Install the required libraries.
3. Run the script in a Python environment
   ```python mnist_classification.py```

 
   
  
  


