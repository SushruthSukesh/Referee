# 🧑‍⚖️ ML Model Referee

A referee-style decision support tool that compares machine learning models and explains trade-offs instead of providing a single recommendation.

---

## 📌 Problem Statement

Choosing the right machine learning model is rarely straightforward.  
Accuracy, interpretability, training time, scalability, and deployment constraints often conflict. Most tools and tutorials recommend a single “best” model without explaining the trade-offs involved.

This makes it difficult for practitioners to make informed decisions based on their real-world constraints.

---

## 💡 Solution

**ML Model Referee** is designed as a neutral decision-support system.

Instead of answering *“Which model should I use?”*, it helps users:
- Compare multiple ML models side-by-side
- Understand trade-offs clearly
- Choose a model based on their priorities

There is **no universally best model** — only context-dependent choices.

---

## 🧠 Models Compared

- Logistic Regression  
- Random Forest  
- XGBoost  

Each model is evaluated across:
- Accuracy potential  
- Interpretability  
- Training time  
- Inference latency  
- Scalability  
- Overfitting risk  

---

## 🔧 User Inputs (Constraints)

Users define:
- Dataset size  
- Interpretability requirement  
- Accuracy priority  

The tool adapts its guidance based on which constraints matter most.

---

## 📊 Output

The application provides:
- A **Kiro-generated comparison table**
- Clearly explained **trade-offs**
- **Conditional guidance** (not absolute recommendations)

Example:
- If interpretability is the priority → trade-offs favor simpler models
- If accuracy is the priority → trade-offs favor ensemble methods

---

## ⚙️ Tech Stack

- Python  
- Streamlit  
- Kiro (local) for structured reasoning and trade-off generation  

---



