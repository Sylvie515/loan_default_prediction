# Loan Default Prediction  

Machine learning project for loan default prediction using Logistic Regression, Random Forest, and XGBoost.  

The project includes exploratory data analysis (EDA), feature engineering, hyperparameter tuning, model evaluation, and business interpretation.  

## Project Overview  

This project develops machine learning models to predict loan default risk using borrower demographic, financial, and credit-related information.  

The project workflow includes:  
- Exploratory Data Analysis (EDA)  
- Data Preprocessing  
- Feature Engineering
- Multicollinearity Analysis (VIF)  
- Model Development  
- Hyperparameter Tuning  
- Model Evaluation  
- Business Interpretation  

Three supervised machine learning models were developed and compared:  
- Logistic Regression (baseline model)  
- Random Forest  
- XGBoost  

Among these models, XGBoost achieved the best predictive performance with a ROC-AUC score of 0.9600.  

## Dataset  

The original dataset used for this project is not included in this repository.  

## Technologies  

- Python  
- Pandas  
- NumPy
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Logistic Regression  
- Random Forest  
- XGBoost  
- RandomizedSearchCV  

## Model Performance  

| Model | ROC-AUC |  
|:--- | ---:|   
| Logistic Regression | 0.9043 |  
| Random Forest       | 0.9417 |  
| XGBoost             | **0.9600** |  

## Results  

- XGBoost achieved the highest ROC-AUC score (0.9600) for loan default prediction.  
- Tree-based models outperformed Logistic Regression, suggesting that nonlinear relationships play an important role in loan default prediction.  
- Loan grade, financial burden (loan_percent_income), and housing status were identified as the strongest predictors of loan default risk.  

## Project Structure  

```text
.
├── Report.pdf
├── EDA.ipynb    # Notebook for exploratory data analysis (EDA)
├── ML.ipynb     # Main notebook for machine learning modeling
└── README.md  
```
