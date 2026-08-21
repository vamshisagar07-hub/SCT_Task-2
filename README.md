# SCT_Task-2: Titanic EDA & Data Cleaning

This repository contains **Task 02** of my Data Science Internship with **SkillCraft Technology**.

## 📌 Project Overview
Performed Exploratory Data Analysis (EDA) and data cleaning on the Titanic dataset using Python in Google Colab to identify key demographics and factors influencing passenger survival rates.

## 🛠️ Key Steps & Workflow
1. **Data Cleaning:** Imputed missing values for `age` and `fare`, and removed high-null/non-predictive columns (`cabin`, `ticket`, `boat`, `body`, `home.dest`).
2. **Univariate Analysis:** Generated histograms and count plots for age distribution, class splits, and survival totals.
3. **Bivariate & Multivariate Analysis:** Analyzed survival rates by gender and class (`pclass`), including side-by-side counts of survived vs. deceased per gender.
4. **Correlation Analysis:** Created a heatmap to highlight relationships among numerical variables.

## 📊 Core Findings
- **Gender Impact:** Females achieved a ~74% survival rate compared to under 20% for males.
- **Class Impact:** 1st Class passengers had the highest survival rate (~63%) compared to 3rd Class (~24%).
- **Combined Demographics:** 1st Class females had the highest survival probability (>95%), while 3rd Class males had the lowest (~15%).

## 📁 Repository Structure
- `Task2_Titanic_EDA.ipynb`: Complete Python notebook with code, outputs, and visualizations.
- `README.md`: Project overview and documentation.
