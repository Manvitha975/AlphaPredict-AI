# 📈 AlphaPredict AI
### End-to-End MLOps Pipeline for Stock Market Movement Prediction

Predicting next-day stock price movement using an automated MLOps workflow built with Python, Airflow, MLflow, Supabase, and XGBoost.

---

## 🚀 Overview

AlphaPredict AI is a production-oriented MLOps project that automates the complete machine learning lifecycle for stock market prediction.

The pipeline:

- Collects historical stock data
- Cleans and validates financial records
- Stores data in Supabase
- Performs feature engineering
- Trains multiple ML models
- Tracks experiments with MLflow
- Automatically selects the best model
- Stores trained models in cloud storage
- Supports future deployment for real-time predictions

---

## ✨ Features

- Automated ETL Pipeline
- Airflow Scheduling
- Time-Series Feature Engineering
- Exploratory Data Analysis
- MLflow Experiment Tracking
- Hyperparameter Optimization
- Multiple Machine Learning Models
- Cloud Storage Integration
- Model Versioning
- Production-ready Project Structure

---

## 🏗 Architecture

```
Yahoo Finance
      │
      ▼
 ETL Pipeline
      │
      ▼
 Supabase Database
      │
      ▼
Feature Engineering
      │
      ▼
EDA + Visualization
      │
      ▼
Model Training
(Logistic Regression
Random Forest
XGBoost)
      │
      ▼
MLflow Tracking
      │
      ▼
Best Model Selection
      │
      ▼
Supabase Storage
```

---

# 📂 Project Structure

```
AlphaPredict-AI
│
├── ETL
│   ├── pulldata.py
│   ├── transform.py
│   ├── load.py
│   └── pipeline.py
│
├── ML
│   ├── dataFetch.py
│   ├── features.py
│   ├── eda.py
│   ├── train.py
│   ├── predict.py
│   └── run_training.py
│
├── dags
│   └── StockEtlDag.py
│
├── models
│
├── mlruns
│
├── main.py
├── runml.py
├── uploadModel.py
├── requirements.txt
└── README.md
```

---

# ⚙ Tech Stack

### Languages

- Python

### Machine Learning

- Scikit-learn
- XGBoost
- MLflow

### Data Processing

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Database

- Supabase

### Data Source

- Yahoo Finance (yfinance)

### Workflow Automation

- Apache Airflow

---

# 📊 Machine Learning Pipeline

### Data Collection

- Historical OHLCV data
- Multiple stock symbols
- Automated ingestion

### Feature Engineering

- Lag Features
- Moving Averages
- Rolling Volatility
- Volume Indicators
- Daily Returns
- Price Range
- VWAP Approximation

### Models

- Logistic Regression
- Random Forest
- XGBoost

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

# 📈 MLOps Features

✅ Automated ETL

✅ Airflow Scheduling

✅ MLflow Experiment Tracking

✅ Hyperparameter Optimization

✅ Model Versioning

✅ Cloud Model Storage

✅ Reproducible Pipelines

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/yourusername/AlphaPredict-AI.git

cd AlphaPredict-AI
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Configure Environment

Create a `.env` file

```env
SUPABASE_URL=YOUR_URL

SUPABASE_KEY=YOUR_KEY
```

---

# ▶ Run ETL

```bash
python main.py
```

---

# ▶ Train Models

```bash
python runml.py
```

---

# ▶ Launch MLflow

```bash
mlflow ui --backend-store-uri sqlite:///mlflow.db
```

---

# 📊 Workflow

```
Collect Data
      ↓
Validate Data
      ↓
Store in Supabase
      ↓
Generate Features
      ↓
EDA
      ↓
Train Models
      ↓
Hyperparameter Search
      ↓
MLflow Tracking
      ↓
Best Model Selection
      ↓
Upload Model
```

---

# 🎯 Future Improvements

- LSTM Models
- Transformer-based Time Series
- Live Stock Streaming
- FastAPI Prediction API
- Docker Deployment
- Kubernetes
- CI/CD Pipeline
- Real-time Dashboard

---

# 🏆 Highlights

- Production-grade MLOps architecture
- Automated data pipeline
- Experiment tracking with MLflow
- Cloud-based model versioning
- Time-series machine learning workflow
- Designed for scalable stock prediction systems

---

## 👩‍💻 Author

**Manvitha Ankam**

AI • Machine Learning • MLOps • Data Science
