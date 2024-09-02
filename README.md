# 🚗 CarPrice-ML

CarPrice-ML is a machine learning project that predicts car prices based on a dataset with features such as make, color, odometer reading, number of doors, and more. The project uses a Random Forest Regressor model to predict car prices and includes steps to handle missing data, encode categorical features, and evaluate model performance using cross-validation.

## 📋 Project Overview

The dataset contains various features relevant to car pricing, such as the make of the car, its color, odometer reading, number of doors, and the target variable, the price of the car. This project involves preprocessing the data, handling missing values, encoding categorical features, and using a Random Forest Regressor for predicting car prices.

### 📝 Features Used:
- **Make**: The brand of the car.
- **Colour**: The color of the car.
- **Odometer (KM)**: The distance the car has traveled in kilometers.
- **Doors**: The number of doors on the car.
- **Price**: The target variable representing the price of the car.

### 📦 Dependencies

All the dependencies required to run the model are listed in the `requirements.txt` file. You can install them using the following command:

```bash
pip install -r requirements.txt
```

## 🚀 How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/maheera421/CarPrice-ML.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open and run the `CarPrice-ML.ipynb` notebook to preprocess the data, train the model, and evaluate its performance.

## 📊 Model Evaluation

The project evaluates the model using cross-validation with the following metrics:
- **R-squared**: Measures the proportion of variance in the dependent variable that is predictable from the independent variables.
- **Mean Squared Error (MSE)**: Measures the average of the squares of the errors, i.e., the difference between the observed and predicted values.
- **Mean Absolute Error (MAE)**: Measures the average magnitude of the errors in a set of predictions, without considering their direction.

The results obtained using cross-validation help in assessing the accuracy and performance of the model.

