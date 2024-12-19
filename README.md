# MNIST Classifier Neural Network
This project develops a neural network from scratch to calssify handwritten digits from the MNIST dataset.
The network is built using python, specifically the numpy library. It uses forward and backward propagation, activation functions, and gradient descent.

## Project Overview
This project was initially a part of a Kaggle competition, where I wanted to design and implement a neural network to classify images from the MNIST dataset
This dataset contains 60,000 training images, and 10,000 testing images of handwritten digits [0,9]. 

Network is trained through backpropagation, and is further optimized through Adap optimizer and Leaky ReLU and Softmax acitivation

## Key Features
- **Neural Network Architecture**: Built from scratch using Numpy, with Leaky ReLU activation and Softmax for output.
- **Optimization**: Utilizes the Adam optimizer and gradient descent to improve training efficiency.
- **Hyperparameter Tuning**: Experimented with different learning rates, number of layers, and neurons to achieve optimal performance.
- **Model Performance**: Achieved 93% accuracy on the MNIST test set.

## Technologies Used
- **Python**: Programming language used to implement the neural network.
- **Numpy**: Used for matrix operations and efficient computation in the neural network.
- **Linear Algebra**: Key mathematical concepts used for forward/backward propagation and optimization.
