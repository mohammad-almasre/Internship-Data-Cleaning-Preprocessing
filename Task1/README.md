# 🎬 Netflix Data Cleaning & Preprocessing

This repository contains **Task 1** of my Data Science Internship project, focusing on cleaning and preprocessing the Netflix Movies & TV Shows dataset.

---

## 📌 Project Overview

The objective of this task is to prepare the raw dataset for future analysis by performing essential data cleaning and preprocessing steps.

The cleaned dataset produced in this project will be used in the following internship tasks such as Exploratory Data Analysis (EDA), Machine Learning, and Data Visualization.

---

## 📂 Repository Structure

```
.
├── Dataset.csv                     # Original dataset
├── cleaned_netflix_dataset.csv     # Cleaned dataset
├── Task1.ipynb                     # Data cleaning notebook
└── README.md
```

---

## 🛠️ Data Cleaning Steps

The following preprocessing operations were performed:

- Loaded the dataset using Pandas.
- Explored dataset structure and data types.
- Checked for duplicate records.
- Removed duplicate rows.
- Replaced missing/unknown values with appropriate labels.
- Converted `date_added` to datetime format.
- Created additional useful features:
  - `duration_min`
  - `seasons_count`
  - `year_added`
  - `month_added`
- Exported the cleaned dataset.

---

## 📊 Dataset Information

| Item | Value |
|------|------:|
| Original Records | 8,790 |
| Records After Cleaning | 8,786 |
| Original Columns | 10 |
| Final Columns | 13 |

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 📁 Output Files

- **Dataset.csv** → Original dataset
- **cleaned_netflix_dataset.csv** → Cleaned dataset ready for analysis

---

## 🚀 Next Steps

The cleaned dataset will be used in the upcoming internship tasks:

- Exploratory Data Analysis (EDA)
- Data Visualization
- Recommendation System
- Trend Prediction
- Classification Models
- Dashboard Development

---

## 👨‍💻 Author

**Mohammad Riyad Al-Masre**

Data Science Internship Project