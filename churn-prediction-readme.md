# Customer Churn Prediction Project

## Overview
This project implements various machine learning models to predict customer churn using historical customer data. The analysis includes data preprocessing, feature selection, model training, and comprehensive performance evaluation of multiple classification algorithms.

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Models Implemented](#models-implemented)
- [Features](#features)
- [Results](#results)
- [Contributing](#contributing)

## Requirements
- Python 3.8+
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn
- warnings

## Installation
1. Clone the repository:
```bash
git clone <repository-url>
cd customer-churn-prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Project Structure
```
customer-churn-prediction/
│
├── data/
│   └── Customer Churn.csv
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── evaluation.py
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── README.md
└── requirements.txt
```

## Usage
1. Prepare your data in CSV format with similar structure to the provided example
2. Run the main analysis script:
```python
python src/main.py
```

## Models Implemented
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost Classifier
- AdaBoost Classifier
- Support Vector Machine (SVM)

## Features
- Comprehensive data preprocessing
- Automated feature selection using SelectKBest
- Multiple model comparison and evaluation
- Cross-validation for model stability
- Feature importance analysis
- ROC and Precision-Recall curves
- Confusion matrices for all models
- Hyperparameter tuning using GridSearchCV

## Results
The project achieves the following key results:
- Random Forest achieved the highest accuracy with optimized hyperparameters
- Gradient Boosting and XGBoost showed competitive performance
- Feature importance analysis revealed key factors influencing customer churn
- Cross-validation confirmed model stability across different data splits

### Model Performance Summary
- Random Forest: Best overall performance with optimal hyperparameters
- Gradient Boosting: Strong performance with good generalization
- XGBoost: Competitive results with efficient training
- Other models (Logistic Regression, AdaBoost, SVM): Provided baseline comparisons

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Dataset source: [provide source if applicable]
- Contributors and maintainers
- Any third-party libraries or resources used
