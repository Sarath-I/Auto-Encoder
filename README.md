# Autoencoder Implementation using MNIST

This project demonstrates the implementation of a deep learning Autoencoder for image reconstruction using the MNIST handwritten digits dataset. The goal of the model is to learn a compressed representation of input images and reconstruct them with minimal information loss.

The architecture consists of two main components:

Encoder: Compresses the input 28×28 grayscale images into a lower-dimensional latent representation.

Decoder: Reconstructs the original image from the compressed latent space.

The model is trained on the MNIST training dataset and evaluated using the test dataset to measure how well it reconstructs unseen handwritten digits. 

DL Assignment 3 - Auto Encoders

Key Features

Implementation of an Encoder–Decoder Autoencoder architecture

Training the model on the MNIST dataset

Visualization of training and validation loss curves

Comparison of original vs reconstructed images

Clear model summary and well-structured code

Project Workflow

Data Loading and Preprocessing

MNIST dataset is loaded and normalized for training.

Model Architecture

Encoder compresses input images into a latent feature space.

Decoder reconstructs images from encoded representations.

Model Training

The autoencoder is trained using the training dataset.

Performance is monitored through training and validation loss.

Evaluation and Visualization

Model summary is displayed.

Training vs validation loss curves are plotted.

Side-by-side visualization of original and reconstructed images is provided. 

DL Assignment 3 - Auto Encoders

Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib

Jupyter Notebook

Results

The trained autoencoder successfully learns compressed representations of handwritten digits and reconstructs images that closely resemble the original inputs, demonstrating the effectiveness of unsupervised representation learning.
