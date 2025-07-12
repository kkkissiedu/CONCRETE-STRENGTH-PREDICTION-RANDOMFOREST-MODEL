# 🧪 Data-Driven Concrete Strength Prediction

This project applies **machine learning** to a core civil engineering challenge: predicting the **compressive strength** of concrete. Using a **Random Forest Regressor**, it estimates strength based on the mix components—enabling optimization for **performance**, **cost**, and **sustainability**.

> ✅ Successfully used on *"The Ark"* construction project to select a mix with **10% higher predicted strength**.

---

## 📊 Dataset

The analysis is performed on the **Concrete Compressive Strength Data Set**. This dataset contains 8 quantitative input variables representing the components of concrete and 1 quantitative output variable, which is the concrete compressive strength.

### **Features (Input Variables):**
* Cement
* Blast Furnace Slag
* Fly Ash
* Water
* Superplasticizer
* Coarse Aggregate
* Fine Aggregate
* Age (in days)

### **Target (Output Variable):**
* Concrete compressive strength (in MPa)

---
## 🎯 Goal & Motivation

Traditional mix design methods are empirical and slow. This project provides a **data-driven alternative** to:

- ⚡ Rapidly estimate strength from mix proportions  
- 🧠 Optimize mix designs more efficiently  
- 🏗️ Support faster, smarter material decisions

---

## 📊 Key Results

### 🔹 Model Performance

| Metric                  | Score     |
|-------------------------|-----------|
| R-squared (R²)          | `0.87`    |
| Mean Absolute Error (MAE) | `5.81 MPa` |

---

### 🔹 Predicted vs Actual Strength

![output](output.png)

---

### 🔹 Feature Importance

![importances](feature_importances.png)

---

## 🧰 Tech Stack

| Component       | Technology                          |
|------------------|--------------------------------------|
| Model           | `RandomForestRegressor` (scikit-learn) |
| Data Libraries  | Pandas, NumPy                        |
| Visualization   | Matplotlib, Seaborn                  |
| Tuning          | GridSearchCV                         |

---
