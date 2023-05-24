## Project name: Solving Sudoku with Convolutional Neural Networks
### Author: Qichun Yu

## Table of Contents
1. [Introduction](#Abstract)  
    1.1. [Abstract](#Abstract)  
    1.2. [Use Case](#Use-Case)  
    1.3. [Load and Read Data](#Load-and-Read-Data)  
    1.4. [Data Cleaning](#Data-Cleaning)
2. [Preprocessing](#Preprocessing)  
    2.1. [Normalization](#Normalization)  
    2.2. [Data Splitting](#Data-Splitting)  
3. [Convolutional Neural Networks (CNNs)](#Convolutional-Neural-Networks-(CNNs))  
    3.1. [CNN Model 1](#CNN-Model-1)  
    3.2. [CNN Model 2](#CNN-Model-2)   
    3.3. [CNN Model 3](#CNN-Model-3)  
    3.4. [CNN Model 4](#CNN-Model-4)  
    3.5. [CNN Model 5](#CNN-Model-5)  
    3.6. [CNN Model 6](#CNN-Model-6)  
    3.7. [CNN Model 7](#CNN-Model-7)  
    3.8. [CNN Model 8](#CNN-Model-8)  
    3.9. [CNN Model 9](#CNN-Model-9)  
    3.10. [CNN Model 10](#CNN-Model-10)  
    3.11. [CNN Model 11](#CNN-Model-11)  
4. [Discussion](#Discussion)
5. [Conclusion](#Conclusion)

### Abstract

Sudoku is a number puzzle game that requires you to fill in digits 1 to 9. The game requires digits 1 to 9 to appear exactly once in each row, column and each of the nine 3x3 subgrids. The project experiment with different neural networks such as CNN. The data have been divided by 9 and subtracted by 0.5 to achieve zero mean-centred data. The CNN model that includes 9 convolution layers with 512 kernels works best with 95% of training accuracy. The study found that an increase in the number of epochs, number of layers, and number of neurons per layer can help improve the accuracy of the neural network model. Moreover, the dropout layer and maxpooling can help prevent overfitting. Adding strides of 3 x 3 is useful but requires large computing power. The main objective of this project is to build a deep learning model for a mobile app company that can analyze the grid of Sudoku to be filled, solve the Sudoku problem, and fill the grid. The convolution neural networks (CNN) is good at extracting features from the dataset and can be used to solve a sudoku game successfully. 

### Use Case
A mobile app company is building a classical Sudoku game. The development team is working on building a deep learning model which can analyze the grid of sudoku puzzles to be filled, solve the sudoku puzzles problem, and then automatic fill the grid in the end. The dataset includes 1 million Sudoku quizs with solution. This deep learning model will be part of a larger code as the backend of the Sudoku game application. 

### Citation

Kyubyong Park.(September, 2022). 1 million Sudoku games. Retrieved from https://www.kaggle.com/datasets/bryanpark/sudoku.

### Environment
Operating system: Windows Server 2019 atacenter, 64-bit<br>
GPU: Tesla V100-PCIE-16GB
