# Rock-Paper-Scissors Image Prediction Using TensorFlow Sequential Model

## Problem Statement:

Rock-Paper-Scissors is a classic game where each choice—rock, paper, or scissors—has an equal chance of winning, losing, or drawing against the other. With advancements in image recognition technology, the challenge arises to develop a model capable of accurately identifying and predicting the outcome based on an image uploaded by a user. This project is relevant in the field of computer vision, where the ability to identify objects in images is crucial for a wide range of applications.

## Project Scope:

The goal of this project is to build a predictive model using TensorFlow's Sequential API to recognize images representing the game choices of Rock, Paper, and Scissors. The model will be trained on a dataset of labeled images and then applied to predict the class of new images uploaded by users.

This project encompasses the following key steps:

1. Data Collection and Preprocessing: Gather a dataset of images that includes categories for rock, paper, and scissors. Preprocess the images by normalizing and augmenting them to enhance the diversity and robustness of the training data.

2. Model Development: Construct the predictive model using TensorFlow's Sequential API. The model will include several convolutional layers for feature extraction, followed by dense layers for final classification.

3. Training and Validation: Train the model using the processed dataset and validate it with a separate set of data to assess the model’s performance.

4. Prediction: Deploy the model to predict the category of new images uploaded by users, determining whether the image represents rock, paper, or scissors.

5. Evaluation and Refinement: Evaluate the model’s accuracy and fine-tune the parameters as needed to improve prediction performance.

## Result Model Sequential
- Accuracy: 92%
- Val Accuracy: 93% 

## Conclusion:

This project successfully demonstrates how TensorFlow can be utilized to develop a predictive model capable of recognizing and predicting images from the Rock-Paper-Scissors game. The approach taken here can be extended to various other image recognition tasks, including game development, interactive applications, or other object recognition systems. The success of this project underscores the importance of high-quality datasets and well-optimized models in achieving high prediction accuracy.