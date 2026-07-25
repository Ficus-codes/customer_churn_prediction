# Customer Churn Prediction

A Machine Learning project that predicts whether a customer is likely to churn using customer demographic information, subscription details, and spending behavior.

---

## Project Overview

Customer churn directly affects business profitability. This project uses machine learning algorithms to classify customers into:

- Churn
- No Churn

Several classification models are trained and compared to determine the most accurate model.

---

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess customer data
- Visualize important trends
- Train multiple ML classification models
- Compare model performance
- Select the best-performing model
- Predict customer churn for unseen data

---

## Dataset

The dataset contains customer information such as:

- Customer ID
- Age
- Gender
- Monthly Spending
- Subscription Length
- Usage Frequency
- Customer Support Calls
- Other customer-related features
- Churn (Target Variable)

Target Variable:

- **0 → No Churn**
- **1 → Churn**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Machine Learning Models Used

The project compares multiple classification algorithms including:

- Logistic Regression
- Random Forest
- Gradient Boosting

The best model is selected using evaluation metrics.

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis
4. Data Visualization
5. Data Preprocessing
6. Train-Test Split
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. Best Model Selection
11. ROC-AUC Analysis
12. Feature Importance
13. Sample Predictions

---

## Visualizations

The project includes several visualizations:

- Feature Distributions
- Churn Rate Analysis
- Correlation Heatmap
- Confusion Matrix
- ROC-AUC Curve
- Feature Importance Graph

---

## Evaluation Metrics

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

## Project Structure

```
Customer-Churn-Prediction/
│
├── CUSTOMER_CHURN_PREDICTION.ipynb
├── customer_churn_dataset.csv
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
CUSTOMER_CHURN_PREDICTION.ipynb
```

Run all cells.

---

## Results

The project compares multiple machine learning models and automatically selects the best-performing model based on evaluation metrics.

The final model provides:

- High prediction accuracy
- Churn probability for each customer
- Feature importance analysis
- Easy interpretation through visualizations

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- XGBoost and LightGBM models
- Deployment using Flask or FastAPI
- Interactive dashboard using Streamlit
- Real-time churn prediction API

---

## Learning Outcomes

Through this project, I gained experience in:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Classification
- Model Evaluation
- Data Visualization
- Business Problem Solving

---

## Author

**Saurav Sundriyal**

## Github: https://github.com/Ficus-codes
