# Basic Perceptron Neural Network

This Jupyter Notebook, `ML_Test_2.ipynb`, is part of the Basic_Perceptron_NN repository. It demonstrates the implementation of a basic Perceptron Neural Network for binary classification tasks. The Perceptron is one of the simplest forms of artificial neural networks, comprising a single layer of interconnected neurons.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Dataset](#dataset)
- [Perceptron Algorithm](#perceptron-algorithm)
- [Training](#training)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)

## Introduction

The Perceptron is a fundamental building block in neural network models. It's a binary classifier that learns to classify inputs into two classes based on weights and thresholds. This notebook demonstrates how to build a simple Perceptron Neural Network using Python and the Numpy library.

## Prerequisites

To run this notebook, you'll need:

- Python 3.x
- Jupyter Notebook
- Numpy

You can install the required dependencies using:

```bash
pip install jupyter numpy

```

## Usage
1. Clone this repository

```bash
git clone https://github.com/mrdetective007/Basic_Perceptron_NN.git
```

2. Navigate to the Perceptron_Algorithm directory:

```bash
cd Basic_Perceptron_NN/Perceptron_Algorithm
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook ML_Test_2.ipynb
```

4. Follow the instructions in the notebook to understand and experiment with the Perceptron Neural Network.

## Dataset
The notebook uses a sample dataset for binary classification. The dataset is loaded and preprocessed to train and evaluate the Perceptron.

## Perceptron Algorithm
The Perceptron algorithm consists of the following steps:

1. Initialize weights and bias.
2. For each input, calculate the weighted sum of inputs.
3. Apply the activation function (usually a step function).
4. Adjust weights and biases based on prediction error.
5. Repeat steps 2-4 for multiple epochs.

## Training
The notebook demonstrates how the Perceptron is trained using the dataset. It showcases the iterative process of adjusting weights to minimize classification error.

## Evaluation
After training, the notebook evaluates Perceptron's performance on the dataset. It displays metrics such as accuracy, precision, recall, and F1-score.

## Conclusion
This notebook provides a hands-on introduction to the basic Perceptron Neural Network and its application in binary classification tasks. By following along, you can gain insights into how neural networks learn and make predictions.
