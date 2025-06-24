# 📱 App Rating Predictor using UI/UX Features

Predict mobile app ratings from Google Play Store data using machine learning — built by a passionate UI/UX designer diving into data science and ML 💡.

---

## 📊 Overview

This project uses real-world Google Play Store data to train a regression model that predicts app ratings based on features like:

- Installs
- Reviews
- Size
- Price
- Category, Content Rating, Type (one-hot encoded)

Aimed to bridge design insight and data-driven decisions for better app success.

---

## 🧠 Machine Learning Stack

| Task                    | Tool / Library         |
|-------------------------|------------------------|
| Data Processing         | `pandas`, `numpy`      |
| Modeling                | `XGBoost`, `sklearn`   |
| Model Evaluation        | RMSE, R² Score         |
| Model Saving            | `joblib`               |
| Visualization (optional)| `matplotlib`, `seaborn`|

---

## 🧪 Model Performance

| Metric | Value | What It Means |
|--------|-------|----------------|
| **RMSE**   | `0.4766` | Average prediction error is ~0.48 stars |
| **R² Score** | `0.1366` | Model explains 13.66% variance in ratings |

> ✅ Good baseline — further tuning and feature engineering can improve this.

---

## 🔁 Workflow Summary

1. **Clean & preprocess data**: Remove invalid rows, encode categories.
2. **Train/test split**: 80/20 split using `train_test_split`.
3. **Train model**: `XGBRegressor` with 3-fold cross-validation.
4. **Evaluate**: RMSE, R².
5. **Export**: Save model with `joblib` for future prediction.

---

## 💾 Saved Model

The trained model is saved as:

`model_export/uiux_rating_predictor.pkl`

## 🔧 Requirements
Install the dependencies using:

`pip install -r requirements.txt`

## 🚀 Try It Yourself
You can run this notebook on Kaggle or locally.

**✨ Designed & Built By
Selya1722-Amaya Jayasekara
UI/UX Designer · ML Enthusiast**
