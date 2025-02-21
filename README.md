# NAS
Neural Architecture Search (NAS) on MNIST Dataset

This code implements Neural Architecture Search (NAS) using Evolutionary Algorithms and Random Search to optimize deep learning models for MNIST digit classification.

FeaturesDataset: Uses the MNIST dataset (handwritten digits 0-9).

Search Methods:
Evolutionary Algorithm: Uses selection, crossover, and mutation to evolve model architectures.
Random Search: Randomly samples hyperparameters and selects the best model.

Model Architectures:
Fully Connected (Dense) Networks
Convolutional Neural Networks (CNNs)
Long Short-Term Memory (LSTM) Networks
Hyperparameter Optimization:
Number of layers
Layer sizes (32, 64, 128 units)
Activation functions (ReLU, Tanh)
Optimizers (Adam, SGD)
Batch size and epochs
How It WorksEvolutionary NASGenerates an initial population of random models.
Evaluates each model based on validation accuracy.
Selects the best models and creates a new generation using crossover and mutation.
Random Search NASRandomly samples hyperparameters from a predefined search space.
Trains and evaluates each model.
Selects the best-performing model.
Getting StartedPrerequisitesEnsure you have the following dependencies installed:
pip install tensorflow numpy scikit-learn kerasClone the Repositorygit clone https://github.com/your_username/NAS_Project.git
cd NAS_ProjectRun the NAS Evolutionary Algorithmpython evolutionary_nas.pyRun the Random Search NASpython random_search_nas.pyResultsThe best architecture found during the search is displayed at the end, along with its accuracy on the test set.
Neural Architecture Search automates deep learning model design, saving time and improving efficiency!

