# ❤️ CardioStat: Statistical Insights into Heart Disease Risk

## 📖 Overview
This project explores **statistical analysis of heart disease risk factors** using a well-known healthcare dataset curated from **four international medical institutions**:
- Cleveland Clinic Foundation (USA)  
- Hungarian Institute of Cardiology (Budapest)  
- V.A. Medical Center (Long Beach, CA)  
- University Hospital (Zurich, Switzerland)  

The dataset contains **76 attributes**, with **14 key clinical indicators** commonly used in published research. These include age, sex, chest pain type, cholesterol, resting blood pressure, ECG results, maximum heart rate achieved, exercise-induced angina, ST depression, and thallium stress test results.

The **target variable** is the **heart disease risk value** (0–4), representing increasing likelihood of cardiovascular disease.

---

## 🎯 Project Goals
This project investigates **three critical healthcare questions** through data wrangling, exploratory data analysis (EDA), and statistical modeling:

1. **Geographic Variation**  
   Do patients from different hospital datasets show different *average risk values*?  
   Or is heart disease risk consistent across locations?

2. **Age and Risk**  
   Does the dataset reflect an **increased risk for older patients**?  
   If yes, what is the statistical significance?

3. **Cholesterol Threshold Effect**  
   How **probable** is it that a patient with **cholesterol > 200 mg/dL** will have **above-average heart disease risk**?

---

## 🛠️ Tech Stack
- **Data Engineering**: Pandas, NumPy for cleaning & preprocessing  
- **Data Analysis**: SciPy, Statsmodels for hypothesis testing & correlation analysis  
- **Data Science**: Scikit-learn for probability modeling  
- **Visualization**: Matplotlib, Seaborn for insights & healthcare reporting  
- **Reproducibility**: Jupyter Notebooks with step-by-step documentation  

---

## 📊 Methodology
1. **Data Wrangling**:  
   - Merged datasets from multiple hospitals  
   - Selected 14 clinically relevant attributes  
   - Handled missing values and encoded categorical features  

2. **Exploratory Data Analysis**:  
   - Distribution plots of cholesterol, blood pressure, and heart rate  
   - Risk value comparisons across hospital sources  
   - Age-group stratification vs. disease risk  

3. **Statistical Tests**:  
   - ANOVA / t-tests for comparing hospital datasets  
   - Correlation between age and risk values  
   - Logistic regression / conditional probability for cholesterol > 200 mg/dL  

---

## 🔑 Key Findings (Highlights)
- Certain hospitals reported **higher average risk values**, suggesting potential sampling bias.  
- **Age strongly correlates** with increased risk, supporting clinical assumptions.  
- Patients with **cholesterol > 200 mg/dL** were **significantly more likely** to have above-average risk.  

---

## 🚀 Future Work
- Build a **predictive ML model** to classify patients (risk 0–4)  
- Apply **feature engineering** to improve interpretability  
- Explore **modern datasets** to validate results against 21st-century health trends  

---

## 💡 Why This Project Matters
Cardiovascular disease remains the **#1 global cause of death**.  
This project demonstrates how **data engineers, analysts, and data scientists** can collaborate to:  
- Clean and integrate complex healthcare data  
- Perform **meaningful statistical tests**  
- Provide insights that may inform **clinical decision-making**  

---

## 🧑‍💻 Author
**Devarsh Vora**  
- 📎 [LinkedIn](https://linkedin.com/in/devarshvora)  
- 🌐 [Portfolio](https://devarshvora-portfolio.netlify.app)  

