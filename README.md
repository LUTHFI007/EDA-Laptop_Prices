# 📊 Exploratory Data Analysis: Laptop Pricing Dataset

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a laptop pricing dataset to understand the factors influencing laptop prices.  
The workflow includes data cleaning, visualization, statistical analysis, and identifying significant features that impact pricing.

---

## 🎯 Objectives
- **Data Cleaning**: Handle missing values, remove unnecessary columns.  
- **Feature Exploration**: Visualize patterns in individual numerical and categorical features.  
- **Descriptive Statistics**: Summarize central tendency, dispersion, and distribution shape.  
- **Group Analysis**: Use grouping and pivot tables to understand category-price relationships.  
- **Correlation Analysis**: Apply Pearson correlation to measure feature importance for price prediction.

---

## 🛠️ Tools & Libraries
- **Python** (Pandas, NumPy)  
- **Matplotlib** & **Seaborn** (Data Visualization)  
- **SciPy** (Statistical Analysis)  

---

## 📂 Dataset
The dataset contains laptop specifications such as:  
- CPU Frequency  
- RAM (GB)  
- Storage (GB SSD)  
- Screen Size (cm)  
- Weight (kg)  
- GPU, OS, Category, CPU Core Count  
- Price  

## 🔍 Key Steps in the Analysis
1. **Data Loading & Cleaning**  
   - Removed unnecessary index column.  
   - Filled missing values for `Screen_Size_cm` and `Weight_kg` using mean imputation.

2. **Numerical Feature Analysis**  
   - Regression plots for CPU Frequency, Screen Size, and Weight vs Price.

3. **Categorical Feature Analysis**  
   - Boxplots for Category, GPU, OS, CPU Core, RAM, and Storage vs Price.

4. **Group & Pivot Table Analysis**  
   - GPU vs CPU Core combinations analyzed using a heatmap.

5. **Correlation & Statistical Significance**  
   - Pearson correlation with p-values to rank features by importance.  
   - `RAM_GB` showed the highest correlation with Price (0.55).

---

## 📈 Key Findings
- **RAM_GB** has the strongest positive correlation with price (0.55, moderate).  
- CPU cores and CPU frequency also have moderate positive correlations.  
- Screen size and weight show weak negative correlations with price.  
- Most correlations are statistically significant (p < 0.05), except weight.

---

## 📷 Sample Visualizations
- Regression plots for continuous variables vs Price.  
- Boxplots for categorical variables vs Price.  
- Heatmap from pivot table analysis.

---


