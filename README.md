# 🎧 Spotify Churn Prediction Dashboard

This project is an AI-powered churn prediction system for Spotify users, combining Python for data processing and machine learning, and Power BI for interactive data visualization. The system identifies potential churners, analyzes user behavior, compares model performance, and assists in making data-driven decisions to improve user retention.

---

## 🚀 Features

- ✅ Cleaned and preprocessed user data (handling nulls, encoding, etc.)
- 🌲 Trained **Random Forest** and **XGBoost** models
- 📈 Generated churn predictions and probabilities for all users
- 🧠 Compared model performance and visualized churn risk
- 📊 Built an interactive Power BI dashboard:
  - Demographics and behavior analysis
  - Churn breakdown by model
  - Churn probability scatter plot
  - High-risk users table
  - Model disagreement visualization
  - KPIs for accuracy and churn rate

---

## 🧠 Machine Learning Models

- **Random Forest Classifier**  
- **XGBoost Classifier** (with hyperparameter tuning and `scale_pos_weight` for imbalance)

Each model was trained on 80% of the cleaned dataset and used to predict on all 520 users.

---

## 📁 File Structure

📦Spotify-Churn-Prediction/
┣ 📊 PowerBI_Dashboard.pbx
┣ 📄 Spotify_data.csv
┣ 📄 full_churn_predictions_rf.csv
┣ 📄 full_churn_predictions_xgb.csv
┣ 📄 full_churn_predictions_combined.csv
┣ 🧠 churn_prediction_model.py
┣ 📄 README.md

---

## 🛠️ Requirements

- Python 3.10+
- Libraries:
  - `pandas`
  - `scikit-learn`
  - `xgboost`
  - `matplotlib` (for feature importance)

---

📊 Power BI Highlights
Page 1: User behavior analysis (genre, gender, plan preferences)

Page 2: Model-based insights (churn predictions, scatter comparison, high-risk users, KPIs)

Disagreement markers help identify model uncertainty for deep insights.

👤 Author
Karan Jogi – AI/ML Developer
