# machine-learning
# Human Activity Recognition using Wearable Sensor and Machine Learning

![Human Activity Recognition]

## Overview

This project is aimed at developing a machine learning model to recognize and classify human activities based on data collected from wearable sensors. The dataset contains various features extracted from accelerometer and gyroscope readings of wearable devices while individuals perform different activities.

The goal is to build a predictive model that can accurately classify activities such as walking, running, sitting, standing, etc., based on the sensor data.

## Dataset

The dataset used in this project can be found [ https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones ]. It contains a collection of samples, each representing a particular activity performed by a person. The features include various statistical measures and time-domain features derived from the sensor data.

## Project Structure

The project repository is organized as follows:

- `data/`: Contains the dataset used for training and evaluation.
- `notebooks/`: Jupyter notebooks containing the data exploration, preprocessing, model training, and evaluation steps.
- `trained_models/`: Saved trained models that can be used for prediction.
- `README.md`: This file, providing an overview of the project.

## Dependencies

The following libraries are required to run the Jupyter notebooks:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels

You can install them using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

License
This project is licensed under the MIT License.

Acknowledgments
Special thanks to the creators of the dataset used in this project for providing valuable data for research and development.
