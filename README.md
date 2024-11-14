# Street Flood Prediction

This repository contains the code and data for predicting street-level flooding in urban areas using machine learning. The project utilizes a Random Forest regression model to forecast hourly water depth on streets during storm events based on topographic and environmental features.

## Project Overview

Urban flooding is a critical challenge in densely populated areas. Traditional flood prediction models are computationally intensive and may not be feasible for real-time applications. This project explores a machine learning-based surrogate model to provide accurate and efficient flood predictions, enabling quicker responses and better management of urban flood risks.

## Model

The project leverages a Random Forest regression model, which is suitable for handling non-linear relationships and feature importance analysis. The model uses a combination of topographic and environmental variables:

- **Topographic Features**: Elevation, Depth to Water (DTW), and Topographic Wetness Index (TWI)
- **Environmental Features**: Rainfall metrics over varying time intervals

The model achieved high accuracy, with an R² of 0.9977 on the training set and 0.9463 on the testing set, indicating its robustness and suitability for real-time urban flood forecasting.

## Repository Structure

- `events/` - Contains the event-based data files used for model training and testing.
- `oldfiles/` - Archive of previous files and versions.
- `test/` - Test data for model validation.
- `main.ipynb` - The main Jupyter notebook with the code for data preprocessing, model training, and evaluation.
- `LICENSE` - License file (MIT License).
- `README.md` - Overview and instructions for the project.

## Installation and Requirements

To run the code, make sure you have Python 3.x installed along with the following packages:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
  
Install dependencies using:
```bash
pip install -r requirements.txt
