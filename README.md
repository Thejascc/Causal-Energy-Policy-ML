# ⚡ Causal Energy Policy ML

This project uses **advanced causal machine learning** techniques to evaluate how different building characteristics impact energy consumption (specifically, **heating load**). The analysis leverages methods like **Double Machine Learning (DML)** and **T-Learner with XGBoost**, combined with **SHAP** for explainability.

---

## 📊 Dataset

- **Name:** [Energy Efficiency Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency)
- **Features:** Building design variables (e.g., surface area, glazing area, orientation)
- **Target:** Heating Load (Y1)
- **Treatment:** High vs Low Roof Area (binary treatment)

---

## 🔍 Techniques Used

| Method                      | Library        | Description                                     |
|----------------------------|----------------|-------------------------------------------------|
| LinearDML                  | `econml`       | Double Machine Learning for causal inference    |
| T-Learner (BaseTRegressor) | `causalml`     | Tree-based meta-learner using XGBoost           |
| SHAP                       | `shap`         | Feature importance via model explanation        |
| KDE Plots                  | `seaborn`      | Visualization of ITE distributions              |

---

## 📁 Project Structure

causal-energy-policy-ml/
├── causal_energy_policy.ipynb # Jupyter notebook with full workflow
├── requirements.txt # Python dependencies
└── README.md # Project overview (this file)

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/causal-energy-policy-ml.git
   cd causal-energy-policy-ml
