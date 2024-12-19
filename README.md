# Regression with an Insurance Dataset

Welcome to the "Regression with an Insurance Dataset" repository! This project is my submission for the [Kaggle competition](https://www.kaggle.com/competitions/playground-series-s4e12/leaderboard?#), where I tackled the challenge of predicting insurance costs using a complex dataset. After a rollercoaster of data wrangling and model optimization, I achieved a score of 1.139 on the RMSLE metric.

## Project Overview

This repository contains the code and resources used to preprocess the data, build the model, and evaluate its performance. Here's a quick overview of what you'll find:

### Key Features

1. **Handling Missing Values:** Addressed the numerous missing values in the dataset to ensure data integrity.
2. **Encoding Categorical Data:** Transformed categorical variables into a format suitable for model training.
3. **Extracting Date-Time Features:** Broke down date-time data into individual features for better analysis.
4. **Scaling Numeric Values:** Applied scaling techniques to maintain consistency across numeric data.
5. **Outlier Management:** Identified and managed outliers using visualization techniques (a task that tested my patience!).
6. **Model Selection:** Opted for a Feedforward Neural Network (FNN) to capture the complex patterns in the data.
7. **Model Architecture:** Designed a model with an input layer, four hidden layers, and an output layer, incorporating batch normalization, dropout, regularization, EarlyStopping, and ReduceLROnPlateau.
8. **Model Evaluation:** Thoroughly assessed the model's performance to ensure no overfitting or underfitting.
9. **Test Data Preparation:** Prepared the test data for the final prediction submission.

## Getting Started

To get started with this project, clone the repository and follow the instructions in the `notebook.ipynb` file. You'll find detailed comments and explanations throughout the code to guide you through the process.

### Dataset

To download the dataset, use the following Kaggle API command:

```bash
kaggle competitions download -c playground-series-s4e12
```

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow, keras

## Contributing

Feel free to fork this repository and submit pull requests if you have any improvements or suggestions. Let's make this project even better together!

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
