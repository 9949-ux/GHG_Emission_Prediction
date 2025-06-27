# GHG_Emission_Prediction
# 🌿 GHG Emission Prediction

## 📌 Project Goal

This project aims to **analyze and predict greenhouse gas (GHG) emissions** from various U.S. industries and commodities. It leverages machine learning techniques to model GHG emission behavior based on economic and industrial data provided by the U.S. government.

---

## 📁 Dataset Overview

- **Source**: [data.gov – Supply Chain Greenhouse Gas Emission Factors](https://data.gov)
- **Description**: This dataset includes GHG emissions (in kg CO₂e) linked to supply chain commodities and industries.

### 🔑 Key Columns:
| Column Name             | Description                                                |
|------------------------|------------------------------------------------------------|
| `Code`                 | Industry classification code                                |
| `Industry_Name`        | Name of the U.S. industry                                   |
| `Commodity`            | Item or commodity name                                     |
| `GHG_Emissions_kgCO2e` | Emissions per unit (kg CO₂ equivalent)                     |
| `Units`                | Measurement unit (e.g., kg/2018 USD, purchaser price)      |

---

## 🧰 Tools & Libraries

- **Python**
- `Pandas` – data handling
- `Matplotlib` & `Seaborn` – data visualization
- `Scikit-learn` – machine learning

---

## 🧪 Project Steps

### Step 1: Import Required Libraries
Standard libraries used for data loading, cleaning, modeling, and evaluation.

### Step 2: Load Dataset
Load and preview the structure, types, and null values.

### Step 3: Data Preprocessing
- Handle missing values
- Unit conversion (if applicable)
- Label encoding for categorical features
- Scaling of numerical columns

### Step 4: Model Building
Train models to predict `GHG_Emissions_kgCO2e` using:
- Linear Regression
- Random Forest Regression

### Step 5: Model Evaluation
Metrics used:
- RMSE (Root Mean Square Error)
- MAE (Mean Absolute Error)
- R² Score (Coefficient of Determination)

### Step 6: Hyperparameter Tuning
Optimize model performance using `GridSearchCV`.

### Step 7: Model Comparison
Compare all trained models and select the best-performing one based on evaluation metrics.

---

## 📊 Visualizations

- Distribution plots of GHG emissions
- Correlation heatmap
- Bar charts comparing industries and commodities with high emissions

---

## ✅ Results

- The Random Forest model outperformed linear regression with higher R² and lower RMSE.
- Key features influencing emissions include commodity type and industry category.

---

## 🚀 Future Enhancements

- Add support for time-series analysis if temporal data becomes available
- Deploy the best model using Streamlit or Flask
- Integrate external APIs for real-time commodity data

---

## 📁 Project Structure

