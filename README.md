Sentiment Analysis Model

This repository contains a Jupyter Notebook (Notebook.ipynb) that demonstrates the creation of a sentiment analysis model using TensorFlow and Keras. The model is designed to classify text data into different categories based on their sentiment. The following sections provide an overview of the tasks performed in the notebook.
Table of Contents

    Task 1: Import Libraries and Modules
    Task 2: Load the Datasets
    Task 3: Check the Missing Values
    Task 4: Check the Target Balance
    Task 5: Display the Distribution of Labeled Intents
    Task 6: Shuffle the Dataset
    Task 7: Transform the Data
    Task 8: Tokenize the Words
    Task 9: Pad the Training and Test Sequences
    Task 10: Encode the Labels
    Task 11: Prepare a Validation Set
    Task 12: Define a Neural Network Architecture
    Task 13: Fit the Model
    Task 14: Plot Training and Validation Loss Curves
    Task 15: Retrain the Model
    Task 16: Examine the Model’s Performance with the Test Dataset
    Task 17: Predict the Outcomes for New Data
    Task 18: Match Predictions with Severity Levels

Task 1: Import Libraries and Modules

The required libraries and modules for the sentiment analysis task are imported, including pandas, numpy, matplotlib, seaborn, and TensorFlow.
Task 2: Load the Datasets

Training and test datasets are loaded from CSV files (train.csv and test.csv) using pandas.
Task 3: Check the Missing Values

The notebook checks and handles missing values in the datasets.
Task 4: Check the Target Balance

The balance of the target categories in the training set is examined.
Task 5: Display the Distribution of Labeled Intents

The distribution of labeled intents in the training set is visualized using seaborn.
Task 6: Shuffle the Dataset

The training dataset is shuffled to ensure randomness during model training.
Task 7: Transform the Data

Text data from the datasets is transformed into NumPy arrays.
Task 8: Tokenize the Words

Words are tokenized using TensorFlow’s Tokenizer, converting them into sequences of integers.
Task 9: Pad the Training and Test Sequences

The sequences of integers are padded to a specified length for uniformity.
Task 10: Encode the Labels

The target labels are encoded into numerical values.
Task 11: Prepare a Validation Set

A validation set is created from the training data to monitor model performance during training.
Task 12: Define a Neural Network Architecture

A bidirectional LSTM neural network architecture is defined using TensorFlow's Keras API.
Task 13: Fit the Model

The model is compiled and trained on the partial training dataset.
Task 14: Plot Training and Validation Loss Curves

Training and validation loss curves are plotted using matplotlib.
Task 15: Retrain the Model

The model is retrained on the entire training dataset.
Task 16: Examine the Model’s Performance with the Test Dataset

The model's performance is evaluated on the test dataset.
Task 17: Predict the Outcomes for New Data

The trained model is used to predict outcomes for new data (queries).
Task 18: Match Predictions with Severity Levels

Predicted categories are matched with severity levels using a reference dataset (severity_levels.csv).

Feel free to explore the notebook for a detailed walkthrough of each task.
