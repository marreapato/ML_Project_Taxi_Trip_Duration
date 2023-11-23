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
3. **Linear Regression:** A simple linear model for baseline comparison.

## Deep Learning Models

1. **LSTM (Long Short-Term Memory):** A type of recurrent neural network (RNN) suitable for sequence prediction tasks.
2. **DNN (Deep Neural Network):** A feedforward neural network with multiple hidden layers.

## Evaluation Metrics

The performance of the models is evaluated using metrics such as mean squared error (MSE), mean absolute error (MAE), and R-squared.

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/your-username/taxi-trip-duration-prediction.git
cd taxi-trip-duration-prediction
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Explore the Jupyter notebooks in the `notebooks` directory for data analysis and preprocessing steps.

4. Train and evaluate the models using the scripts in the `src` directory.

## Usage

To train and evaluate the machine learning models, run the following commands:

```bash
python src/train_ml_models.py
```

To train and evaluate the deep learning models, run:

```bash
python src/train_dl_models.py
```

## Results

The results of the model evaluations, including performance metrics and visualizations, can be found in the `notebooks` directory.

## Contributors

- [Your Name]
- [Collaborator Name]

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute and improve this project!
