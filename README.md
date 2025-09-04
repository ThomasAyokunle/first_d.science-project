# Loan Default Prediction with Machine Learning

> A complete end-to-end machine learning solution for predicting loan defaults, helping financial institutions make data-driven lending decisions and reduce portfolio risk.

## Project Overview

This project develops a comprehensive ML pipeline that predicts loan default probability using customer demographics, loan characteristics, and historical repayment data. The solution achieved **68% ROC-AUC** and includes production-ready deployment options.

## Key Features

- **Advanced Feature Engineering** - Loan-to-income ratios, temporal patterns, financial stress indicators
- **Model Optimization** - Hyperparameter tuning with GridSearchCV and threshold optimization
- **Interactive Dashboard** - Power BI visualization for risk analysis and portfolio monitoring  
- **Production Deployment** - Streamlit web app for real-time predictions
- **Complete Pipeline** - From raw data to deployable model with preprocessing

## Technical Highlights

- **Best Model**: LightGBM with 0.68 ROC-AUC score
- **Optimal Threshold**: 0.4 for balanced precision-recall trade-off
- **Key Risk Factors**: Loan-to-income ratio, customer age, interest fees
- **Data Handling**: SMOTE for class imbalance, robust preprocessing pipeline

## 🛠️ Technologies Used

**Machine Learning**: Python, Scikit-learn, LightGBM, XGBoost, Pandas, NumPy
**Visualization**: Power BI, Matplotlib, Seaborn  
**Deployment**: Streamlit, Joblib
**Data Processing**: SMOTE, StandardScaler, OneHotEncoder

## Business Impact

- **Risk Reduction**: Identify high-risk applications before approval
- **Portfolio Management**: Monitor existing loan portfolio health  
- **Dynamic Pricing**: Adjust interest rates based on predicted risk
- **Resource Optimization**: Focus collection efforts on high-risk accounts

## Model Performance

**Training Results:**
- Accuracy: 78.6%
- Precision: 55.6% 
- Recall: 9.9%
- ROC-AUC: 72.2%

**Optimal Threshold (0.4):**
- Precision: 29.7%
- Recall: 69.5%
- F1-Score: 41.6%

## 🚀 Quick Start

### 1. Explore the Analysis
# Open the Jupyter notebook
jupyter lab notebooks/loan_default_prediction.ipynb

View Interactive Dashboard

Download dashboards/loan_dashboard.pbix
Open in Power BI Desktop

Dashboard Features
The Power BI dashboard provides:

- Risk Distribution: Portfolio risk overview and trends
- Feature Analysis: Impact of key variables on default probability
- Performance Metrics
- Interactive Filters: Drill-down by demographics, loan types, time periods

Key Insights

- Loan-to-income ratio is the strongest predictor of default risk
- Customer age shows clear patterns with younger borrowers having higher risk
- Interest fees above certain thresholds correlate with increased defaults
- Employment type significantly impacts repayment reliability
- Seasonal trends exist in both approvals and default patterns

Learning Outcomes
This project demonstrates:

- End-to-end ML pipeline development
- Feature engineering for financial data
- Handling class imbalance with SMOTE
- Hyperparameter optimization techniques
- Model evaluation beyond accuracy metrics
- Production deployment considerations
- Business-focused model interpretation

Contributing
Feel free to:

Open issues for questions or suggestions
Share feedback on model performance
Suggest additional features or visualizations

📄 License
This project is open source and available under the MIT License.
