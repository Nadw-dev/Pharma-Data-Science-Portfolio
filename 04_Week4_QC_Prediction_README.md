Week 4 – Predictive QC Intelligence (Decision Tree Model)

This project builds on my pharmaceutical QC analytics by introducing predictive modeling.
I trained a decision tree model to predict whether a batch will Pass or Fail, using:

Assay %

Moisture %

Yield %

What I Did

Created a labeled Pass vs Fail dataset

Split data into train/test sets

Trained a decision tree model

Evaluated accuracy, precision, recall, and F1-score

Added cross-validation for scientific reliability

Visualized model decisions and feature importance

Explainable AI (GMP-aligned)

I examined model rules and feature importance to keep the AI transparent and traceable — aligning with GMP and quality expectations.

Expanded Realism

I added additional “High Risk” batches with normal assay but poor moisture/yield. After retraining, the model began using Moisture and Yield more, reflecting realistic multi-factor risk behavior.

Skills Gained

Python • Pandas • Scikit-Learn
QC Analytics → Predictive Analytics
Model Evaluation • Explainable AI
Pharma CMC / GMP Reasoning
