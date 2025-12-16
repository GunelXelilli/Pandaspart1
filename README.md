# 📊 Pandas – Part 1  
## Introduction to DataFrame & Lists

This section is an **introduction to the Pandas library in Python**, focusing on  
creating and working with **DataFrames using lists**.

---

## 🐼 What is Pandas?
**Pandas** is a powerful Python library used for:
- Reading data 📥  
- Cleaning data 🧹  
- Analyzing data 📈  
- Storing data in structured formats 🗂️  

It is widely used in **data analysis, data science, and machine learning**.

---

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
🎯 What You Will Learn in This Part

✔ What Pandas is and why it is used
✔ Difference between Series and DataFrame
✔ How to create DataFrames from lists
✔ Basic methods to explore a DataFrame

🚀 Next Part (Part 2)

Reading CSV / Excel files

Column selection

Filtering with conditions

📌 This README is designed for beginners learning Pandas.
✨ Simple explanations with practical examples.

Basic data analysis
