# Solar Energy Production Prediction

## Project Overview

This project predicts annual solar energy production using machine learning techniques and solar installation data. The objective is to estimate the expected yearly energy generation of photovoltaic (PV) systems based on system specifications, installation details, and historical records.

---

## Business Problem

Accurate prediction of solar energy generation is important for:

- Renewable energy planning
- Solar project feasibility analysis
- Energy demand forecasting
- Investment decision making
- Grid management and optimization

This project uses machine learning to estimate annual solar energy production and support data-driven renewable energy planning.

---

## Dataset

Dataset: Solar Energy Production Dataset

Target Variable:

- Estimated Annual PV Energy Production (kWh)

Features include:

- PV System Size (kWdc)
- PV System Size (kWac)
- Energy Storage System Size
- Installation Information
- Interconnection Date
- Geographic and System Attributes

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- LightGBM
- XGBoost
- Joblib
- Streamlit

---

## Data Preprocessing

The following preprocessing steps were performed:

- Missing value treatment
- Data type conversion
- Date handling
- Outlier treatment
- Feature scaling
- Categorical encoding

---

## Feature Engineering

Created additional features including:

- Year
- Month
- Quarter
- Time-based installation trends
- Solar system performance indicators

Target transformation techniques were also applied to improve model stability and prediction accuracy.

---

## Exploratory Data Analysis (EDA)

Performed:

- Distribution Analysis
- Missing Value Analysis
- Feature Correlation Analysis
- Solar Production Trends
- Temporal Analysis
- Outlier Detection

---

## Machine Learning Models

### Random Forest Regressor

Baseline regression model.

### XGBoost Regressor

Boosting model for improved predictive performance.

### LightGBM Regressor

High-performance gradient boosting framework used for accurate energy prediction.

---

## Hyperparameter Tuning

RandomizedSearchCV was used to optimize model performance and identify the best parameter combinations.

---

## Model Evaluation

Evaluation Metrics:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

The final model was selected based on holdout dataset performance.

---

## Feature Importance Analysis

Permutation importance was used to identify the most influential variables affecting solar energy production.

Key factors included:

- PV System Size
- Installation Date
- Storage Capacity
- System Characteristics

---



## Streamlit Deployment

A Streamlit application was created to allow users to predict annual solar energy production through an interactive web interface.

Run locally:

```bash
streamlit run app.py
```

---

## Business Impact

This project demonstrates how machine learning can support:

- Renewable energy forecasting
- Solar investment planning
- Utility management
- Sustainable energy initiatives
- Infrastructure optimization

---

## Future Improvements

- Deep Learning Models
- Real-Time Solar Forecasting
- Weather Data Integration
- Cloud Deployment
- API Development

---

## Project Structure

```text
solar-energy-production-prediction/
│
├── data/
│   └── Solar Energy.xlsx
│
├── notebook/
│   └── Solar project.ipynb
│
├── presentation/
│   └── Predicting Annual Solar Energy Production.pptx
│
├── models/
│   └── solar_model.joblib
│
├── app/
│   └── app.py
│
├── images/
│   ├── solar_distribution.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   ├── feature_importance.png
│   └── model_rmse.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Author

### Suyash Patil

Aspiring Data Scientist | Data Analyst | Machine Learning Engineer
