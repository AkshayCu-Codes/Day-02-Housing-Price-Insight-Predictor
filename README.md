# Day 02 — Housing Price Insight Predictor

Multi-feature linear regression using the **California Housing Dataset** to predict median house values.  
This project demonstrates a practical regression workflow with feature scaling, model training, evaluation, and feature impact analysis.

---

## 📦 Dataset
- **Source:** `fetch_california_housing()` from Scikit-Learn
- **Records:** ~20,000
- **Target:** Median House Value (`MedHouseVal`)
- **Input Features:** Income levels, house age, rooms, population, latitude/longitude, etc.
- **Download Requirement:** None (built-in to sklearn)

---

## 🎯 Objectives
- Load a real-world housing dataset
- Explore correlations & influential features
- Train a multi-input Linear Regression model
- Evaluate using MSE, RMSE, MAE, and R²
- Visualize Actual vs Predicted values
- Identify strongest contributing features

---

## 📁 Project Structure
```text
Day-02-Housing-Price-Insight-Predictor/
├─ data/                     # optional if saving splits
├─ models/
│  └─ housing_regressor.pkl  # saved trained model
├─ notebooks/
│  └─ main.ipynb             # full workflow
└─ README.md
```

---

## 🧰 Tech Stack
| Component | Tool |
|-----------|------|
| Language | Python |
| Notebook | Jupyter |
| Data | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Modeling | Scikit-Learn (LinearRegression) |

---

## ⚙️ How to Run the Project
```bash
git clone https://github.com/USERNAME/Day-02-Housing-Price-Insight-Predictor.git
cd Day-02-Housing-Price-Insight-Predictor
pip install -r requirements.txt
jupyter notebook notebooks/main.ipynb
```

---

## 📊 Evaluation Metrics Used
| Metric | Description |
|--------|--------------|
| **MSE** | Penalizes large errors |
| **RMSE** | Standard deviation of prediction error |
| **MAE** | Average absolute difference |
| **R² Score** | Variance explained by the model |

A feature impact bar chart is included to show which input variables affect price the most.

---

## 📈 Visual Outputs
- Heatmap: Feature correlation
- Actual vs Predicted scatter comparison
- Coefficient bar chart for feature importance
- Error metrics summary

---

## 💾 Model Export
Trained model saved at:
```
models/housing_regressor.pkl
```

---

## 📌 Notes
This project builds on concepts from Day 01 and transitions from a single-variable synthetic regression to a **multi-variable real dataset** for deeper insight.

