# Taxi Trip Duration Prediction Project

## Overview

This machine learning project is part of a computer science master's degree course at UFPE (Federal University of Pernambuco), inspired by a Kaggle competition. The goal of the project is to predict the duration of taxi trips using a combination of both deep learning and traditional machine learning techniques.

## Dataset

The dataset used for this project is sourced from the Kaggle competition and consists of historical taxi trip data, including information such as pickup and drop-off locations, timestamps, and other relevant features. The dataset has been preprocessed to handle missing values, outliers, and other data quality issues.

## Features

The features used in the model include:

- Pickup and drop-off locations (latitude and longitude)
- Timestamp of the taxi trip
- Additional contextual features (e.g., weather conditions, traffic information)

## Project Structure

The project is organized into the following directories:

- **data:** Contains the dataset used for training and testing the models.
- **notebooks:** Jupyter notebooks used for data exploration, preprocessing, and model training.
- **src:** Source code for the machine learning and deep learning models.
- **models:** Saved models after training for later use.

## Machine Learning Models

The project employs a combination of traditional machine learning algorithms and deep learning models to predict taxi trip duration. The machine learning models include:

1. **Random Forest:** A decision tree ensemble method for regression.
2. **XGBoost:** A gradient boosting algorithm for regression.

## Deep Learning Models

1. **ANN (Aetificial Neural Network)** A Feedforward Neural Network with multiple neurons

## Evaluation Metrics

The performance of the models is evaluated using the root mean squared error (RMSE)

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/your-username/taxi-trip-duration-prediction.git
cd taxi-trip-duration-prediction
```

2. Explore the Jupyter notebooks in the `notebooks` directory for data analysis and preprocessing steps.

3. Train and evaluate the models using the scripts.

## Contributors

- [Lucas Rabelo]

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute and improve this project!
