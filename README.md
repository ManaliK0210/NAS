# NAS
Neural Architecture Search (NAS) on MNIST Dataset

This code implements Neural Architecture Search (NAS) using Evolutionary Algorithms and Random Search to find the optimal neural networks for MNIST digit classification.

Dataset: MNIST dataset (handwritten digits 0-9).

Search Methods:
Evolutionary Algorithm: Uses selection, crossover, and mutation to evolve model architectures.
Random Search: Randomly samples hyperparameters and selects the best model.

Model Architectures: Fully Connected (Dense) layers, Convolutional Neural Networks (CNNs) layers, Long Short-Term Memory (LSTM) layers

Hyperparameter Optimization: Number of layers, Layer sizes (32, 64, 128 units), Activation functions (ReLU, Tanh), Optimizers (Adam, SGD), Batch size and epochs

How It Works
Evolutionary NAS: Generates an initial population of random models.Evaluates each model based on validation accuracy. Selects the best models and creates a new generation using crossover and mutation.
Random Search NAS: Randomly samples hyperparameters from a predefined search space. Trains and evaluates each model. Selects the best-performing model.

Ensure you have the following dependencies installed:
tensorflow: 2.16.1, numpy: 1.26.4, scikit-learn: 1.1.2, keras: 3.1.1

The best architecture found during the search is displayed at the end, along with its accuracy on the test set.

Neural Architecture Search automates deep learning model design, saving time and improving efficiency!


