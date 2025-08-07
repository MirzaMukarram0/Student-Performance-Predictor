# Student Performance Predictor

## Overview

The Student Performance Predictor is a machine learning project designed to analyze and predict student exam scores based on various factors such as hours studied, attendance, previous scores, and motivation level. The project uses a linear regression model to estimate exam scores and provides visualizations to help understand the data distribution and model predictions.

## Features

- Loads and preprocesses student performance data
- Encodes categorical features for modeling
- Trains a linear regression model to predict exam scores
- Evaluates model performance using metrics (MAE, MSE, RMSE, R²)
- Visualizes exam score distribution and regression results
- Predicts exam scores for new student data

## Libraries Used

- **pandas**: Data manipulation and analysis
- **scikit-learn**: Machine learning algorithms and metrics
- **matplotlib**: Data visualization
- **numpy**: Numerical operations

## Files

- `StudentPerformance.ipynb`: Main notebook containing code for data analysis, modeling, and visualization
- `StudentPerformanceFactors.csv`: Dataset with student performance factors and exam scores

## Setup Instructions

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Student-Performance-Predictor.git
   ```
2. Install required Python libraries:
   ```
   pip install pandas scikit-learn matplotlib numpy
   ```
3. Place the dataset (`StudentPerformanceFactors.csv`) in the project directory.

## Usage

1. Open `StudentPerformance.ipynb` in Jupyter Notebook or VS Code.
2. Run the notebook cells to:
   - Load and preprocess the data
   - Train and evaluate the linear regression model
   - Visualize results
   - Predict exam scores for new data

## Example Prediction

You can input new student data (e.g., hours studied, attendance, previous scores, motivation level) and the model will predict the expected exam score.

## License

This project is licensed under the MIT License.

## Author

[Your Name]
