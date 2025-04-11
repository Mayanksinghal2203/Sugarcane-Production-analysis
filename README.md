# 🌾 Exploratory Data Analysis on Global Sugarcane Production

This project focuses on performing Exploratory Data Analysis (EDA) on global sugarcane production data to uncover patterns, trends, and insights related to agricultural efficiency, production volumes, and per capita outputs across countries.

---

## 📊 Project Overview

- **Goal:** Analyze sugarcane production data to understand yield efficiency, production per capita, and regional patterns.
- **Dataset:** Collected from a CSV file listing global sugarcane production metrics including:
  - Total production (tons)
  - Production per person (kg)
  - Acreage (hectares)
  - Yield (kg/hectare)

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (for imputation)
- Jupyter Notebook

---

## 🔍 Key Tasks Performed

- Cleaned and transformed raw data by:
  - Removing formatting inconsistencies (e.g., periods as thousand separators)
  - Converting string values to numeric
  - Handling missing values using `SimpleImputer` and drop methods
- Engineered new features and renamed columns for clarity
- Visualized:
  - Top producing countries
  - Yield distribution
  - Correlation between acreage and production
- Gained insights into which countries have the highest efficiency in terms of yield per hectare

---

## 📂 Project Structure

```bash
📦sugarcane-eda
 ┣ 📄 sugarcane_production_eda.ipynb
 ┣ 📄 List of Countries by Sugarcane Production.csv
 ┗ 📄 README.md
