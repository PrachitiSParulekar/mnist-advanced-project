# MNIST Advanced Project
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?logo=pytorch)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)

## Overview
This project implements and experiments with convolutional neural networks (CNNs) for handwritten digit recognition on the MNIST dataset using PyTorch.  
It includes baseline modeling, hyperparameter tuning, architecture improvements, regularization, and data augmentation.

## Structure
- `/notebooks/mnist_baseline.ipynb`: Main notebook with all essential steps, experiments, and results.
- `requirements.txt`: List of package dependencies.
- `LICENSE`: Project license (MIT).

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/PrachitiSParulekar/mnist-advanced-project.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook notebooks/mnist_baseline.ipynb
   ```

## Results
- Baseline test accuracy: ~98–99%
- Data augmentation, dropout, and deeper architectures implemented
- Visualizations of training loss and misclassifications
