# 🤖 Automation Probability Prediction Using Machine Learning

Predict the probability that a job will be automated by **2030** using a **Random Forest Regressor**. This project demonstrates an end-to-end machine learning workflow, including data preprocessing, feature engineering, model training, and performance evaluation.

## 📌 Project Overview

The objective of this project is to estimate the **Automation Probability (2030)** for different job roles using machine learning. The project follows a complete ML pipeline from data exploration to model evaluation.

## 📂 Dataset Information

- **Dataset:** AI Impact on Jobs 2030
- **Records:** 3000
- **Features:** 18
- **Target Variable:** Automation_Probability_2030

## 🚀 Features

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- One-Hot Encoding
- Binary Encoding
- Train / Validation / Test Split
- Random Forest Regression
- Model Evaluation

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Category Encoders
- Jupyter Notebook

## 📊 Model Performance

| Dataset    | MAE     | RMSE   | R² Score |
|------------|---------|--------|----------|
| Validation | 0.0818  | 0.0996 | 0.8488   |
| Test       | 0.0789  | 0.0960 | 0.8524   |

### Key Findings

- The model explains approximately **85%** of the variance in automation probability.
- Validation and test scores are very similar, indicating good generalization.
- Random Forest Regressor achieved reliable predictive performance on unseen data.

## 📁 Repository Structure

Automation-Probability-Prediction/
  - Automation_Probability_Prediction.ipynb
  - AI_Impact_on_Jobs_2030.csv
  - requirements.txt
  - README.md
  - .gitignore
  - LICENSE

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Gautamsingh98/automation-probability-prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run all cells sequentially.

## 📈 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Build an interactive Streamlit web application
- Deploy the model using FastAPI
