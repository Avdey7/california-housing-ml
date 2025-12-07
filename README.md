# Predicting California Housing Prices

Machine Learning regression project comparing Linear Regression vs Neural Network for predicting California housing prices.

## Installation
```bash
pip install -r requirements.txt
```

## Requirements
```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

## Usage
```bash
jupyter notebook housing_analysis.ipynb
```

Run all cells to train models and generate visualizations.

## Results

| Model | Test R² | Test RMSE |
|-------|---------|-----------|
| Linear Regression | 0.611 | $72.4k |
| Neural Network | 0.793 | $59.7k |

Neural Network achieves 29.9% improvement over Linear Regression.

## Dataset

California Housing (sklearn built-in)
- 20,640 samples
- 8 features
- Target: Median house value

## Project Structure
```
├── housing_analysis.ipynb
├── requirements.txt
└── README.md
```

Runtime: 3-5 minutes