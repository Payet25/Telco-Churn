This project explores customer churn behavior using the [shubh0799/churn-modelling dataset](https://www.kaggle.com/datasets/shubh0799/churn-modelling). It leverages Exploratory Data Analysis, Machine Learning models, and Time-Series Forecasting to deliver actionable insights and predictive capabilities for churn management.
The primary goal of this project is to identify key factors influencing customer churn, build predictive models to classify churners, and forecast churn trends to assist businesses in improving retention strategies.

Key Features of the Project
1. Exploratory Data Analysis
- Visualized target variable (`Exited`) distribution.
- Analyzed feature relationships like:
  - Age and Churn
  - Geography and Churn
  - Balance and Churn
  - CreditScore and Churn
- Generated heatmaps for feature correlation analysis.

2. Machine Learning Models
- Prepared data with encoding, scaling, and stratified splitting.
- Trained models to predict churn:
  - Random Forest Classifier for robust and interpretable predictions.
  - Achieved an ROC AUC Score of 78%.
- Visualized feature importances to understand predictive factors.

3. Time-Series Forecasting
- Used Exponential Smoothing to forecast churn trends across age groups.
- Provided actionable forecasts to assist in proactive customer retention efforts.

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/telco-churn-forecasting.git
