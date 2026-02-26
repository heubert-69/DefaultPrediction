📉 Stock Pledge Financing Default Prediction (2026)
🔍 Overview

This project develops predictive and explainable machine learning models to identify early warning signals of default in stock pledge financing.

Equity pledges by controlling shareholders are widely used for capital raising but introduce systemic financial risk. This work builds a robust, interpretable, and stress-tested modeling framework to predict default events (IsDefault) using financial indicators from 2017–2022.

🎯 Objectives

Predict stock pledge financing defaults

Identify key financial risk drivers

Test model robustness under stress scenarios

Perform statistical comparison between models

Conduct causal inference analysis

Ensure interpretability using SHAP

📊 Dataset Features

Key financial indicators include:

Z-SCORE

Share pledge ratio of controlling shareholders

Stock Volatility

P/E ratio

P/B ratio

Stock price rise and fall (last year)

Annual turnover rate

Equity concentration

Institutional shareholding ratio

Financial cycle (M2/GDP)

And more...

Target variable:

IsDefault (Binary Classification)

🤖 Models Implemented

Logistic Regression

Random Forest Classifier

Gradient Boosting Classifier

XGBoost

LightGBM

CatBoost

Voting Ensemble (Soft Voting)

🧠 Advanced Evaluation
✅ Statistical Testing

McNemar’s Test

Wilcoxon Signed-Rank Test

Cliff’s Delta

Bootstrapped Confidence Intervals

Cross-validated performance comparison

DeLong’s test for ROC comparison

🔬 Stress Testing

Feature perturbation analysis

Adversarial scenario testing

Impossibility testing

🔎 Interpretability

SHAP global feature importance

SHAP force plots (local explanations)

Feature ablation analysis

🧩 Causal Inference

DoWhy causal effect estimation

Placebo refutation tests

Heterogeneous treatment effects (EconML)

📈 A/B Testing Framework

Simulated financial interventions:

Reduced stock volatility

Adjusted pledge ratios

Market downturn scenarios

Statistical significance tested via:

T-tests

Bootstrapped confidence intervals


🚀 Key Results

High classification accuracy across models

Robust ensemble performance

Stable predictions under stress conditions

Significant statistical differences between linear and tree-based models

Financial risk drivers validated via SHAP and causal inference

🛠 Tech Stack

Python

Scikit-learn

XGBoost

LightGBM

CatBoost

SHAP

DoWhy

EconML

MLflow

Matplotlib / Seaborn


📚 Research Context

This project integrates:

Predictive modeling

Statistical hypothesis testing

Financial stress testing

Causal inference

Model interpretability

It is designed to be both competition-ready and research-paper-ready.
