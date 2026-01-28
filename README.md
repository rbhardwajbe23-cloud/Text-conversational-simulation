# Text-Based Conversational Simulator (ML Evaluation)

## Overview
This project implements a **text-based conversational simulator** to analyze how conversational parameters influence overall conversation quality.  
Synthetic data is generated using a rule-based simulation and evaluated using multiple machine learning regression models.


## Methodology
A conversational simulator was designed to model user–bot interactions using quantitative features such as sentiment, message length, politeness, response relevance, and context retention.

Each conversation is assigned a **Conversation Quality Score (0–100)** computed using a weighted combination of parameters with added noise to simulate real-world variability.

- Total simulations: **1000**
- Dataset: `conversation_simulation.csv`
- Train/Test split: **80/20**



## Machine Learning Models
The following regression models were evaluated:

- Linear, Ridge, Lasso  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- KNN  
- SVR  
- MLP  
- Extra Trees  

**Evaluation metrics:** Mean Squared Error (MSE) and R² Score.



## Results

### Model Performance (R² Score)
<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/ff840c58-83bc-4f23-8e20-09adb69ecd28" />

### Model Performance (MSE)
<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/39704164-3042-4834-9a4c-a07773b41dfd" />

### Feature Importance
<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/1bb2f68a-0c8e-4894-bdf4-b62d6ecec538" />

### Actual vs Predicted Quality
<img width="629" height="470" alt="image" src="https://github.com/user-attachments/assets/f8c0d41b-d21a-4eec-b08d-60980fe8e2af" />


## Key Observations
- Linear Regression achieved the best performance due to the predominantly linear nature of the simulated system.
- Ensemble models (Gradient Boosting, Random Forest) performed robustly under noise.
- Response relevance, sentiment, and context retention were the most influential parameters.



## Conclusion
The results demonstrate that simulation-based conversational modeling is effective for studying dialogue quality and comparing ML models without requiring real user data.


