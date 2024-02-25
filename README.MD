# Kore University of Enna Machine Learning Project Template

Welcome to the Kore University of Enna Machine Learning Project Template! This repository serves as a template for structuring and organizing your final project for the Machine Learning course at Kore University of Enna.

## Overview

This repository provides a standardized structure for your Machine Learning projects. It includes folders for dataset management, model implementation, utility functions, and scripts for training and inference.

## Repository Structure

- **dataset/**: This directory contains code associated with data handling, including data reading, dataset classes, and preprocessing.
  
- **model/**: Here, you'll find the code for implementing machine learning models. This includes model architectures, classes, and any related utilities.

- **utils/**: The utility functions directory holds commonly used functions and modules that can be imported across different parts of the project.

- **train.py**: This script contains the logic for training your machine learning models. It includes functions for training, validation, and model evaluation.

- **inference.py**: Here, you'll find the logic for running inference on trained models. This script includes functions for loading models, making predictions, and computing evaluation metrics.

- **requirements.txt**: This file lists all Python packages required to run the project. You can install them using `pip install -r requirements.txt`.

## Getting Started

To get started with using this template for your project, follow these steps:

1. Clone this repository to your local machine.
2. Organize your dataset-related code and classes and place it in the `dataset/` directory.
3. Implement your machine learning models in the `model/` directory.
4. Add any utility functions or modules to the `utils/` directory.
5. Use `train.py` to train your models and `inference.py` for testing and inference.
6. Install the required packages using `pip install -r requirements.txt`.

## Usage

- **Training**: Run `train.py` to train your models. You can specify hyperparameters and settings within the script.
  
- **Inference**: Use `inference.py` to perform inference on trained models. This script provides functions for loading models and making predictions on test data.

Both for training and inference, arguments (e.g., batch size, data folder, etc.) can be passed to the scripts. They can be managed either through **YAML configuration files or using argparse for command-line interaction**.

## Contributors

- [Moreno La Quatra](mlaquatra.me) - Kore University of Enna

## License

This project is licensed under the [MIT License](LICENSE).

