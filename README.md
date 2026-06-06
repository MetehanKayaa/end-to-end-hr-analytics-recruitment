# End-to-End HR Performance and Recruitment Prediction System

This repository contains a production-ready, end-to-end Data Science and Web Engineering project designed to optimize Human Resources workflows. The application seamlessly integrates dynamic Exploratory Data Analysis (EDA) dashboards with a predictive recruitment engine powered by Machine Learning pipelines.

## 🚀 Key Features

- **Dynamic EDA Dashboard:** Comprehensive analytics panel visualizing employee satisfaction levels, retention rates, department metrics, and salary distribution structures utilizing backend Seaborn/Matplotlib automation.
- **Predictive Recruitment Engine:** A custom-trained Machine Learning classification pipeline designed to process candidate background metrics (academic history, test percentages, work experience) to predict placement outcomes.
- **Enterprise UI/UX Experience:** Fully modular frontend layout designed with **Bootstrap 5** and **Bootstrap Icons**, featuring a polished, modern web navigation structure and a corporate video-based background implementation.

## 📊 Project Architecture & Datasets

The system works natively with a structured dual-dataset environment:
1. **Internal HR Retention Data:** Maps employee operational behavior, tracking evaluation scores, workspace accidents, promotions, and turnover correlation matrixes.
2. **External Corporate Recruitment Data:** Evaluates candidate profiles through cross-verified statistical benchmarks to calculate job placement probabilities.

## 📁 Repository Structure

```text
├── models/
│   ├── model.pkl            # Trained Machine Learning classification model
│   └── scaler.pkl           # Feature scaler pipeline
├── static/
│   ├── video.mp4            # Cinematic background assets
│   └── *.png                # Dynamically generated analytics plots
├── templates/
│   ├── index.html           # Main landing hero section
│   ├── job.html             # Candidate recruitment prediction form
│   └── ana.html             # Core analytical metrics dashboard
├── app.py                   # Main Flask application controller
├── main.ipynb               # EDA & Visualization development notebook
└── main2.ipynb              # Model training & serialization pipeline
