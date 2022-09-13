# Experiment-No.-2

EX NO: 02

DATE: 09/09/2022

# Implementation of single neuron with Feed-Forward propagation in Python

**AIM:**

To implement a neuron with a feed-forward propagation in Python



**EQUIPMENTS REQUIRED:**
Hardware – PCs
Anaconda – Python 3.7 Installation / Google Colab /Jupiter Notebook



**RELATED THEORETICAL CONCEPT:**

A neural network is a system that learns how to make predictions by following these steps:
Taking the input data
Making a prediction
Comparing the prediction to the desired output
Adjusting its internal state to predict correctly the next time
Vectors, layers, and linear regression are some of the building blocks of neural networks. The data is stored as vectors, and with Python you store these vectors in arrays. Each layer transforms the data that comes from the previous layer. Each layer is a feature engineering step, because each layer extracts some representation of the data that came previously.
The first step in building a neural network is generating an output from input data. It can be done by creating a weighted sum of the variables. 
In this first example, consider an input vector and the other two weight vectors. The goal is to find which of the weights is more similar to the input, taking into account the direction and the magnitude. This is how the vectors look if you plot them:

weights_2 is more similar to the input vector since it’s pointing in the same direction and the magnitude is also similar. First, you define the three vectors, one for the input and the other two for the weights. Then you compute how similar input_vector and weights_1 are. To do that, you’ll apply the dot product. Since all the vectors are two-dimensional vectors, these are the steps to do it:
Multiply the first index of input_vector by the first index of weights_1.
Multiply the second index of input_vector by the second index of weights_2.
Sum the results of both multiplications.
Making Your First Prediction
First neural network can be built with only two layers with two operations used inside the neural network were the dot product and a sum. Both are linear operations.
The neuron  developed can use the sigmoid activation function. 




A single neuron feed-forward propagation output can be obtained as shown in the above figure.


**ALGORITHM:**
Importing the libraries
Importing the dataset
Taking care of missing data
Encoding categorical data
Normalizing the data
Choose the input parameters and output parameters
Splitting the data into test and train
Assign synaptic weights in random number
Find the dot product of input vector and weights
Apply sigmoid function for the dot product to find the output of each input set in the data set.



**PROGRAM:**


**Output**


**RESULT**
