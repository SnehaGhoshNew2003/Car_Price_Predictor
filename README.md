# Car Price Predictor

This project builds a **machine learning model** to predict car prices based on various attributes using **Linear Regression**.

## Features
- **Data Cleaning:** Handles missing values and incorrect data formats.
- **Feature Engineering:** Applies OneHotEncoding for categorical variables.
- **Model Training:** Uses **Linear Regression** for predicting car prices.
- **Pipeline Creation:** Implements an end-to-end processing pipeline.
- **Model Persistence:** Saves trained models using `pickle`.

## Technologies Used
- **pandas** (Data manipulation)
- **numpy** (Numerical operations)
- **scikit-learn** (ML model training & evaluation)
- **pickle** (Model storage)

## Installation
Install the required dependencies:
```bash
pip install pandas numpy scikit-learn
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Car_Price_Predictor.git
cd Car_Price_Predictor
```
2. Run the Jupyter Notebook:
```bash
jupyter notebook Car_Price_Predictor.ipynb
```
3. Follow the notebook instructions to preprocess data, train the model, and make predictions.

## Example Output
- **Input:** Car details (year, brand, mileage, fuel type, etc.)
- **Output:** Predicted car price

## Contributing
Feel free to submit issues or pull requests to improve this project.
