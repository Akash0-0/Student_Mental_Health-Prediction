# Student_Mental_Health-Prediction

# 🧠 Student Mental Health Predictor

This project uses machine learning (XGBoost) to predict students' self-rated mental health scores based on their social media usage patterns, academic data, sleep habits, and more.

---

## 📁 Dataset

The dataset includes the following features:

- `Student_ID`: Unique identifier
- `Age`: Student's age
- `Gender`: Male/Female
- `Academic_Level`: High School, Undergraduate, Graduate
- `Country`: Country of residence
- `Avg_Daily_Usage_Hours`: Daily social media usage in hours
- `Most_Used_Platform`: Instagram, TikTok, etc.
- `Affects_Academic_Performance`: Yes/No
- `Sleep_Hours_Per_Night`: Average sleep per night
- `Mental_Health_Score`: Target variable (1–10)
- `Relationship_Status`: Single/In Relationship/Complicated
- `Conflicts_Over_Social_Media`: Number of conflicts due to social media
- `Addicted_Score`: Social media addiction score (1–10)

---

## 🚀 Features

- Preprocessing (Label Encoding, Train/Test Split)
- XGBoost Regressor for predicting `Mental_Health_Score`
- Model evaluation with RMSE and R² Score
- Visualization of XGBoost decision trees (like MATLAB-style plots)
- Model saved as `.pkl` for later use

---

## 🧪 Model Performance

| Metric | Value |
|--------|-------|
| **RMSE** | ~0.24 |
| **R² Score** | ~0.95 |

✅ Very accurate — 95% of mental health score variation is explained by the model.

---

## 📦 How to Run

1. Clone the repository
2. Install dependencies:

```bash
pip install xgboost pandas scikit-learn matplotlib joblib
Run the Jupyter Notebook or script

The model will train and save as xgboost_mental_health_model.pkl

🖼️ Tree Visualization
XGBoost trees are visualized using xgboost.plot_tree() for interpretability and debugging.

📁 Output
xgboost_mental_health_model.pkl: Trained model file

Tree plots: Rendered inline via Matplotlib

💡 Future Work
Add frontend (Streamlit or Flask)

Deploy as API

Extend to classification (e.g., "At Risk"/"Healthy")
```
🧑‍💻 Author
Developed by Aakash pal
E-mail : palaakaah148@gmail.com
