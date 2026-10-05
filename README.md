# Breast Cancer Dataset - Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Breast Cancer dataset.

The main objective is to understand the dataset using statistical analysis and data visualization techniques. The analysis focuses on identifying patterns, relationships, distributions, correlations, and possible outliers in the data.

The dataset contains measurements of breast cell nuclei and a diagnosis indicating whether the tumor is **Malignant (M)** or **Benign (B)**.

---

## 🎯 Objective

The objectives of this project are:

- Understand the structure of the dataset.
- Perform basic data cleaning.
- Generate descriptive statistics.
- Analyze numerical feature distributions.
- Identify possible outliers.
- Study relationships between different features.
- Analyze correlations between numerical variables.
- Compare features between benign and malignant tumors.
- Identify important patterns that may help in breast cancer classification.

---

## 🗂️ Dataset

The dataset used in this project is the **Breast Cancer Wisconsin Diagnostic Dataset**.

Each row represents a patient/tumor observation.

### Target Variable

The `diagnosis` column contains two classes:

| Value | Meaning |
|-------|---------|
| M | Malignant |
| B | Benign |

### Important Features

Some of the main numerical features include:

- `radius_mean`
- `texture_mean`
- `perimeter_mean`
- `area_mean`
- `smoothness_mean`
- `compactness_mean`
- `concavity_mean`
- `concave points_mean`
- `symmetry_mean`
- `fractal_dimension_mean`

The dataset also contains additional measurements such as standard error and worst-case values.

---

## 🛠️ Technologies Used

The following Python libraries are used:

- **Python**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical operations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualization
- **Plotly** - Interactive visualization
- **Jupyter Notebook** - Development environment

---

## 📁 Project Structure

```text
Breast-Cancer-EDA/
│
├── data.csv
├── TASK_2.ipynb
└── README.md
