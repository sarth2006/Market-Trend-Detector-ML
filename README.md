# 📈 Market Trend Detector

Market Trend Detector is a machine learning-based system designed to
identify bullish and bearish stock patterns using historical time-series
data.

This project combines time-series transformation techniques, algorithmic
optimizations, and supervised learning to generate short-term market
trend signals.

------------------------------------------------------------------------

## 📌 Project Overview

Financial market data is sequential and must be transformed into a
supervised learning format before training ML models.

This project:

-   Converts stock price data into fixed-length sliding windows
-   Uses prefix sum optimization for efficient rolling feature
    computation
-   Applies hash maps for fast pattern matching
-   Trains a Random Forest classifier to detect bullish and bearish
    trends
-   Visualizes detected patterns using Matplotlib

------------------------------------------------------------------------

## 🧠 Methodology

### 1️⃣ Data Processing

Historical stock price data is processed using Pandas and NumPy.

### 2️⃣ Sliding Window Transformation

Time-series data is converted into fixed-size windows to create
structured input features for supervised learning.

### 3️⃣ Prefix Sum Optimization

Prefix sums are used to efficiently compute rolling metrics and reduce
redundant calculations.

### 4️⃣ Model Training

A Random Forest classifier (Scikit-learn) is trained on engineered
features to classify trend direction.

### 5️⃣ Visualization

Market patterns and prediction outputs are visualized using Matplotlib
for interpretation.

------------------------------------------------------------------------

## 🛠 Tech Stack

-   Python\
-   Pandas\
-   NumPy\
-   Scikit-learn\
-   Matplotlib

------------------------------------------------------------------------

## 📂 Project Structure

    Market_Trend_Detector/
    │
    ├── notebooks/
    │   └── trend_detection.ipynb
    │
    ├── src/
    │   ├── data_processing.py
    │   ├── feature_engineering.py
    │   ├── model_training.py
    │   └── utils.py
    │
    ├── requirements.txt
    ├── README.md
    └── .gitignore

------------------------------------------------------------------------

## ▶ How to Run

1.  Install dependencies:

``` bash
pip install -r requirements.txt
```

2.  Run the notebook:

``` bash
jupyter notebook
```

------------------------------------------------------------------------

## 🎯 Project Objective

-   Apply algorithmic optimization techniques to financial time-series
    data\
-   Build a supervised ML pipeline for trend classification\
-   Generate interpretable short-term trading signals

------------------------------------------------------------------------

## 📎 Notes

-   This project focuses on historical data analysis (no live trading
    integration).
-   The system is designed for educational and experimentation purposes.
-   No deployment or automated trading execution is implemented.

------------------------------------------------------------------------

## 👤 Author

Sarth Kaushik\
IIT Delhi
