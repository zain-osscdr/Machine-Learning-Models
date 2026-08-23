# Machine Learning Models & Datasets

A structured collection of machine learning experiments, datasets, Jupyter notebooks, and project documentation covering classification and regression problems.

## 📌 Project Overview

This repository contains practical machine learning work developed using multiple datasets from different domains. The projects cover data exploration, preprocessing, feature preparation, model training, prediction, and evaluation.

The repository is organized into two primary areas:

- **Classification Models & Datasets**
- **Regression Models & Datasets**

A complete project report is also included.

## 📂 Repository Structure

```text
Machine-Learning-Models/
│
├── Classification Models & Datasets/
│   ├── Global Student Performance & Lifestyle.ipynb
│   ├── Stroke Risk Synthetic 2025.ipynb
│   └── Student Performance & Teaching Dataset.ipynb
│
├── Regression Models & Datasets/
│   ├── Life Expectancy (WHO).ipynb
│   ├── Walmart Dataset.ipynb
│   └── _Medical Cost Personal .ipynb
│
├── ML Project Report.pdf
└── .gitignore
🧠 Classification Models & Datasets
1. Global Student Performance & Lifestyle

Notebook: Global Student Performance & Lifestyle.ipynb

This project works with student lifestyle and academic performance information for machine learning analysis.

Dataset: global_student_lifestyle_academic_performance.csv

The notebook explores the available student-related features and applies machine learning techniques to the dataset.

2. Student Performance & Teaching

Notebook: Student Performance & Teaching Dataset.ipynb

This project focuses on student performance and teaching-related information.

Dataset: Student_Performance_Teaching_Effectiveness.csv

The notebook provides the workflow for exploring the dataset, preparing features, and applying machine learning techniques.

3. Stroke Risk

Notebook: Stroke Risk Synthetic 2025.ipynb

This project works with a synthetic stroke-risk dataset and demonstrates machine learning analysis using health-related features.

Dataset: stroke_dataset.csv

Note: The dataset is identified as synthetic in the project files. The resulting model should not be interpreted as a clinically validated medical prediction system.

📈 Regression Models & Datasets
1. Life Expectancy

Notebook: Life Expectancy (WHO).ipynb

Dataset: Life Expectancy Data.csv

This project analyzes factors associated with life expectancy using country-level health and socioeconomic information and applies regression-based machine learning techniques.

2. Walmart Sales

Notebook: Walmart Dataset.ipynb

Dataset: Walmart.csv

This project analyzes Walmart sales data and applies regression techniques to model weekly sales.

The notebook includes:

Linear Regression
Decision Tree Regression
Random Forest Regression
3. Medical Cost Personal

Notebook: _Medical Cost Personal .ipynb

Dataset: insurance.csv

This project uses personal medical insurance information for regression analysis.

The objective is to analyze the relationship between available personal and demographic features and medical insurance charges.

🛠️ Technologies
Python
Jupyter Notebook
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Joblib
🔬 Machine Learning Workflow

The projects generally follow this workflow:

Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Cleaning / Preprocessing
   ↓
Feature Preparation
   ↓
Train / Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Result Analysis
📊 Dataset Overview
Dataset	Domain	Primary Focus
Global Student Lifestyle & Academic Performance	Education	Student performance analysis
Student Performance & Teaching Effectiveness	Education	Student and teaching analysis
Stroke Dataset	Health / Risk Analysis	Stroke-risk analysis
Life Expectancy	Public Health	Life-expectancy analysis
Walmart Sales	Retail	Sales prediction
Insurance	Medical Cost Analysis	Insurance-cost prediction
📓 Jupyter Notebooks

The notebooks contain the practical implementations of the machine learning workflows.

They can be opened using:

Jupyter Notebook
JupyterLab
Visual Studio Code
Google Colab

Before running a notebook, ensure that the required Python libraries are installed and that the corresponding dataset is available at the expected path.

📄 Project Report

The complete project documentation is available in:

ML Project Report.pdf

The report provides additional information about the machine learning project, methodology, experiments, and implementation.

🎯 Project Goals
Practice practical machine learning workflows
Work with datasets from different domains
Understand classification and regression problems
Apply data preprocessing techniques
Train and evaluate machine learning models
Compare different machine learning approaches
Maintain organized and reusable machine learning work
⚠️ Disclaimer

The datasets and notebooks in this repository are provided for educational and experimental purposes.

Health-related datasets and models should not be treated as medical or clinical decision-making systems.

Model performance depends on the dataset, preprocessing techniques, selected features, and experimental setup used in each notebook.
