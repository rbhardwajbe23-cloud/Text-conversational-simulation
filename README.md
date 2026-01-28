# Text-conversational-simulation# Text-Based Conversational Simulator (ML Evaluation)

This project implements a **text-based conversational simulator** to study how conversational parameters affect overall conversation quality.  
Synthetic conversations are generated using rule-based simulation, and multiple machine learning models are evaluated.

---

## 🔧 Simulation Overview
The simulator models user–bot interactions using linguistic, behavioral, and system-level parameters such as sentiment, message length, response relevance, and context retention.

- Total simulated conversations: **1000**
- Output variable: **Conversation Quality Score (0–100)**

---

## 🤖 Machine Learning Models
The following regression models were evaluated:

- Linear Regression
- Ridge & Lasso Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- KNN
- SVR
- MLP
- Extra Trees

---

## 📊 Results & Graphs

### 🔹 Model Performance (R² Score)
<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/ffa3cd05-e4ad-4766-9f21-33fe6a418b82" />

### 🔹 Model Performance (MSE)
<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/6fd49b84-1eeb-43c4-82b5-f5d4693d867e" />

### 🔹 Feature Importance
<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/7880f7d3-0fe4-429e-b7b2-436828eaad5e" />

### 🔹 Actual vs Predicted Quality Score
<img width="629" height="470" alt="image" src="https://github.com/user-attachments/assets/0c564a40-1aa1-4ec9-a21b-1eca9256e2d1" />

---

## 🏆 Conclusion
Linear regression achieved the best performance due to the predominantly linear nature of the simulated data, while ensemble methods such as Gradient Boosting also performed strongly under noisy conditions.

---

## 👨‍🎓 Author
**Rishi Bhardwaj**

---

## 📄 License
Academic and educational use only.
