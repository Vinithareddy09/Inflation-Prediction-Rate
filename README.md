# Inflation Prediction Rate 📈🧠

A machine learning-based project that predicts the inflation rate using historical financial and economic data. This project leverages regression techniques to model trends and forecast future inflation rates.

## 🧾 Overview

- Load and preprocess historical inflation and related economic indicators  
- Train regression models to predict future inflation  
- Visualize prediction results for analysis and interpretation  
- Useful for academic research, economic forecasting, or ML experimentation

## 🛠 Tech Stack

- **Language**: Python  
- **Libraries**:  
  - `pandas` – data loading and preprocessing  
  - `numpy` – numerical operations  
  - `matplotlib`, `seaborn` – data visualization  
  - `scikit-learn` – regression modeling and evaluation  
- **Platform**: Jupyter Notebook / Python script

## 🚀 Features

- Data preprocessing and feature engineering  
- Multiple regression algorithms (Linear, Ridge, etc.)  
- Accuracy metrics like RMSE or R²  
- Line plots comparing actual vs predicted inflation  
- Easy-to-modify code for different datasets

## 📦 How to Run

```bash
# Clone the repository
git clone https://github.com/Vinithareddy09/Inflation-Prediction-Rate.git
cd Inflation-Prediction-Rate

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
# If using Jupyter Notebook
jupyter notebook inflation_prediction.ipynb

# OR if using a Python script
python inflation_prediction.py
