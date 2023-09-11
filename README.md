# MNIST-Starter-Neural-Network

# Neural Network Models: MNIST Letter and Color Prediction
This repository contains two neural network models: one for predicting handwritten letters from the MNIST dataset and another for predicting colors based on a color prediction dataset. In this README, we'll provide an overview of the neural network architectures and algorithms used in these models.

## Model Architectures
### MNIST Letter Prediction Neural Network
The MNIST letter prediction neural network is designed to recognize handwritten letters from the MNIST dataset. It consists of multiple dense layers with appropriate activation functions to capture complex patterns in the image data. The final output layer uses softmax activation to produce probabilities for each letter class.

### Color Prediction Neural Network
The color prediction neural network is designed to predict colors based on a color prediction dataset. It uses regression techniques to estimate color values. This model consists of multiple dense layers with varying activation functions to learn complex relationships in the input features. The output layer uses sigmoid activation for regression, producing the predicted color values.

### Training and Evaluation
Both models can be trained by providing the training data and specifying the number of epochs. During training, the models optimize their parameters to make accurate predictions. After training, you can evaluate the models' performance on both training and test datasets. The accuracy metric for the MNIST letter prediction model and mean squared error (MSE) for the color prediction model help assess their predictive capabilities.

### Usage
You can use these neural network models for various applications, such as image recognition for letters or color prediction for design projects. The models provide valuable tools for solving classification and regression problems in machine learning.

### Folders
There are 4 folders, each one contains a report summarizing the whole steps in the notebook on the same folder. 
