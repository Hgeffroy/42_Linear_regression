# 42_Linear_regression

## 🎯 Description  
The **42_Linear_regression** project aims to implement a simple (and/or multiple) linear regression model in order to apply and understand the basic concepts of machine learning: data loading, normalization, gradient descent algorithm, prediction, etc.

## 🛠️ Installation  
Make sure you have the following prerequisites installed:  
- Python 3  
- Required libraries:  
  ```bash
  pip install -r requirements.txt
  ```
  
## 🚀 Usage
Place your dataset file in assets/data.csv

Start by training the model:
```bash
python3 src/train.py
```

You can then make a prediction:
```bash
python3 src/estimate.py
```

More options are available through the main program:
```bash
python3 src/main.py --help
```

## 📌 Concepts Covered
- Simple linear regression: y = ax + b
- Feature normalization / standardization
- Gradient descent algorithm to determine coefficients a and b
- Model evaluation: Mean Squared Error (MSE), coefficient of determination (R²)
- Visualization of results (matplotlib, etc.)
