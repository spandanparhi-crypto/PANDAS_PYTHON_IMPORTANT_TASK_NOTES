# 🐼 Pandas Python Important Notes

> A complete collection of **Pandas** concepts, methods, examples, and data analysis techniques for beginners to advanced learners.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

---

# 📖 About

This repository contains all the important **Pandas Python Notes** with:

- ✅ Syntax
- ✅ Examples
- ✅ Output
- ✅ Explanation
- ✅ Data Cleaning
- ✅ Data Manipulation
- ✅ Data Analysis
- ✅ File Handling
- ✅ Real-world Practice Examples

Perfect for

- Students
- Data Science Beginners
- Python Learners
- Interview Preparation
- College Assignments

---

# 📂 Repository Structure

```
Pandas-Python-Important-Notes/
│
├── Dataset/
│   ├── employee.csv
│   ├── sales.csv
│   ├── student.csv
│
├── Images/
│
├── Jupyter Notebook/
│   └── Pandas_Important_Notes.ipynb
│
├── Python Files/
│   └── pandas_notes.py
│
├── Output/
│
├── README.md
│
└── requirements.txt
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Pandas-Python-Important-Notes.git
```

Move into the folder

```bash
cd Pandas-Python-Important-Notes
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# 📦 Requirements

```
pandas
numpy
matplotlib
openpyxl
```

Install manually

```bash
pip install pandas numpy matplotlib openpyxl
```

---

# 📚 Topics Covered

## 📌 Pandas Basics

- Import Pandas
- Series
- DataFrame
- Read CSV
- Read Excel
- Save CSV
- Save Excel

---

## 📌 Data Inspection

- head()
- tail()
- sample()
- info()
- describe()
- shape
- size
- columns
- index
- dtypes
- values

---

## 📌 Selecting Data

- loc[]
- iloc[]
- at[]
- iat[]
- Boolean Indexing
- Filtering

---

## 📌 Missing Values

- isnull()
- notnull()
- fillna()
- dropna()

---

## 📌 Duplicate Values

- duplicated()
- drop_duplicates()

---

## 📌 Sorting

- sort_values()
- sort_index()

---

## 📌 Renaming

- rename()

---

## 📌 Data Type Conversion

- astype()
- to_numeric()

---

## 📌 Column Operations

- insert()
- pop()
- drop()
- assign()

---

## 📌 String Functions

- str.upper()
- str.lower()
- str.title()
- str.replace()
- str.contains()

---

## 📌 Mathematical Operations

- sum()
- mean()
- median()
- mode()
- min()
- max()
- std()
- var()

---

## 📌 Grouping

- groupby()
- agg()
- transform()

---

## 📌 Merge Operations

- merge()
- join()
- concat()

---

## 📌 Apply Functions

- apply()
- applymap()
- map()

---

## 📌 Conditional Operations

- where()
- mask()
- np.where()

---

## 📌 File Operations

- read_csv()
- to_csv()
- read_excel()
- to_excel()

---

## 📌 Indexing

- set_index()
- reset_index()

---

## 📌 Advanced Functions

- pivot_table()
- crosstab()
- value_counts()
- unique()
- nunique()

---

# 🔥 Most Important Pandas Methods

| Method | Description |
|---------|-------------|
| head() | First rows |
| tail() | Last rows |
| info() | Dataset information |
| describe() | Statistics |
| shape | Rows & Columns |
| columns | Column names |
| dtypes | Data types |
| isnull() | Missing values |
| fillna() | Fill missing values |
| dropna() | Remove null values |
| duplicated() | Check duplicates |
| drop_duplicates() | Remove duplicates |
| rename() | Rename columns |
| astype() | Change datatype |
| replace() | Replace values |
| sort_values() | Sort data |
| groupby() | Group data |
| merge() | Merge datasets |
| concat() | Combine datasets |
| pivot_table() | Pivot tables |
| apply() | Apply function |
| map() | Mapping |
| value_counts() | Count values |

---

# 💻 Example

```python
import pandas as pd

df = pd.read_csv("employee.csv")

print(df.head())

print(df.info())

print(df.describe())
```

---

# 📊 Sample Output

```
   ID   Name   Age   Salary
0   1   John    24   35000
1   2   David   28   42000
2   3   Alice   31   52000
```

---

# 🎯 Learning Roadmap

✔ Python Basics

⬇

✔ NumPy

⬇

✔ Pandas

⬇

✔ Data Cleaning

⬇

✔ Data Analysis

⬇

✔ Data Visualization

⬇

✔ Machine Learning

---

# 🛠 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code

---

# 🎓 Who Can Use This Repository?

- College Students
- Beginners
- Data Analysts
- Data Science Learners
- Python Developers
- Interview Preparation

---

# ⭐ Features

- Easy to Understand
- Well Structured
- Beginner Friendly
- Practical Examples
- Interview Questions
- Real-world Dataset Practice
- Step-by-Step Explanation

---

# 🤝 Contribution

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```
git checkout -b feature-name
```

3. Commit changes

```
git commit -m "Added new examples"
```

4. Push

```
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Spandan Parhi**

Python | Data Science | AI | Machine Learning Enthusiast

---

# 🌟 Support

If you found this repository useful,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

Happy Coding! 🚀
