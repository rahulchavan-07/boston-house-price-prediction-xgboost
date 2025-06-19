# 🏠 House Price Prediction using Machine Learning (Boston Dataset)

This project uses a Machine Learning model to predict house prices based on various features of the Boston Housing dataset. The implementation is done in Python using libraries such as Pandas, NumPy, Scikit-learn, and XGBoost.

## 📊 Dataset
The dataset includes several key features that influence house pricing, such as:
- CRIM: Per capita crime rate by town
- ZN: Proportion of residential land zoned for large lots
- INDUS: Proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- NOX: Nitric oxide concentration
- RM: Average number of rooms per dwelling
- AGE: Proportion of owner-occupied units built before 1940
- DIS: Weighted distance to employment centers
- TAX: Property-tax rate
- LSTAT: % lower status of the population
- **MEDV**: Median value of owner-occupied homes (Target Variable)

## 🧠 Model Used
- **XGBoost Regressor**
- Data preprocessing includes:
  - Handling missing values
  - Feature selection
  - Data normalization (if needed)
- Evaluation metrics:
  - **R² Score**
  - **Mean Absolute Error (MAE)**

## 📈 Model Evaluation
The model performance is evaluated using:
- Training Score
- Testing Score
- Residual plots to compare predicted vs actual values
- Error metrics to quantify model accuracy

## 🔧 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
- Jupyter Notebook
