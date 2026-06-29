# Plane Price Prediction

A machine learning project for predicting airplane ticket prices using advanced regression models.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project implements machine learning models to predict airplane ticket prices based on historical data and various features. By leveraging ensemble learning techniques, we achieve highly accurate price predictions with minimal error margins.

## ✨ Features

- **Multiple ML Models**: Random Forest and XGBoost Regressors
- **High Accuracy**: R² Score of 0.95 (95% variance explained)
- **Low Error Margin**: Mean Absolute Error of $145,061
- **Data Visualization**: Density plots for model performance analysis
- **Robust Ensemble Learning**: Handles complex datasets effectively

##  Project Structure

```
plane_price_prediction/
├── model.ipynb          # Main ML model implementation
├── README.md            # Project documentation
└── data/                # Dataset files (if applicable)
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YassineSdk/plane_price_prediction.git
cd plane_price_prediction
```

2. Create a virtual environment:
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

## 📖 Usage

Run the Jupyter notebook to train and evaluate models:

```bash
jupyter notebook model.ipynb
```

The notebook includes:
- Data loading and preprocessing
- Feature engineering
- Model training (Random Forest & XGBoost)
- Performance evaluation
- Visualization of results

## Models

### Random Forest
- Ensemble learning method using multiple decision trees
- Robust against overfitting
- Reliable for regression tasks
- Outputs the average prediction of all trees

### XGBoost (Extreme Gradient Boosting)
- Sequential tree building with error correction
- Particularly effective for accuracy improvement
- Handles complex datasets efficiently
- Optimized gradient boosting framework

## Results

| Metric | Value |
|--------|-------|
| **R² Score** | 0.95 |
| **Mean Absolute Error (MAE)** | $145,061 |
| **Variance Explained** | 95% |

**Key Findings:**
- Both models demonstrate strong predictive capabilities
- High R² score indicates excellent model fit
- Density plots show good alignment between predicted and actual values
- Models are suitable for production deployment

## Contributing

Contributions are welcome! Feel free to:
- Report issues
- Suggest improvements
- Submit pull requests

## License

This project is open source and available under the MIT License.

---

**Author:** [YassineSdk](https://github.com/YassineSdk)  
**Last Updated:** 2026
