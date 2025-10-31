# 🕒 Time Series Forecasting — Local Kaggle Replication

This project recreates and extends concepts from Kaggle’s *Forecasting with Machine Learning* course entirely **offline**.  
It demonstrates how to reproduce Kaggle’s hidden helper utilities, visualize time-series patterns, and build reusable analysis code.

---

## 🎯 Project Goals

- Reproduce Kaggle’s `plot_lags` and `lagplot` functions from scratch.  
- Implement smooth (LOWESS) trend lines and autocorrelation annotations.  
- Explore deseasonalization, detrending, and lag relationships in sales data.  
- Organize the workflow into a modular, reproducible structure.  

---

## 🧠 What I Learned

- Practical understanding of **time-series autocorrelation** and **feature engineering**.  
- Writing custom visualization utilities with `matplotlib` and `seaborn`.  
- Managing environments, dependencies, and large datasets locally.  
- Using **Git and GitHub** for version control and reproducible research.  

---

## 🧰 Tools & Libraries

| Category | Tools |
|-----------|-------|
| Core | Python 3.x, JupyterLab |
| Data | pandas, NumPy |
| Visualization | matplotlib, seaborn |
| Modeling | scikit-learn |
| Version Control | Git, GitHub |

---

## ⚙️ Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/RahbariAhmadreza/kaggle-time-series-local.git
   cd kaggle-time-series-local

2. **(Optional) Create a virtual environment**
python -m venv .venv
.venv\Scripts\activate       # Windows
source .venv/bin/activate    # macOS/Linux

3. ** Install dependensies**
pip install -r requirements.txt

4. **Launch JupyterLab**