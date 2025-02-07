# 📍 Newmark Property Investment Analysis

## 🔍 Data-Driven Insights to Identify High-Growth ZIP Codes

### 🚀 Executive Summary
This project leverages **geospatial analysis** and **predictive modeling** to identify **top 10 high-growth ZIP codes** for property investment. By integrating **spatial statistics, machine learning, and economic indicators**, the analysis uncovers **hidden investment gems** and provides a **data-backed strategy** for high-return property investments.

---

## 🏢 Business Problem

### Key Questions:
1. **Where to Invest?** – Which 10 ZIP codes show the highest property value growth potential?
2. **Why These ZIP Codes?** – What economic and geographic factors drive their growth?
3. **Geospatial Influence?** – How do neighboring ZIP codes impact property values?

---

## 📊 Methodology Overview

### 🔹 Data Collection & Cleaning
- Census data (2012–2018) covering **demographics, housing prices, and income levels**.
- Removed **missing values and outliers** to ensure model robustness.

### 🔹 Exploratory Data Analysis (EDA)
- Identified **key trends, correlations, and data distributions**.

### 🔹 Predictive Modeling
- **Model Used:** Random Forest Regressor, optimized using **Bayesian Optimization**.
- **Performance Metrics:**  
  - **RMSE:** 17,194.94 (Best Run)  
  - **R² Score:** 0.92 (Best Run)

### 🔹 Geospatial Analysis
- **Moran’s I Statistic** – Measures spatial autocorrelation of property values.
- **Hot Spot Analysis (Getis-Ord Gi*)** – Identifies high-growth clusters.
- **Spatial Lag Effect** – Analyzes how neighboring ZIP codes influence property growth.

---

## 🏆 Predictive Model Performance

| Metric | Score |
|--------|------:|
| **R² Score** | **0.92** |
| **RMSE** | **17,194.94** |

💡 **Model Interpretation:**  
- Areas with **rising median home values, gross rent, and household income** show the highest property growth potential.
- **State-level economic factors** influence real estate appreciation.

---

## 📍 Top 10 ZIP Codes for Investment
Based on predictive modeling, these ZIP codes have **the highest forecasted property value growth**:

`['40213', '40214', '40217', '40219', '40505', '41041', '41095', '42066', '46011', '46060']`

---

## 💎 Hidden Gems for Investment

### 🔥 Definition
Hidden gems are **moderately priced ZIP codes** with **high growth potential** based on geospatial influence.

### 🎯 Why Invest?
- **Undervalued markets poised for rapid growth**.
- **Early-stage investment opportunities** before value appreciation.

### 📌 Identified Hidden Gem ZIP Codes:
`['46158', '46208', '46225', '46228', '46254', '46268', '46342', '46410', '46506', '46510', '46526', '46534', '46580', '46614', '46923', '46962', '47126', '47150', '47172', '47232', '47421', '47546', '47957', '47960']`

---

## 📊 Business Recommendations

✅ **Prioritize Investments** in the **Top 10 ZIP codes** identified.  
✅ **Leverage Hidden Gems** for early-stage, high-return investments.  
✅ **Monitor Geospatial Trends** with real-time data updates.  

---

## 🔮 Future Enhancements

📌 **Model Enhancements**
- Integrate **macroeconomic data** (e.g., interest rates, employment stats).
- Experiment with **deep learning models** for better accuracy.

📌 **Advanced Geospatial Analysis**
- Incorporate **real-time data** (e.g., housing permits, infrastructure projects).
- Utilize **dynamic spatial models** for continuous market monitoring.

---

## 🎯 Conclusion & Next Steps
This **data-driven approach** enables **strategic real estate investment** with **high ROI potential**.  
By combining **predictive modeling** and **spatial statistics**, this project offers **a competitive edge** in identifying the best investment locations.

### 🏠 Next Steps:
- **Operationalize the model** for real-time decision-making.
- **Deploy insights into a business workflow** for dynamic market evaluation.

---

## 💻 Repository Structure

```
📂 Newmark_Property_Investment_Analysis/
├── Newmark_assessment_final.ipynb   # Jupyter Notebook with full analysis
├── Newmark_Property_Investment_Analysis.pptx # Business presentation
└── README.md  # This document
```

---

## 🚀 How to Use This Repository

1️⃣ Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Newmark_Property_Investment_Analysis.git
   cd Newmark_Property_Investment_Analysis
   ```

2️⃣ Open the Jupyter Notebook:  
   ```bash
   jupyter notebook Newmark_assessment_final.ipynb
   ```

3️⃣ Run all cells to generate insights and visualizations.

---
