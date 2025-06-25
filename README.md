# MachineLearning-miniProject

## 🌳 Forest Carbon Sequestration Using Machine Learning

### 📌 Overview

This project explores how machine learning techniques can be applied to predict **forest carbon sequestration**—the process by which forests absorb and store carbon dioxide (CO₂) from the atmosphere. The ability to accurately estimate carbon sequestration helps in climate modeling, policy decisions, and sustainable forest management.

---

### 🎯 Problem Statement

The goal is to build a machine learning model that predicts the amount of carbon sequestered based on forest attributes like tree species, biomass, age, climate, and soil characteristics.

---

### 📂 Dataset

* **Source:** U.S. Forest Service Open Data / FAO / other academic repositories
* **Attributes include:**

  * Tree species
  * Tree height and diameter
  * Age of forest stand
  * Soil type and quality
  * Temperature and rainfall
  * **Target Variable:** Carbon stock (in metric tons per hectare)

---

### 🧹 Data Preprocessing

* Missing values handled via imputation
* Categorical variables encoded (tree species, soil type)
* Normalized numerical variables for model performance
* Split into training (80%) and testing (20%) sets

---

### 📈 Exploratory Data Analysis

* Visualized distribution of carbon stock across species and age
* Positive correlation found between tree age, biomass, and carbon storage
* Noted geographical patterns in carbon sequestration potential

---

### 🧠 Models Used

| Model                   | Accuracy (R²) | RMSE   |
| ----------------------- | ------------- | ------ |
| Linear Regression       | 0.71          | Medium |
| Random Forest Regressor | **0.89**      | Low    |
| XGBoost Regressor       | 0.87          | Low    |

✅ **Best Model:** Random Forest Regressor (strong balance of accuracy and interpretability)

---

### 📊 Results

* The Random Forest model was able to predict carbon sequestration with high accuracy (R² = 0.89).
* Important features: tree age, diameter, biomass, and region.

---

### 📌 Applications

* Used by forest managers for planning afforestation
* Supports carbon offset programs and environmental sustainability
* Can be integrated with GIS for spatial carbon mapping

---

### 🛠 Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

---

### 📁 Project Structure

```
forest-carbon-sequestration/
│
├── data/                       # Raw and processed data
├── notebooks/                 # Jupyter Notebooks
├── src/                       # Python scripts (if modularized)
├── results/                   # Plots, evaluation reports
├── README.md                  # Project overview
├── requirements.txt           # Dependencies
└── model.pkl                  # Saved ML model
```
