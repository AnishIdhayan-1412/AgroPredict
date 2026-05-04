# AgroPredict - Crop Yield Prediction

## Overview
AgroPredict is a machine learning project that predicts crop yield based on soil nutrients (N, P, K), temperature, and fertilizer usage.

## Features
- Predicts crop yield using Random Forest Regressor
- Analyzes feature importance (soil nutrients, temperature, fertilizer)
- Provides visualization of actual vs predicted yields
- Achieves 99% R² accuracy

## Dataset
The dataset includes:
- Fertilizer amount
- Temperature
- Nitrogen (N) levels
- Phosphorus (P) levels
- Potassium (K) levels
- Crop yield (target variable)

## Requirements
pandas
numpy
matplotlib
scikit-learn


## Usage
1. Upload your dataset (CSV format with columns: Fertilizer, temp, N, P, K, yeild)
2. Run all cells in the Jupyter notebook
3. Model will train and display performance metrics

## Model Performance
- R² Score: 0.9908
- Mean Squared Error: 0.0347

## Results
The model achieves high accuracy in predicting crop yield based on the input parameters. Feature importance analysis shows which factors most significantly impact yield.

## Author
[Your Name]

## License
MIT