# 📊 Pandas & Car Data Projects

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 🐼 What is Pandas?
**Pandas** is a powerful Python library used for:
- Reading data 📥  
- Cleaning data 🧹  
- Analyzing data 📈  
- Storing data in structured formats 🗂️  

It is widely used in **data analysis, data science, and machine learning**.

## 🧱 Core Concepts

### 🔹 Series
- One-dimensional data structure  
- Similar to a list  
- Represents a single column  

### 🔹 DataFrame
- Two-dimensional tabular data structure  
- Consists of rows and columns  
- Similar to an Excel spreadsheet  

---

## 📋 Creating a DataFrame from Lists

### ▶️ Example 1: Simple List
```python
import pandas as pd

numbers = [10, 20, 30, 40]
df = pd.DataFrame(numbers, columns=["Numbers"])
print(df)

▶️ Example 2: List of Lists
data = [
    ["Ali", 20, "A"],
    ["Aysel", 21, "B"],
    ["Murad", 19, "A"]
]

df = pd.DataFrame(data, columns=["Name", "Age", "Grade"])
print(df)
▶️ Example 3: Dictionary with Lists
data = {
    "Name": ["Ali", "Aysel", "Murad"],
    "Age": [20, 21, 19],
    "City": ["Baku", "Ganja", "Sumqayit"]
}

df = pd.DataFrame(data)
print(df)
Basic DataFrame Operations
df.head()      # Shows first 5 rows
df.tail()      # Shows last 5 rows
df.shape       # Returns (rows, columns)
df.columns     # Displays column names
df.info()      # General information about the DataFrame
```
## 🧩 Basics — DataFrames & Lists

Check `PandasPart1.ipynb` for:

- Creating DataFrames  
- Exploring data with `.head()`, `.shape`, `.info()`, `.columns`  

---

## 🚀 Data Cleaning & Filtering

Check `PandasPart2.ipynb` for:

- Cleaning text & numeric columns  
- Adding new columns (like Currency)  
- Removing duplicates  
- Handling missing values in car datasets  

---

## 🚗 Car Data Projects

Worked on:

* **Car Sales Dataset** — cleaned prices, removed duplicates  
* **Car Dataset** — handled missing values, filtered data  

Example:

```python
# Handling missing values
df.isna().sum()  # Count missing
df.dropna()      # Remove missing rows
df.fillna(0)     # Fill missing values
```

---

## 🎯 Topics Covered

- ✅ DataFrames & Series  
- ✅ Reading CSV / Excel files  
- ✅ Filtering & selection  
- ✅ Cleaning text & numeric data  
- ✅ Removing duplicates  
- ✅ Handling missing values  

---

## 📁 Repository Structure

```
/Pandas-Car-Projects
│
├── data/               # CSV / Excel datasets
├── notebooks/
│   ├── PandasPart1.ipynb  # Basics & DataFrames
│   └── PandasPart2.ipynb  # Cleaning & Car Data
├── README.md           # This file
└── LICENSE             # MIT License
```

---

## 💙 License

This project is licensed under the **MIT License** — see `LICENSE` for details.  

Happy Coding! 🐍




---


