# Tensorflow-Projects

#A storytale to Master the skills:

#Process 1 : 

#CLOTH and Handwritten Digits RECOGNITION

Classify the Clothes and Handwritten Digits with the help of Mnist Dataset with an API CALL FROM KERAS and measure its accuracy with the help of train and test datasets.

#Process 2:

#Improvise the MNIST DATASET with CONVOLUTION and MAX POOLING

Convoloution--The images are reshaped and the filters are applied on top of it
Max Pooling--The maximum pixel in the specified shape is taken out and the image is enhanced and compressed

#Process 3:
#Human or Horse Classifier

*The dataset is downloaded and extracted
*Tensorflow Sequential model is defined with 5 Convolution and Max Pooling layers
*Sigmoid Activation layer is used to improve accuracy for Binary classification with one output neuron and 512 hidden neurons for training purpose
*RMSprop optimizer  with a learning rate of 0.001 is defined with a binary cross entropy loss function
*Image Data Generator is imported from keras preprocessing image module and the images are rescaled and trained with 15 epochs
*Numpy is used to convert the image into a vertical stack array and the test image set is validated 
*Meanwhile, by adding image augmentation, overfitting can be avoided

#Transfer Learning Model
*Pre trained model is downloaded, the last layer is taken in the existing model and is trained with concolutions on the local machine 
*The new model is trained and the existing model is added additionally for greater accuracy

#Natural Language Processing

Project description:
Find out the accurate neural network to classify Saracasm

Neural Nets used :
Simple RNN,
LSTM,
Convolution,
GRU

Process:
*Firstly, check the TF version , if its based on version one, then add eager execution
*Classify, the training and testing sentences and labels
*Word indexing and sequence padding is done using tokenizer by setting up the parameters
*The sequences are converted to an array with numpy and the sequential model is developed with embedding and appropriate neural nets are tested and compiled with binary classification

Results:
Model | Epochs | Training Accuracy | Validation
Simple RNN | 30 | 99.34% | 81.64%
LSTM | 30 | 99.96% | 81.83%
Convolution | 30 | 99.94% | 82.17%
GRU | 30 | 99.95% | 83.23%
