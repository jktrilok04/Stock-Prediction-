# Stock Price Prediction with Machine Learning

## Overview
This project focuses on predicting stock price movements using various machine learning models. The dataset is preprocessed and analyzed using technical indicators, and different models are evaluated based on key performance metrics.

## Purpose
The goal of this project is to build a predictive model that can analyze historical stock price data and identify potential trading opportunities using machine learning techniques.

## Key Features
- **Data Preprocessing**: Handling missing values, feature scaling, and engineering new features from technical indicators.
- **Technical Indicators**: Includes Relative Strength Index (RSI), Moving Averages, and more.
- **Machine Learning Models**: Implements multiple models like Linear Regression, XGBoost, LightGBM, and Random Forest.
- **Ensembling Techniques**: Uses a Voting Regressor to combine model predictions for improved accuracy.
- **Backtesting**: Evaluates the model’s performance by simulating historical trades.
- **Win Rate Analysis**: Computes the win rate of predictions to assess trading strategy effectiveness.
- **Performance Metrics**: Compares models based on Mean Squared Error (MSE) and R² score.

## Data Preprocessing
- Handled missing values.
- Normalized data for better model performance.
- Created new features from technical indicators.
- Split data into training and testing sets.

## Models Used
- **Linear Regression**
- **XGBoost Regressor**
- **LightGBM Regressor**
- **Random Forest Regressor**
- **Voting Regressor** (ensemble of multiple models)

## Evaluation Metrics
| Model               | Mean Squared Error | R² Score  |
|--------------------|------------------|----------|
| Linear Regression | 378.09           | 0.9953   |
| XGBoost           | 1533.18          | 0.9808   |
| LightGBM          | 1448.95          | 0.9819   |
| Random Forest     | 1648.29          | 0.9794   |
| Voting Regressor  | 766.10           | 0.9904   |

## Visualizations
- **RSI Plot**: Displays RSI values over time with overbought/oversold levels.
- **Win Rate Comparison**: A bar chart comparing win rates of all models.
- **Final Model Metrics**: MSE and R² score comparison for model selection.

## Backtesting
- Evaluates the model’s effectiveness by applying predictions to historical data.
- Helps analyze potential profitability of the strategy.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/jktrilok04/Stock-Prediction-.git
   cd stock-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to train and evaluate models.

## Conclusion
The Voting Regressor demonstrated the best balance between accuracy and error metrics. The project highlights the potential of machine learning in stock price prediction, with further improvements possible through feature engineering and hyperparameter tuning.

