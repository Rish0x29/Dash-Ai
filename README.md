 🧠 Dash-AI

**Upload any dataset, train a classifier, and understand WHY it makes predictions — powered by SHAP.**

Dash-AI is a high-performance, local-first machine learning diagnostic tool. It strips away the "black box" nature of ML models by providing real-time, interactive feature importance and per-prediction explanations using SHapley Additive exPlanations.

---

## ✨ Features

- **📁 Smart Data Ingestion:** Upload any CSV. Auto-handles mixed types, missing values, and categorical encoding.
- **🤖 Quad-Model Engine:** Choose between Random Forest, Gradient Boosting, Logistic Regression, and Decision Trees.
- **🔍 XAI Suite (SHAP):** - **Global Importance:** See which features drive the model overall.
    - **Local Explanations:** Pick a specific row and see exactly which values pushed the prediction up or down.
    - **Beeswarm & Waterfall Plots:** High-fidelity visualizations of feature impact.
- **🎯 Interactive "What-If" Analysis:** (Planned) Tweak feature values on the fly to see how the model's "mind" changes.
- **📊 Performance Audit:** Instant confusion matrices, precision/recall curves, and classification reports.
- **🚫 100% Privacy:** No API keys, no cloud uploads. Everything stays on your machine.

---

## 🛠 Tech Stack

- **UI Framework:** Streamlit / Plotly
- **ML Core:** Scikit-Learn
- **Explainability:** SHAP (SHapley Additive exPlanations)
- **Processing:** Pandas / NumPy

---

## 🧠 How It Works

1. **Ingest:** Smart CSV parsing with automated label encoding.
2. **Train:** Local execution of Scikit-Learn ensembles.
3. **Audit:** SHAP decomposes the "black box" into human-readable contributions.
4. **Interact:** Analyze individual samples to find bias or validate logic.

### SHAP Explained Simply
SHAP answers: *"How much did each feature contribute to this specific outcome compared to the average?"*

- **🔴 Positive SHAP:** Feature value increased the probability of the target class.
- **🔵 Negative SHAP:** Feature value decreased the probability of the target class.

---

## 🚀 Getting Started

### Installation
```bash
# Clone the repository
git clone [https://github.com/Rish0x29/Dash-AI.git](https://github.com/Rish0x29/Dash-AI.git)

# Install dependencies
pip install -r requirements.txt

# Launch the dashboard
streamlit run app.py
