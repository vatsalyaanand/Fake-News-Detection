# Fake News Detection Using Deep Learning Models

This repository contains the code and resources for our comprehensive study on the effective detection of fake news using the LIAR dataset. Our study investigates three robust deep learning models: Convolutional Neural Network (CNN), Long Short-Term Memory (LSTM), and Bidirectional Long Short-Term Memory (BiLSTM).

## Overview

Misinformation has become a pervasive issue in the digital age, and accurately detecting fake news is crucial. This project explores the capabilities of CNN, LSTM, and BiLSTM models in identifying fake news, leveraging the LIAR dataset for training and evaluation. Our results show that while the CNN model demonstrates exceptional accuracy, the BiLSTM model excels in precision and recall.

## Key Features

- **Models Implemented**:
  - Convolutional Neural Network (CNN)
  - Long Short-Term Memory (LSTM)
  - Bidirectional Long Short-Term Memory (BiLSTM)
  
- **Dataset**: The LIAR dataset, which includes around 12.8 thousand manually verified statements from POLITIFACT.COM.

- **Evaluation Metrics**: Accuracy, precision, recall, and loss.

- **Approaches**:
  - 6-way classification (using original labels: Pants on fire, False, Barely true, Half true, Mostly true, True)
  - 2-way classification (binary classification: True or False)

## Results

- **CNN Model**: Achieved the highest accuracy with the 2-way classification approach.
- **BiLSTM Model**: Showcased superior precision and recall.
- **Comparison with Existing Research**: Our models, especially the CNN with 2-way classification, outperformed previous results from similar studies.

## Repository Contents

- `data/`: Contains scripts for loading and preprocessing the LIAR dataset.
- `notebook/`: Jupyter notebooks demonstrating the training and evaluation process.
- `results/`: Stores the results of our experiments, including accuracy, precision, recall, and loss metrics.
- `Fake News Detection Report`: A detailed report of the study and findings on fake news detection
- `README.md`: Provides an overview and instructions for setting up and running the project.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: numpy, pandas, tensorflow/keras, scikit-learn, matplotlib

## Usage

### Data Preprocessing
- Load and preprocess the LIAR dataset using the scripts provided in the `data/` directory.

### Model Training
- Train the CNN, LSTM, and BiLSTM models using the Jupyter notebook in the `notebook/` directory.

### Evaluation
- Evaluate the models using the provided evaluation metrics and compare the results.

## Acknowledgements
We acknowledge the creators of the LIAR dataset and previous researchers whose work provided a foundation for our study.
