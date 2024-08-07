# Power Plant Output Prediction

Welcome to the Power Plant Output Prediction project. This project focuses on predicting the net hourly electrical energy output of a power plant using machine learning techniques, utilizing ambient temperature, ambient pressure, relative humidity, and exhaust vacuum as features.

## Table of Contents

- [Introduction](#introduction)
- [Dataset Information](#Dataset-Information)
- [Setup and Required Installs](#setup-and-required-installs)
- [Model Selection](#model-selection)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction

Predicting the net hourly electrical energy output of a power plant is crucial for optimizing performance and efficiency. This project aims to develop a machine learning model to predict the power output based on ambient conditions. By accurately forecasting the power output, power plants can improve their operational planning and reduce costs.

## Dataset Information

The dataset used for this project includes the following attributes:

- Ambient Temperature (AT)
- Ambient Pressure (AP)
- Relative Humidity (RH)
- Exhaust Vacuum (V)
- Net hourly electrical energy output (PE) - Target variable

## Setup and Required Installs

To run the project, you need to set up your environment and install the required dependencies:

1. Clone this repository:

```bash
git clone https://github.com/dhanushkorada/Power-Plant-Output-Prediction.git
```

```bash
cd Power-Plant-Output-Prediction
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Model Selection

Several Regression models are tested to predict the predict the power plant output:

- Support Vector Regression
- Decision Tree Regression
- Random Forest Regression
- Multiple Linear Regression
- Polynomial Regression

The process includes the following steps:

- Importing the Libraries: Import the necessary libraries for data manipulation and visualization.
- Importing the Dataset: Load the dataset from a CSV file into a pandas DataFrame.
- Splitting the Dataset: Split the data into training and testing sets.
- Training the Model: Train a Random Forest Regressor on the training set.
- Predicting the Results: Use the trained model to predict the test set results.
- Evaluating the Model Performance: Evaluate the model's performance using the R-squared (R2) score.


## Results

After evaluating the performance of various models using Accuracy Score the Random Forest Regression model is chosen as the optimal model due to its higher R2 score in predictions. The results of the Random Forest Regression model are discussed with the help of performance metrics in the Jupyter Notebook provided in the repository. The R-squared score indicates how well the model is able to predict the power plant output based on the given features.

## Conclusion
The Power Plant Output Prediction model developed in this project offers a valuable tool for optimizing power plant operations. By accurately predicting the net hourly electrical energy output, power plants can improve their operational planning, enhance efficiency, and reduce operational costs.

## License

This project is licensed under the [MIT License](LICENSE).
