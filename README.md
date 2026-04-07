# Cancer Risk Prediction

## Project Overview
This project builds a machine learning system to predict an individual's cancer risk level as Low, Medium, or High using demographic, lifestyle, environmental, and medical-related features.

The goal is not only to achieve strong overall model performance, but also to handle class imbalance carefully so that high-risk individuals are identified as reliably as possible.

## Business Problem
Early identification of high-risk individuals can support better screening strategies, earlier interventions, and more informed healthcare planning.

This project explores how machine learning can be used for risk stratification in a healthcare context, while paying attention to practical modeling issues such as data leakage, class imbalance, model comparison, and deployment readiness.

## Objectives
- Explore and understand the dataset through EDA
- Build a clean preprocessing pipeline
- Compare multiple machine learning models
- Handle class imbalance using appropriate techniques
- Evaluate performance beyond accuracy
- Deploy the final model using Streamlit or FastAPI

## Project Structure
```text
cancer-risk-prediction/
├── app/
├── data/
├── docs/
├── models/
├── notebooks/
├── reports/
├── src/
├── tests/
├── README.md
├── requirements.txt
└── main.py