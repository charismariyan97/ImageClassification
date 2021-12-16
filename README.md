# ImageClassification
## Rock-Paper-Scissors Image Classification Using Convolutional Neural Network (CNN)
Author: Charisma Riyan Etta | E-mail: charismariyan@gmail.com

> This project is about training the dataset of rock paper scissors images, to predict if an uploaded image is either a rock, a paper, or a scissor.

**Convolutional Neural Network (CNN)** is a deep learning algorithm that was designed for computer vision, such as image and videos. CNNs are most commonly used to analyze visual imagery and are frequently working behind the scenes in image classification.

### **How CNN works:**
![image](https://user-images.githubusercontent.com/96250221/146399281-36c1f90d-408c-455f-b737-1376520a4069.png)
*Picture from: https://iglab.tech/wp-content/uploads/2020/09/A-Convolutional-Neural-Network-1024x235.png

To build a model to classify pictures, we create a two-dimensional (2D) CNN architecture. 2D CNN is formed by an input layer, convolutional layer, max-pooling layer, a layer to flatten the 2D array, and output layer.

The Convolutional layer is used to extract the attributes of the picture, while the Max-Pooling is to reduce the size of each picture from the convolutional process (to fasten the training process).
The use of ReLU (Rectified Linear Unit) activation function in the convolutional layer is to increase the non-linearity of the model, since the images are non-linear.

Max-Pooling works by choosing a pixel with maximum value and results in a new image of the same size as the max-pooling layer.

After the images are being processed to the last Max-pooling Layer, the array of pictures will be flattened to a one-dimensional (1D) array.

Dense layer / fully connected layer, is used in the final stage of the neural network, it helps changing the dimensionality and receives output of every neuron from the preceding layer.

## Table of Contents
- Load Data (https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip)
- Check Directory
- Data Pre-Processing
- CNN Architecture (Build CNN Model, the use of Callback Function)
- Training the Model (Checking the loss, accuracy, train and validation)
- Upload and Predict Images

##
#DataScienceProject #DataScience #Bootcamp #achineLearning #DeepLearning #NeuralNetwork #ImageClassification #RockPaperScissors #DataAnalyst #DataPreparation #DataPreProcessing #EDA #CallbacksFunction #Modeling #ImagePrediction #ImageRecognition #CNN #Convolutional #Pooling #ReLU #Algorithm 
