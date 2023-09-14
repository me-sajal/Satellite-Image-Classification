# Satellite Image Classification

This repository contains code for a satellite image classification project using Convolutional Neural Networks (CNN) with TensorFlow and Keras. The project classifies satellite images into four categories: cloudy, desert, green_area, and water.

## Prerequisites

Before running the Jupyter Notebook (.ipynb) file, make sure you have the following:

1. Kaggle Account: To download the dataset, you need a Kaggle account. If you don't have one, you can sign up [here](https://www.kaggle.com/account/login).

2. Kaggle API Credentials: You will need your Kaggle username and API key to access the dataset. If you haven't generated an API key before, you can follow [these instructions]([https://www.kaggle.com/docs/api#authentication](https://www.kaggle.com/docs/api)) to create one.

3. Open the Jupyter Notebook file `satelliteimageclassification.ipynb` to begin working on the project.

## Project Overview

- **Dataset**: The dataset consists of satellite images categorized into four classes: cloudy, desert, green_area, and water. You can download the dataset from Kaggle using the Kaggle API credentials you set up earlier.

- **Model Architecture**: The project uses a Convolutional Neural Network (CNN) implemented with TensorFlow and Keras for image classification. The model architecture and summary are provided in the Jupyter Notebook.

- **Training and Validation**: The Jupyter Notebook includes code to train the model and monitor training and validation accuracy and loss. You can track the model's progress during training.

- **Evaluation**: After training, the model is evaluated on a separate test dataset, and the accuracy achieved is approximately 99.26%.

## Usage

1. Set up your Kaggle API credentials as mentioned in the prerequisites.

2. Open the Jupyter Notebook (`satelliteimageclassification.ipynb`) using Jupyter or a compatible environment.

3. Follow the notebook's instructions to load the dataset, preprocess the data, train the model, and evaluate its performance.

4. Customize the code and model parameters as needed for your specific use case.

## Acknowledgments

This project is for educational purposes and can be used as a starting point for satellite image classification tasks. The dataset used in this project is obtained from Kaggle, and credit goes to the original data providers.

Happy coding!
