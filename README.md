# project-01
 EDA – Exploratory Data Analysis (Student Project)

This repository contains my EDA (Exploratory Data Analysis) practice project where I worked with a raw, unclean dataset and transformed it into a clean, structured format suitable for analytics and machine learning.

## 📌 What This Project Covers

- Importing and exploring data (head, tail, info, shape, columns)
- Detecting missing values using isnull() and isna()
- Cleaning text columns using regex (str.replace)
- Extracting numeric values from text fields using str.extract
- Handling missing values with mean and mode imputation
- Converting data into proper numeric formats
- Saving the cleaned dataset to a CSV file
- Creating visualizations:
  - Salary distribution (histogram + distplot)
  - Boxenplot (Experience vs Salary)
  - Linear relationship plots using lmplot
- Creating dummy variables using pd.get_dummies() for ML readiness

## 🎯 Skills Practiced

- Data Cleaning & Preprocessing  
- Missing Value Handling  
- Regex Techniques  
- Data Visualization  
- Understanding Data Distributions  
- Feature Preparation for ML  
- One-Hot Encoding  

## 🛠 Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

## ✔ Purpose

This project is part of my learning journey in Data Science, where I am strengthening my core skills for Data Analysis, Machine Learning, and AI workflows.

# project-02

# 🤖 LLM-Powered Exploratory Data Analysis (EDA)

This project demonstrates an **automated Exploratory Data Analysis (EDA) system** using Python, where traditional data analysis is combined with **LLM-based insights**.

The application allows users to upload a CSV file and receive:
- EDA summary
- Missing value analysis
- Visualizations
- AI-generated insights

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Gradio
- Ollama (Mistral-7B LLM)

---

## 📂 Dataset Used

- Titanic dataset (CSV)
- Shape: 891 rows × 12 columns

---

## 🔍 What This Project Does

- Loads dataset using Pandas
- Checks missing values
- Fills missing values:
  - Median for numerical features
  - Mode for categorical features
- Generates dataset summary using `describe()`
- Performs EDA visualizations:
  - Survival count plot
  - Histograms with KDE
  - Correlation heatmap
- Uses **LLM (Mistral-7B)** to generate insights from dataset summary
- Displays results using a **Gradio web interface**

---

## 📊 Visualizations Generated

- Count plot for survival distribution
- Histogram for numerical columns
- Correlation heatmap for numeric features

---

## 🤖 AI Integration

- Dataset summary is passed to the LLM
- LLM generates insights automatically
- Helps interpret statistical results in natural language

---

## 🎯 What I Learned

- How to automate EDA using Python
- How to handle missing values programmatically
- How to integrate LLMs with data analysis
- How to build interactive data apps using Gradio
- How AI can assist in data understanding

---

