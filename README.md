# Mini GPT Implementation

## Overview
`minigpt.py` is a Python implementation of a simplified GPT (Generative Pre-trained Transformer) model. It's designed to demonstrate the core functionalities of GPT in a more accessible and less resource-intensive manner. The script uses PyTorch for model construction and training.

## Features
- **Mini GPT Model**: A lightweight version of the GPT model.
- **PyTorch Framework**: Built using PyTorch, a popular deep learning library.
- **Customizable Hyperparameters**: Includes settings for batch size, block size, number of layers, etc.
- **Training and Evaluation**: Script includes provisions for both training and evaluating the model.

## Requirements
- Python 3.x
- PyTorch
- (Any other dependencies if required)

## Usage
To use this script, ensure you have Python and PyTorch installed. Configure the hyperparameters as needed for your specific application. The script can be run directly in a Python environment. It's pre-configured for a sample NLP task, which can be modified according to your dataset and requirements.

## Hyperparameters
Batch Size: 16
Block Size: 32
Max Iterations: 5000
Evaluation Interval: 100
Learning Rate: 1e-3
Device: "cuda" if available, else "cpu"
Evaluation Iterations: 200
Embedding Dimension: 64
Number of Heads: 4
Number of Layers: 4
Dropout: 0.0
