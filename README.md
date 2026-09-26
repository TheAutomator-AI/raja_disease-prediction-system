# 🩺 Raja Health Prediction System

An ML-powered web application for health-risk prediction, combining a Flask API with a browser-based dashboard.

> **Project note:** This repository currently contains the multi-disease prediction implementation described below. Model outputs are for software demonstration / educational purposes and are not medical diagnoses.

## ✨ Features

- ❤️ Heart disease prediction
- 🩸 Diabetes prediction
- 🎗️ Breast cancer prediction
- 🤖 Automatic model comparison
- 📊 Analytics and model metrics
- 📄 Downloadable reports
- 🕘 Local prediction history
- 🌐 Flask REST API
- 💻 React-based frontend

## 🧠 ML workflow

Input → preprocessing → candidate models → evaluation → selected model → prediction → explanation

The project explores Logistic Regression, Random Forest, SVM, XGBoost and related evaluation workflows.

## 🗂️ Repository structure

- `backend/` — Flask API + model training
- `frontend/` — Web application
- `datasets/` — Training datasets
- `models/` — Generated model artifacts
- `render.yaml` — Render deployment configuration

## 🌐 Deployment

Live demo:
https://theautomator-ai.github.io/raja_disease-prediction-system/

## ⚠️ Disclaimer

This is an educational software project. Predictions should not be used as medical advice or as a substitute for a qualified healthcare professional.

## 📌 Status

**Prototype / portfolio project**
