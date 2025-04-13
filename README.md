# first_logistic_regression_model
python is used, ML model
# Logistic Regression Model (Saved & Reusable)

This project uses logistic regression to classify 0,1 or 2 caterory of the iris dataset.

## 📁 Files Included

- `your_notebook.ipynb` — Full training, testing, and model saving code
- `logistic_regression_model.pkl` — Saved model using `joblib`
- `data.csv` — Dataset used (or see link below)

## 📊 Dataset Source

You can download the dataset from:
just as i have loaded it in the code itself.

## 🚀 How to Use

1. Clone the repo or download the files.
2. Run the notebook OR use the saved model like this:

```python
import joblib
model = joblib.load("logistic_regression_model.pkl")
prediction = model.predict([your_input_here])
