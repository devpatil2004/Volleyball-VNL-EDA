# 🏐 Volleyball VNL 2023 — Exploratory Data Analysis

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the **Volleyball Nations League (VNL) 2023 dataset**.

The main goal of this project is to analyze volleyball match and player-related data, identify important patterns and trends, and understand the factors that contribute to team and player performance.

Python and its data analysis libraries were used to clean, explore, and visualize the dataset.

---

## 🎯 Objectives

The key objectives of this project are:

* Understand the structure and characteristics of the VNL 2023 dataset.
* Clean and preprocess the data.
* Handle missing and inconsistent values.
* Perform statistical analysis.
* Analyze team and player performance.
* Identify important performance patterns.
* Create meaningful visualizations.
* Generate insights from the data.

---

## 📊 Dataset

**Dataset:** Volleyball Nations League (VNL) 2023

The dataset contains information related to VNL 2023 volleyball matches and player/team performance.

The analysis explores different aspects of volleyball performance, such as:

* Teams
* Players
* Matches
* Match results
* Player statistics
* Team performance
* Attacking performance
* Blocking
* Serving
* Other available performance metrics

> **Note:** The exact columns analyzed depend on the data available in the VNL 2023 dataset.

---

## 🛠️ Technologies & Libraries

The project was developed using **Python**.

### Libraries Used

* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical computations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical data visualization
* **Jupyter Notebook** — Interactive analysis

---

## 🔍 Exploratory Data Analysis

The analysis includes the following steps:

### 1. Data Loading

The VNL 2023 dataset is imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("VNL2023.csv")
```

### 2. Data Understanding

The dataset is explored using functions such as:

```python
df.head()
df.shape
df.info()
df.describe()
df.columns
```

These help understand the dataset's structure, dimensions, data types, and statistical characteristics.

### 3. Data Cleaning

The data is checked for:

* Missing values
* Duplicate records
* Incorrect data types
* Inconsistent values
* Unnecessary columns

### 4. Data Analysis

Different questions are explored using Pandas, aggregation, grouping, and statistical analysis.

Examples include:

* Which teams performed better?
* Which players had stronger performance?
* What are the major performance differences between teams?
* Which performance metrics have the greatest impact on results?
* What patterns can be observed across the tournament?

### 5. Data Visualization

Visualizations are created using **Matplotlib** and **Seaborn** to make the results easier to understand.

Examples include:

* Bar charts
* Count plots
* Distribution plots
* Box plots
* Heatmaps
* Comparative team/player charts

---

## 📈 Key Insights

The EDA helps identify patterns in **team and player performance throughout VNL 2023**.

Some of the insights explored include:

* Differences in performance between teams.
* Distribution of player performance metrics.
* Strong and weak areas of teams.
* Relationship between different volleyball performance metrics.
* Performance patterns across the tournament.

The visualizations make it easier to compare teams and players and understand the underlying data.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/USERNAME/volleyball-eda.git
```

### 2. Navigate to the project directory

```bash
cd volleyball-eda
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open the `Volleyball_EDA.ipynb` notebook and run the cells.

---

## 💡 Conclusion

This project demonstrates how **Exploratory Data Analysis** can be used to understand sports data and extract meaningful insights from it.

By analyzing the **VNL 2023 volleyball dataset**, the project provides a better understanding of team and player performance while demonstrating practical skills in **Python, Pandas, data cleaning, data analysis, and data visualization**.

---

## 👨‍💻 Author

**Devendra Patil**

### Skills Demonstrated

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `EDA` · `Data Cleaning` · `Data Visualization`
