# Hyperspectral-Data-Analysis-for-Millets-Fats

This project applies **machine learning regression models** to hyperspectral reflectance data of different millet varieties in order to predict their **fat content**.  
The dataset is based on **hyperspectral bands (1–169)** as input features, with the target variable being **Fat (%)**.

---

## Features
- Reads and preprocesses **hyperspectral millet dataset** (`Hyperspectral_data_millets_fat.csv`).
- Implements and evaluates multiple regression algorithms:
  - **Linear Regression**
  - **Ridge Regression** (with cross-validation for optimal alpha)
  - **Lasso Regression** (with cross-validation for optimal alpha)
  - **Elastic Net Regression** (with optimal alpha and L1 ratio)
  - **Partial Least Squares Regression (PLSR)** with PCA
  - **Support Vector Regression (SVR)**
- Evaluates models using:
  - ✅ Mean Squared Error (MSE)  
  - ✅ R² Score
- Visualizes model performance comparison in a single plot.

---

## Dataset
The dataset used is:

- **`Hyperspectral_data_millets_fat.csv`**

**Columns:**
- `Samples` → Millet samples  
- `Fat` → Target variable (percentage of fat)  
- `Band_1 ... Band_169` → Hyperspectral reflectance values  
