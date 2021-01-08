# Multi-Class Perceptron for Iris Dataset

The project is a Jupiter Notebook project that focuses on creating a perceptron for classifying a dataset with multiple classifier labels.

The dataset being used is the [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris), which contains 3 classes and 150 total data sets, with 50
belonging to each class. For each example x in the dataset X, there are 4 features.

The aim of this project is to: 
1. Create a Data Visualisation using Principal Component Analysis to determine linear separability of the 3 classes by finding a basis matrix Z from the dataset X
which describes the top principal components of the data, with the first row being the top.
2. Create a multi-class perceptron that classify the data in one of three label.
3. Create a Kernel-based Latent Factor Model of the data to increase their dimensions from 4 to a maximum of 150 (where 150 is the total no. of data sets), and utilise
the RBF Kernel formula. This will create a new matrix that can be used in Grid Search in order to find the ideal hyper-parameters that give the best predictions when
using the multi-class perceptron on the new matrix.
