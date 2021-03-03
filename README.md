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
Project one- To detect the given headline belongs to sarcastic or non sarcastic
*Firstly, check the TF version , if its based on version one, then add eager execution
*Classify, the training and testing sentences and labels
*Word indexing and sequence padding is done using tokenizer by setting up the parameters
*The sequences are converted to an array with numpy and the sequential model is developed with embedding, global average pooling with 24 dense intermediate neurons and compiled with binary classification
*The training and validation model is fitted against with an accuracy of 99.3% and a 81.3% validation accuracy
