# House Price Prediction Assignment

This project is focused on predicting house prices using various regression models. The dataset used is from the [Kaggle House Prices - Advanced Regression Techniques competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

## 🌐 Live Demo
You can view the project hosted via GitHub Pages here:
👉 https://arpitdhasmana.github.io/CelebalTechnologies_week5/

## 📂 Files Included

- `train.csv`: Training dataset
- `test.csv`: Test dataset
- `sample_submission.csv`: Sample format for submission
- `house_price_prediction.ipynb`: Jupyter notebook containing the full pipeline
- `house_price_prediction.html`: HTML export of the notebook (for viewing without Jupyter)

## 🔍 Workflow Overview

1. **Data Preprocessing & Feature Engineering**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
   - Train-validation split

2. **Exploratory Data Analysis (EDA)**
   - Target variable analysis
   - Feature correlation and importance

3. **Model Training & Evaluation**
   - Linear Regression
   - Ridge Regression
   - Lasso Regression
   - ElasticNet Regression
   - Polynomial Regression
   - k-Nearest Neighbors
   - Decision Tree Regressor
   - Random Forest Regressor
   - Support Vector Regressor (SVR)

4. **Model Comparison**
   - Mean Absolute Error (MAE) used for evaluation
   - Bar plot comparing performance of all models

## 🛠️ Technologies Used

- Python
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🚀 How to Run

1. Install requirements (optional):
    ```bash
    pip install numpy pandas matplotlib seaborn scikit-learn jupyter
    ```

2. Open the notebook:
    ```bash
    jupyter notebook house_price_prediction.ipynb
    ```

3. To convert notebook to HTML (already included):
    ```bash
    python -m nbconvert --to html house_price_prediction.ipynb
    ```

---

**Author**: Arpit  
**Project**: ML Regression Models for House Price Prediction  
**Date**: July 2025
