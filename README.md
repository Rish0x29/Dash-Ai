# Dash-Ai
Upload any dataset, train a classifier, and understand WHY it makes predictions — powered by SHAP.

✨ Features


📁 CSV Upload	Upload any CSV dataset — auto-handles mixed types, encodes categoricals
🌸 Demo Mode	Instant start with Iris dataset — no upload needed
🤖 4 Models	Random Forest, Gradient Boosting, Logistic Regression, Decision Tree
🔍 SHAP Values	Global feature importance + per-prediction waterfall explanations
📊 Metrics	Accuracy, confusion matrix, classification report in one view
📈 Feature Viz	Distribution plots per feature and per class
🎯 Single Explain	Pick any test sample and see exactly why the model predicted what it did
🚫 No API keys	100% local — no OpenAI, no cloud required


🧠 How It Works
Your CSV → Preprocessing → Train/Test Split → ML Model → SHAP Explainer → Interactive Plots
Upload a CSV (or use the Iris demo)
Select target column and model
Click "Train & Explain"
Explore global SHAP importance, beeswarm plots, and per-sample explanations
SHAP Explained Simply
SHAP (SHapley Additive exPlanations) answers: "How much did each feature push this prediction up or down?"

🔴 Positive SHAP = pushed prediction toward this class
🟢 Negative SHAP = pushed prediction away from this class

MIT License — free to use, modify, and share.
