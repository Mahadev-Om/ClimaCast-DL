
---

**ClimaCast DL – Multivariate Climate Forecasting**

```markdown
ClimaCast DL

Advanced deep learning models (LSTM, CNN, DNN) applied to multivariate climate forecasting using the Jena dataset (400K+ entries).

Overview

This project demonstrates the power of deep learning for time-series forecasting in climate science. LSTM achieved the lowest MAE, capturing long-range temporal patterns effectively.

Tools & Techniques

TensorFlow, Keras, Pandas, NumPy, Matplotlib
Temporal windowing and sequence preprocessing
MAE, RMSE evaluations

Models Compared

LSTM (Best performance)
CNN
Dense Neural Network

Key Takeaways

LSTM handles long-term dependencies in environmental data.
Temporal structure is critical in accurate forecasting.
Preprocessing directly impacts model robustness.

Structure

`data/` — Raw & processed datasets  
`models/` — Model architecture and training scripts  
`notebooks/` — Exploratory data analysis and results

Status

 Final model ready for deployment  
 Visualized prediction windows for interpretability  
