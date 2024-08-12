# Plant Health Classification
## Objective
The objective of this project is to develop a machine learning model that can classify plant images into two categories based on their health status: Healthy and Unhealthy. This binary classification task is a practical application of concepts learned in the Artificial Neural Networks and Deep Learning course. The project provides an opportunity to implement, train, and evaluate a neural network model capable of accurately predicting the health status of plants from images.
## Project Overview
In this project, we worked with a dataset of plant images, where each image is labeled according to the plant's health condition. The goal is to build a classifier that can distinguish between healthy and unhealthy plants, leveraging deep learning techniques.
## Dataset Details
The dataset used for this project is organized as follows:
- Image Size: 96x96 pixels
- Color Space: RGB (3 channels)
- File Format: .npz
- Number of Classes: 2
- **Class 0: "healthy"**
- **Class 1: "unhealthy"**
## Dataset Structure
The dataset is provided as a single .npz file (public_data.npz) located in the training folder. The .npz file contains the following items:

data: A numpy array with shape 5200x96x96x3, containing 5,200 RGB images.
-labels: A 1-dimensional numpy array with shape 5200, containing labels with values in {'healthy', 'unhealthy'}.

labels: A 1-dimensional numpy array with shape 5200, containing labels with values in {'healthy', 'unhealthy'}.
## Task Overview
- Data Loading: Load the images and labels from the .npz file.
- Data Preprocessing: Normalize the images, possibly augment the data, and prepare it for model training.
- Model Training: Train a neural network model using the preprocessed data to classify the images.
- Model Evaluation: Evaluate the model's performance on a validation or test set to determine its accuracy and reliability.
