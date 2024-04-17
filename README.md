# Cats-Dogs Classification using Neural Network

This repository contains a Python implementation of a deep neural network using NumPy. The network architecture can be customized, and it includes support for both sigmoid and ReLU activation functions.
Features:
- Modular implementation with helper functions for forward and backward propagation.
- Support for loading datasets stored in HDF5 format.
- Customizable network architecture and learning parameters.
- Visualization of the learning process with cost over iterations.

## Dependencies:

- Python 3.x
- NumPy
- matplotlib
- h5py

## Code Summary:

The codebase consists of the following components:
- helpers.py: This file contains various helper functions essential for building and training the deep neural network. These functions include:
  - Activation functions (sigmoid and relu) and their corresponding backward functions (sigmoid_backward and relu_backward).
  - Functions for initializing parameters (initialize_parameters), performing forward propagation (linear_forward and linear_activation_forward), and computing costs (compute_cost).
  -  Functions for backward propagation (linear_backward and linear_activation_backward) and updating parameters (update_parameters).

Additionally, it includes a function for loading datasets stored in HDF5 format (load_dataset).

- train.py: This script serves as the main entry point for training the deep neural network. It imports helper functions from helpers.py to initialize parameters, perform forward and backward propagation, update parameters, and visualize the learning process.

- dataset.hdf5: This HDF5 file contains the dataset used for training and testing the neural network. It includes images along with their corresponding labels.
 
## Customization:
   Adjust the network architecture and hyperparameters in train.py.
   Modify activation functions or add new ones in the helpers.py file.
   Explore different datasets by loading them in helpers.py.

## Credits:

This implementation is inspired by various online resources and tutorials on deep learning and neural networks. See the comments in the code for specific credits.
