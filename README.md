# Fuel Efficiency Tracker

## Project Overview
This project provides a dual-approach solution for fuel efficiency monitoring:
- A **manual fuel tracking tool** for user-input data.
- **Machine learning models** to predict fuel efficiency using historical fleet data.

Developed by **Ziad Wael** and **Sama Mohamed Eldessouky** (Nile University).

## Repository Structure
- `MLpreproc.ipynb` – Data preprocessing and cleaning pipeline
- `MLmodels.ipynb` – Implementation and evaluation of ML models
- `README.md` – This file

## Dataset
The dataset is sourced from **Data Mill North**, containing fleet vehicle performance and fuel usage records from 2018 to 2023.

## Models Implemented
- Linear Regression
- Polynomial Regression
- Artificial Neural Networks (ANN)

## Requirements
- Python 3.7+
- pandas, numpy, seaborn, matplotlib, scikit-learn, tensorflow/keras

## Usage
1. Run `MLpreproc.ipynb` to clean and merge the dataset.
2. Run `MLmodels.ipynb` to train and evaluate prediction models.

## Results
The system provides accurate fuel efficiency predictions and visual insights to help drivers and fleet managers make informed decisions.
