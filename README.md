# 🧠 AI Data Quality Analyst Project – COVID Toy Dataset

This project is an AI Data Quality and Visualization report built using a sample COVID-19 dataset. It focuses on analyzing, cleaning, and visualizing health-related features like age, fever, cough type, city, and COVID test result.

---

## 📁 Dataset Overview

**Filename**: `covid_toy.csv`  
**Rows**: 100  
**Columns**:
- `age`: Age of the person
- `gender`: Male or Female
- `fever`: Body temperature (°F)
- `cough`: Cough severity (e.g., Mild, Severe)
- `city`: City of residence
- `has_covid`: COVID test result (`Yes` or `No`)

---

## ✅ Objectives

- Detect data quality issues (missing, duplicates, inconsistent values)
- Perform data cleaning and preprocessing
- Analyze key patterns and relationships
- Visualize data using Python (Matplotlib and Seaborn)

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas 🐼
- Seaborn 🎨
- Matplotlib 📊
- Google Colab (for interactive analysis)

---

## 📊 Visualizations Included

- Bar Charts (Grouped, Horizontal, Stacked)
- Pie Chart
- Line and Scatter Plots
- Histograms and KDE Curves
- Box Plots
- Heatmaps 


## 📦 How to Run

1. Clone the repository or download the code.
2. Open the `AI_Data_Quality_Analyst.ipynb` notebook in **Google Colab** or Jupyter Notebook.
3. Upload the dataset: `covid_toy.csv`.
4. Run cells step-by-step to see analysis, cleaning, and visualizations.

---

## 📌 Example Insights

- Fever values had some missing entries filled using mean imputation.
- Age and fever are weakly correlated.
- COVID cases were more frequent in certain cities and among certain genders.
- Visualization clearly shows patterns in symptoms and test results.


