# deep-learning-challenge

## Overview

This project aims to develop a deep learning binary classification model to predict whether an organization funded by Alphabet Soup will be successful or not. The model is trained on historical data with various features related to organizational characteristics and funding amounts.

## Data

- **Target Variable:** 
  - `IS_SUCCESSFUL`: Indicates whether an organization was successful (1) or not (0).
  
- **Feature Variables:**
  - The dataset includes features like `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `INCOME_AMT`, `ASK_AMT`, and other variables relevant to the organization.
  
- **Removed Columns:** 
  - `EIN` and `NAME` were dropped as they are non-beneficial for the model's predictions and serve only as identifiers.

  ## Model Architecture

The model was built using the TensorFlow and Keras libraries. It includes:
- **Input Layer**: Based on the number of input features.
- **Hidden Layers**:
  - First hidden layer: 128 neurons, ReLU activation.
  - Second hidden layer: 64 neurons, ReLU activation.
  - Third hidden layer: 32 neurons, ReLU activation.
- **Output Layer**: 1 neuron with sigmoid activation for binary classification (output 0 or 1).

### Model Training and Performance
- The model was trained for **100 epochs** with a batch size of **32**.
- **Accuracy on Training Data**: Reached **72%** in the early epochs.
- **Accuracy on Test Data**: Could be further analyzed by introducing regularization and tuning hyperparameters.

## Implementated Optimization
- **Removed Columns:** 
  - `EIN` was dropped as they are non-beneficial for the model's predictions and serve only as identifiers.
- **Used NAME to create bins**

### Model Architecture

The model was built using the TensorFlow and Keras libraries. It includes:
- **Input Layer**: Based on the number of input features.
- **Hidden Layers**:
  - First hidden layer: 15 neurons, ReLU activation.
  - Second hidden layer: 10 neurons, ReLU activation.
  - Third hidden layer: 5 neurons, ReLU activation.
- **Output Layer**: 1 neuron with sigmoid activation for binary classification (output 0 or 1).

### Model Training and Performance
- The model was trained for **45 epochs** with a batch size of **32**.
- **Accuracy on Training Data**: Reached **75%** in the early epochs.
