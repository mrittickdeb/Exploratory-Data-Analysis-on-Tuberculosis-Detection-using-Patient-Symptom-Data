# Exploratory Data Analysis on Tuberculosis Detection using Patient Symptom Data

## 📁 Project Overview

This project presents a detailed exploratory data analysis (EDA) on a synthetic dataset that simulates real-world tuberculosis (TB) cases. The dataset includes demographic and clinical attributes such as age, gender, smoking history, and symptom severity. The goal of the analysis is to uncover patterns, correlations, and potential indicators of TB, using visualization and statistical methods.

## 📚 Project Objectives

1. **Distribution Analysis**: Evaluate the overall distribution of TB vs. Normal cases in the dataset.
2. **Demographic Risk Factors**: Investigate how age, gender, and smoking status affect TB prevalence.
3. **Feature Correlation**: Identify clinical features most strongly associated with TB.
4. **Symptom Distribution**: Compare symptom intensity and spread across TB and Normal classes.
5. **High-Risk Patient Identification**: Engineer a composite Severity Score to flag high-risk individuals.
6. **Hypothesis Testing**: Use t-tests to determine if age significantly differs between TB and Normal cases.

## 🗂 Dataset

- **Source**: [Kaggle - Tuberculosis X-Ray Dataset (Synthetic)](https://www.kaggle.com/datasets/miadul/tuberculosis-x-ray-dataset-synthetic)
- **Contents**: 1,000 synthetic patient records
- **Features**:
  - Demographics: Age, Gender, Smoking History
  - Symptoms: Cough Severity, Weight Loss, Fatigue, Breathlessness, Fever, etc.
  - Target: Class (TB or Normal)

## 🧹 Data Preprocessing Steps

- Checked for and handled missing values and duplicates
- Converted categorical variables to numerical codes
- Mapped ordinal symptom features (e.g., Fever, Sputum_Production) to numeric scales
- Binned Age into meaningful age groups
- Computed correlation matrices and grouped statistics
- Prepared dataset for visual analysis and statistical testing

## 📊 Techniques & Tools Used

- **Programming Language**: Python (Jupyter Notebook)
- **Libraries**:
  - `pandas`, `numpy` – data wrangling
  - `seaborn`, `matplotlib` – visualization
  - `scipy.stats` – hypothesis testing (t-test)

## 📈 Key Visualizations

- Bar and Pie Charts – Class distribution (TB vs. Normal)
- Grouped Bar Charts – TB cases by gender, smoking, and age groups
- Heatmaps – Correlation between features and TB
- Box & Violin Plots – Symptom distribution by class
- Histogram with KDE – Weight loss distribution by TB class
- Bar Chart – Top 10 high-risk patients by Severity Score

## 📌 Notable Findings

- TB cases slightly outnumber Normal cases (~53% vs. 47%)
- Male smokers in the 31–60 age range show higher TB prevalence
- Severity_Score, Weight Loss, and Fatigue are strongly correlated with TB
- TB patients show consistently higher symptom severity across features
- T-test confirms a significant age difference between TB and Normal groups

## 📂 Repository Contents

├── CONFIRMEDPY.ipynb # Final Jupyter notebook with all analysis ├── mrittickpythonreport.doc # Report document with objectives, visuals, and interpretation ├── README.md # Project overview (this file)

## 📈 Future Scope

- Integration with real patient datasets for higher realism
- Development of predictive models based on Severity Score
- Expansion into symptom clustering using unsupervised learning
- Dashboard development for public health applications

## 👤 Author

**Mrittick Deb**  
Registration No: 12310324  
Lovely Professional University, CSE (INT375)

## 📌 License

This project is developed for educational purposes under INT375 – Data Science Toolbox and follows all academic integrity norms.

---

> For any suggestions or questions, feel free to connect via LinkedIn or reach out via GitHub issues.
