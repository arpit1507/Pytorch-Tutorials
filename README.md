# PyTorch Tutorials

A hands-on learning repository documenting my progress with PyTorch through practical Google Colab implementations.

The notebooks cover tensor operations, automatic differentiation, custom datasets and data loaders, neural networks built from scratch, model development with `torch.nn`, and hyperparameter optimisation with Optuna.

## Notebooks

### 1. [Tensor Basics](torch_basics.ipynb)

Introduction to PyTorch tensors, including:

- Tensor creation methods
- Data types and shapes
- Indexing and reshaping
- Mathematical and matrix operations

### 2. [Gradients and Autograd](Grad.ipynb)

An introduction to gradients and PyTorch's automatic-differentiation system:

- Gradient calculation
- Computational graphs
- Backpropagation
- `requires_grad`
- Disabling gradient tracking during evaluation

### 3. [Custom Datasets and Data Loaders](Batching.ipynb)

Implementation of a custom PyTorch dataset and data-loading pipeline:

- Creating a custom `Dataset`
- Using `DataLoader`
- Dividing data into batches
- Shuffling training data
- Iterating through batches efficiently

### 4. [Neural Network from Scratch](simple_Neural_Network.ipynb)

A simple neural network and linear-regression workflow implemented without using the high-level `torch.nn` model-building utilities.

This notebook focuses on understanding:

- Model parameters
- Forward propagation
- Loss calculation
- Gradient computation
- Parameter updates

### 5. [Artificial Neural Network with torch.nn](ANN.ipynb)

Implementation of a multilayer neural network using PyTorch's `torch.nn` module:

- Fully connected layers
- Activation functions
- Batch normalisation
- Dropout
- Training and validation loops
- GPU-compatible model training

### 6. [Hyperparameter Optimisation with PyTorch and Optuna](pytorch_implimentation.ipynb)

An automated model-training and hyperparameter-optimisation workflow using Optuna.

The notebook explores tuning:

- Number of hidden layers
- Number of nodes per layer
- Optimizer selection
- Learning rate
- Batch size

It also covers model validation and Optuna trial evaluation.

## Technologies

- Python
- PyTorch
- Optuna
- NumPy
- Google Colab
- Jupyter Notebook

## Next Steps

Planned additions include:

- Convolutional neural networks
- Image-classification projects
- Deeper neural-network architectures
- Transfer learning
- Model checkpointing and experiment tracking
- Implementations and reproductions of research papers

This repository is an active learning project and will continue to expand as I develop my practical deep-learning knowledge.
