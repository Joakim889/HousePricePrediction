# House Price Prediction with PyTorch

This repository contains a machine learning project that builds a deep learning regression model to predict house prices using a real-world dataset. The project is implemented as a Jupyter notebook (`main.ipynb`) and demonstrates data preprocessing, model training, evaluation, and prediction using PyTorch.

## Features

- **Data Cleaning**: Handles missing values by dropping columns with more than 50% missing data and imputing others appropriately.
- **Feature Normalization**: Numeric features scaled using `StandardScaler`; categorical variables are one‑hot encoded.
- **Train/Validation/Test Split**: Data is split 60/20/20 to ensure proper training and unbiased evaluation.
- **Deep Learning Model**: A multi-layer perceptron with batch normalization and dropout layers implemented in PyTorch.
- **Training with Early Stopping**: Monitors validation loss and saves the best model to `best_model.pth`.
- **Evaluation Metrics**: Computes MSE, RMSE, MAE, and R² on the test set, and visualizes results.
- **Interactive Prediction**: Provides code to input custom feature values and get a price prediction.

## 🛠️ Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Joakim889/HousePricePrediction.git
   cd HousePricePredict
   ```

2. Create a Python virtual environment and install dependencies:
   ```bash
   py -3.11 -m venv venv
   venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook and open `main.ipynb`

> **Note:** Ensure the dataset (`House_Price_Prediciton_Data.xlsx`) is placed in the project root before running the notebook.

## 📚 Dependencies

See `requirements.txt` for a full list. Key libraries include:

- `python 3.11`
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `torch` (PyTorch)

## 📝 License

This project is provided for educational purposes. Feel free to use, modify, or extend the code.

---