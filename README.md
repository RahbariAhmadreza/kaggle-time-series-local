# 🕒 Time Series Forecasting — Local Kaggle Replication

This project recreates and extends concepts from Kaggle’s *Forecasting with Machine Learning* course entirely **offline**.  
It reproduces Kaggle’s helper utilities, visualizes time-series behavior, and builds modular, reusable analysis code.

---

## 🎯 Project Goals

- Recreate Kaggle’s `plot_lags` and `lagplot` functions from scratch  
- Implement smooth (LOWESS) trend lines and autocorrelation annotations  
- Explore deseasonalization, detrending, and lag relationships in sales data  
- Organize the workflow into a modular, reproducible structure  

---

## 🧠 What I Learned

- Practical understanding of **time-series autocorrelation** and **feature engineering**  
- Writing reusable visualization utilities with `matplotlib` and `seaborn`  
- Managing environments, dependencies, and large datasets locally  
- Using **Git + GitHub** for version control and reproducible research  

---

## 🧰 Tools & Libraries

| Category | Tools |
|-----------|-------|
| Core | Python 3.11, JupyterLab |
| Data | pandas, NumPy |
| Visualization | matplotlib, seaborn |
| Modeling | scikit-learn, statsmodels, xgboost |
| Management | Git, Conda, pip |

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/RahbariAhmadreza/kaggle-time-series-local.git
cd kaggle-time-series-local
```

### 2️⃣ (Option A) Quick setup with pip
For general use or development:
```bash
pip install -r requirements.txt
```

### 3️⃣ (Option B) Reproducible setup with Conda
For an exact environment with pinned versions:
```bash
conda env create -f environment.yml
conda activate kaggle-time-series
```

### 4️⃣ Launch JupyterLab
```bash
jupyter lab
```

---

## 🔁 Environment Management

- **Update dependencies**  
  ```bash
  pip freeze > requirements.txt
  conda env export --from-history > environment.yml
  ```

- **Recreate on another machine**  
  ```bash
  conda env create -f environment.yml
  ```

- **Update existing environment**  
  ```bash
  conda env update -f environment.yml --prune
  ```

---

## 🧱 Project Structure

```
kaggle-time-series-local/
│
├── notebooks/         # Jupyter notebooks for each lesson
├── src/               # Local helper modules (utils.py, plotting.py)
├── requirements.txt   # General package list
├── environment.yml    # Reproducible Conda environment
└── README.md
```

---

## 📘 Notes
- `requirements.txt` provides a flexible, lightweight dependency list.  
- `environment.yml` ensures **exact reproducibility** across systems.  
- Tested with **Python 3.11** and the versions listed in `environment.yml`.

---
