# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using a machine learning approach. The model is trained on a dataset of credit card transactions, using logistic regression for classification. The project addresses the issue of imbalanced data by employing under-sampling techniques.

## Overview

The goal of this project is to accurately identify fraudulent credit card transactions from a dataset containing both normal and fraudulent transactions. The logistic regression model is used for its simplicity and effectiveness in binary classification problems.

## Features

- **Data Collection:** The dataset consists of credit card transactions, typically including features such as transaction amount, transaction time, and more.
- **Data Preprocessing:** The data is cleaned and normalized, with particular attention to handling class imbalance through under-sampling.
- **Model Training:** The logistic regression model is trained on the prepared dataset.
- **Model Evaluation:** The model's performance is evaluated using metrics such as accuracy score.
- **Prediction:** The trained model is used to classify new transactions as normal or fraudulent.

## Technologies Used

- **Python:** The primary programming language used for the project.
- **Pandas:** For data manipulation and analysis.
- **NumPy:** For numerical computations.
- **scikit-learn:** For machine learning algorithms and model evaluation.

## Installation

To get started with the project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/Harshith5314/Credit-Card-Fraud-Detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
```

## Usage

1. **Data Preparation:**
   - Ensure you have the credit card transaction dataset in CSV format.
   - Update the data file path in the script.

2. **Training the Model:**
   - Run the training script to train the logistic regression model on your data.
   ```bash
   python train.py
   ```

3. **Making Predictions:**
   - Use the trained model to classify new transactions.
   ```bash
   python predict.py
   ```


## Results

The model's accuracy is reported and can be further improved with additional techniques such as feature engineering, hyperparameter tuning, and using more advanced algorithms.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
