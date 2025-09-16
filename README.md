# Ds_training_ITS

**Understanding and Forecasting Student Performance in India**

---

## ✅ Project Overview

This project analyzes student performance data to explore, model, and forecast outcomes across academic metrics. Using data on student demographics and exam scores, it aims to:

- Perform exploratory data analysis (EDA) to uncover patterns/trends  
- Compute descriptive statistics for subject scores  
- Build regression and classification models to predict overall performance  
- Provide insights on which demographic factors influence performance the most  

---

## 📂 Repository Structure

| File / Folder | Description |
|---|---|
| `Understanding and Forecasting Student Performance in India.ipynb` | Jupyter Notebook containing analyses: data cleaning, EDA, modeling, results, visualizations. |
| `Understanding and Forecasting Student Performance in India.pdf` | PDF version of the notebook (static report). |
| `SQLImg/` | SQL query images or diagrams related to the analyses. |

---

## 🛠 Data

- The dataset used is the Student Performance (Math, Reading, Writing Scores) (available on Kaggle) or equivalent, cleaned and preprocessed.
- Dataset link: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams 
- Key variables include: `math score`, `reading score`, `writing score`, gender, race/ethnicity, parental education, test preparation status, etc.  
- Derived fields such as **total score**, **average score**, **performance category** (Low/Medium/High) are used.

---

## 🔍 Key Analyses

1. **Exploratory Data Analysis**  
   - Histograms, boxplots, scatter plots to visualize score distributions by gender, parental education, etc.  
   - Correlation heatmap among numeric features to understand inter-relations.

2. **Descriptive Statistics**  
   - Mean, median, variance, standard deviation for each subject score.  
   - Summary tables by demographic groups.  
   - Coefficient of variation to measure relative variability.

3. **Machine Learning**  
   - **Regression tasks**: Predicting average/total scores using models like Linear Regression and Random Forest.  
   - **Classification tasks**: Assigning performance category (Low/Medium/High) using Logistic Regression, Decision Trees, Random Forest; comparing their performance; extracting feature importance.

---

## 📈 How to Use / Reproduce

To run the analysis yourself:

1. Clone the repository:

   ```bash
   git clone https://github.com/adarsh0707-kumar/Ds_training_ITS.git
   cd Ds_training_ITS
