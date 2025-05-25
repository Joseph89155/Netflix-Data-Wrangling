# 🎬 Netflix Data Wrangling Project 📊

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-purple?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 🌟 Project Overview

This project is a **data wrangling journey** through Netflix's catalog tackling messy, real world data and turning it into a reliable, analysis ready dataset.

### 🎯 Problem Statement

With hundreds of shows and movies being added and removed on Netflix every year, understanding patterns in content **What types of shows dominate? What ratings are common? Which countries produce the most content?**  can be tricky. Raw data from such platforms is often full of inconsistencies and missing values.

> 📉 **The Challenge**: Clean, normalize, and structure the raw Netflix data to extract meaningful insights.

---

## 🧩 Key Steps in the Project

### 🔍 1. Data Acquisition

- Scraped Netflix dataset from Kaggle (or a simulated real-world source).
- Loaded it into a Pandas DataFrame for transformation.

### 🧹 2. Data Cleaning

- ✅ Removed duplicates and nulls
- ✅ Parsed `duration` into `duration_value` and `duration_unit`
- ✅ Normalized `rating` and `country` columns
- ✅ Converted `date_added` into datetime format

### 🧱 3. Structuring the Data

- Separated compound fields like `listed_in` (genres) and cleaned country values.
- Created structured subfields to support exploratory data analysis.

### 🧪 4. Normalization & Standardization

- Unified different representations for ratings (e.g. `TV-MA`, `NR`, weird minute labels).
- Harmonized country names and consolidated uncommon ones under `"Unknown"` or grouped by regions.

---

## 📈 Real-Life Impact

This project mimics what a real **Data Analyst or Data Engineer** might face when dealing with content platforms or streaming services. It's not just an academic exercise — it's about turning **chaotic raw data** into a **decision-making asset**.

🔑 **Use cases unlocked by this cleaned dataset**:

- Identify which countries dominate Netflix’s content library
- Analyze family-friendly vs mature content trends
- Correlate content duration with content type (Movie vs Show)
- Genre distribution analysis for business and product decisions

---

## 📂 Files in This Repository

| File | Description |
|------|-------------|
| `netflix_raw.csv` | Original dataset (before cleaning) |
| `cleaned_netflix.csv` | Cleaned and transformed dataset |
| `notebook.ipynb` | Full google colab containing the code and outputs |
| `README.md` | This documentation |

---

## 🧰 Technologies Used

- 🐍 Python 3.10+
- 🧼 Pandas
- 📘 Jupyter Notebook
- 🧪 NumPy
- 📊 Matplotlib & Seaborn *(optional for visualizations)*

---

## 🚀 Getting Started

Clone this repo and run the notebook:

---

## 📜 License
This project is open-source under the MIT License.

---

## 🙌 Acknowledgements.
 - Dataset sourced and inspired by Netflix's public metadata via Kaggle.

 - Guided by real-world wrangling principles used in data journalism and analytics.

---
