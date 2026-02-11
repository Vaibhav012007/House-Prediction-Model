# House Price Prediction using XGBoost

This project implements a complete end-to-end Machine Learning pipeline to predict house prices using XGBoost (Extreme Gradient Boosting). The focus of this project is not just model training, but proper data preprocessing, exploratory data analysis (EDA), and evaluation.

---

## Project Overview

The objective of this project is to build a regression model that can accurately predict house prices based on multiple input features.

Instead of directly applying a model, this project emphasizes:

- Understanding the dataset  
- Cleaning and preprocessing data  
- Performing structured EDA  
- Evaluating model performance properly  

---

## Tech Stack

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  

---

## Workflow

### 1. Data Exploration (EDA)

- Checked dataset shape and data types  
- Analyzed missing values  
- Studied feature distributions  
- Generated correlation matrix  
- Visualized relationships using heatmaps and plots  

Goal: Understand the dataset before modeling.

---

### 2. Data Preprocessing

- Feature and target separation  
- Handled missing values  
- Selected relevant numerical features  
- Train-test split (80/20)  

Goal: Prepare clean, structured data suitable for regression modeling.

---

### 3. Model Building

- Implemented XGBRegressor  
- Trained the model on structured tabular data  
- Tuned basic parameters  

XGBoost was chosen due to:

- Strong performance on structured data  
- Built-in regularization  
- Ability to handle feature interactions effectively  

---

### 4. Model Evaluation

The model was evaluated using:

- R² Score  
- Mean Absolute Error (MAE)  

These metrics help measure:

- How well the model explains variance  
- Average prediction error magnitude  

---

## Repository Structure

House-Prediction-Model/  
│  
├── House-Prediction-model.ipynb  
├── dataset/  
└── README.md  

---

## How to Run the Project

1. Clone the repository  
   git clone https://github.com/Vaibhav012007/House-Prediction-Model  

2. Navigate to the project folder  
   cd House-Prediction-Model  

3. Install required libraries  
   pip install -r requirements.txt  

4. Open the Jupyter Notebook and run all cells  

---

## Future Improvements

- Hyperparameter tuning using GridSearch or RandomizedSearch  
- Feature engineering  
- Cross-validation  
- Model comparison with Linear Regression or Random Forest  
- Deployment using Flask or Streamlit  

---

## Author

Vaibhav Dhaka  

If you have suggestions or improvements, feel free to connect or open an issue.
