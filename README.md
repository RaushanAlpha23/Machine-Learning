# Machine-Learning
# 🧠 Machine Learning - Diabetes Classification

This project demonstrates a complete machine learning workflow to classify diabetes risk using logistic regression. It includes data preprocessing, modeling using Scikit-learn's Pipeline, evaluation, and visualization.

---

## 📁 Dataset

The dataset used is the built-in **Diabetes dataset** from `sklearn.datasets`. It contains medical records of patients with 10 features.

- `Target`: Binary label indicating disease progression (`0`: below average, `1`: above average).

---

## 📌 Project Structure

├── main.py # Main script to train and evaluate the model
├── pipeline.pkl # (Optional) Saved trained pipeline
├── requirements.txt # List of dependencies
├── README.md # This file

---

## 🧪 Features Used

- Age
- BMI
- Blood Pressure
- Serum Measurements
- (All standard features from `sklearn.datasets.load_diabetes()`)

---

## ⚙️ Model Pipeline

Implemented using Scikit-learn's `Pipeline`:

1. **Imputation**: Fill missing values using `SimpleImputer`
2. **Scaling**: Standardize features using `StandardScaler`
3. **Polynomial Features**: Capture nonlinear relationships (optional)
4. **Model**: Logistic Regression for binary classification

---

## 🚀 How to Run

```bash
# Clone this repository
git clone https://github.com/yourusername/ml-diabetes-pipeline.git
cd ml-diabetes-pipeline

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the main script
python main.py
