Overview

This project addresses the growing mental health challenges within the tech industry, where factors like high workloads, job insecurity, and workplace isolation contribute to increasing depression rates. Despite growing awareness, many individuals hesitate to seek treatment.
To tackle this, a two-stage ML and DL framework is proposed for detecting depression and identifying individuals at high risk of not seeking treatment.

Dataset

Source: Mental Health in Tech Survey (Open Dataset)
Samples: 1258 responses from individuals in the tech industry
Features Used: 18 key attributes related to workplace environment, mental health, and treatment history

Methodology

Rule-Based Scoring:
Each feature was assigned a depression score.
Individuals scoring above a threshold were labeled as likely_depressed.

Risk Classification:
Based on treatment status, individuals were classified as:
🟥 High Risk – Likely depressed, not receiving treatment
🟨 Treated – Likely depressed, receiving treatment
🟩 Low/No Risk – Not depressed

Models Used:
Machine Learning: Logistic Regression, XGBoost, SVM, Random Forest, Decision Tree, KNN
Deep Learning: MLP, LSTM, CNN

Evaluation Metrics: Accuracy, Precision, Recall, and F1-Score
Deep Learning models (LSTM, MLP) outperformed ML models, proving more effective for early detection and multi-class risk classification.

Conclusion
The study demonstrates the potential of integrating Machine Learning and Deep Learning for early detection and risk assessment of depression.
Such approaches can enhance timely intervention and improve workplace mental health awareness.
