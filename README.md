# README

## About the project:
The Tic-Tac-Toe Endgame dataset from 1991 (stored here for easy access) contains 9 features that portray the current value in each square on a Tic-Tac-Toe Board, as well as a target value indicating if X won. It contains categorical data and 958 instances. Through the MLPClassifier from Scikit-learn, this project attempts to predict whether X won based on the layout of the board. It returns positive if X wins, and negative if O wins or they draw. It was chosen due to the non-linear relationships between the input features and target output. We compare the difference in accuracy and error based on 4 hyperparameters: The activation function, learning rate, maximum number of iterations, and number of hidden layers. We compare the accuracy of the Logistic, Tanh, and ReLu activation functions.


### Changes made to original starter code:
Second parameters of NeuralNet constructor changed to accept url instead of direct data file.


### Libraries used:
numpy
pandas
scikit-learn, MLPClassifier
matplotlib


### Building and Running
Runs best using the Google Collab Link at the top of the python file, but by installing the necessary packages and libraries mentioned above (like numpy and pandas) before compiling and running.
