

# README: Multivariate LSTM Temperature Prediction

## Overview
This repository contains code for predicting temperature using a Multivariate LSTM (Long Short-Term Memory) neural network. The model takes into account both temperature and heater power as input features to predict the temperature.

## Files
1. `multivariate_lstm_temperature_prediction.ipynb`: This Jupyter Notebook contains the Python code for training the Multivariate LSTM model, evaluating it on test data, and making predictions.
2. `TCLab_train_data.txt`: This file contains the training data consisting of temperature (T1) and heater power (Q1) readings.
3. `TCLab_test_data.txt`: This file contains the test data for validating the trained model.

## Requirements
- Python 3.x
- PyTorch
- NumPy
- pandas
- scikit-learn
- matplotlib

## Usage
1. Clone this repository to your local machine.
2. Ensure you have all the required dependencies installed.
3. Open and run the `multivariate_lstm_temperature_prediction.ipynb` notebook using Jupyter or any compatible environment.
4. Follow the instructions provided in the notebook to train the model, evaluate its performance on test data, and make predictions.

## Note
- Make sure to update the file paths in the notebook if your data files are stored in a different location.
- Adjust hyperparameters such as sequence length, batch size, number of epochs, etc., as needed for your specific use case.
- Feel free to modify the code to experiment with different architectures, preprocessing techniques, and evaluation methods.

---

This README file provides an overview of the code, lists the files included, specifies the requirements, and outlines the usage instructions. It also includes some notes for customization and further experimentation. Let me know if you need further clarification or assistance!
