# 📘 Pandas

## 1. What is Pandas?

**Pandas** is an **open-source Python library** used to **read, organize, clean, analyze, and manipulate data**.

It is one of the most popular libraries used in **Machine Learning** and **Data Analysis**.

### Common Uses

- 📄 Read CSV and Excel files
- 🔍 Filter data
- 📊 Sort data
- 🧹 Clean missing values
- 📈 Analyze data
- 🤖 Prepare datasets for Machine Learning

---

# 2. Import Pandas

```python
import pandas as pd
```

Here,

- **pandas** → Library name
- **pd** → Alias (short name used for convenience)

---

# 3. Data Structures in Pandas

Pandas mainly provides **two data structures**:

## A. Series

A **Series** is a **one-dimensional (1D) array**.

It contains a **single column of data**.

### Example

```python
import pandas as pd

marks = pd.Series([90, 86, 98])

print(marks)
```

### Output

```text
0    90
1    86
2    98
dtype: int64
```

---

## B. DataFrame

A **DataFrame** is a **two-dimensional (2D) table**.

It consists of **rows and columns**, just like an Excel sheet or database table.

It is the **most commonly used data structure** in Machine Learning.

### Example

```python
data = {
    "Name": ["A", "B"],
    "Marks": [80, 90]
}

df = pd.DataFrame(data)

print(df)
```

### Output

```text
  Name  Marks
0    A     80
1    B     90
```

---

# 4. Read a Dataset

## Read a CSV File

```python
df = pd.read_csv("student.csv")
```

## Read an Excel File

```python
df = pd.read_excel("student.xlsx")
```

---

# 5. View Data

## Display the First 5 Rows

```python
df.head()
```

---

## Display the First 10 Rows

```python
df.head(10)
```

---

## Display the Last 5 Rows

```python
df.tail()
```

---

# 6. Basic Functions

## Get Dataset Shape

```python
df.shape
```

Returns:

```text
(Rows, Columns)
```

### Example

```text
(1000, 5)
```

- **1000** → Number of Rows
- **5** → Number of Columns

---

## Show Column Names

```python
df.columns
```

Displays all column names.

---

## Dataset Information

```python
df.info()
```

Shows:

- Column names
- Data types
- Missing values
- Number of rows

---

## Statistical Summary

```python
df.describe()
```

Shows statistics such as:

- Count
- Mean
- Standard Deviation (Std)
- Minimum
- Maximum
- Quartiles

---

# 7. Select Data

## Select a Single Column

```python
df["Marks"]
```

---

## Select Multiple Columns

```python
df[["Name", "Marks"]]
```

---

# 8. Filter Data

## Example: Display Students with Marks Greater Than 80

```python
df[df["Marks"] > 80]
```

---

# 9. Sort Data

## Ascending Order

```python
df.sort_values("Marks")
```

---

## Descending Order

```python
df.sort_values("Marks", ascending=False)
```

---

# 10. Handle Missing Values

## Check Missing Values

```python
df.isnull()
```

---

## Count Missing Values

```python
df.isnull().sum()
```

---

## Remove Missing Values

```python
df.dropna()
```

---

## Fill Missing Values

```python
df.fillna(0)
```

---

# 11. Important Functions

| Function | Code |
|----------|------|
| Average | `df["Marks"].mean()` |
| Maximum | `df["Marks"].max()` |
| Minimum | `df["Marks"].min()` |
| Sum | `df["Marks"].sum()` |
| Count | `df["Marks"].count()` |
| Unique Values | `df["Grade"].unique()` |

---

# 12. Save Data

## Save as CSV

```python
df.to_csv("new.csv")
```

---

## Save as Excel

```python
df.to_excel("new.xlsx")
```

---

# 13. Machine Learning Workflow

```text
Dataset
   │
   ▼
Read Data using Pandas
   │
   ▼
Read CSV / Excel File
   │
   ▼
Clean the Data
   │
   ▼
Analyze the Data
   │
   ▼
Train the Machine Learning Model
   │
   ▼
Make Predictions
```

---

# 🎯 Summary

- **Pandas** is an open-source Python library for data manipulation and analysis.
- The two main data structures are **Series** and **DataFrame**.
- Pandas helps you read datasets, clean data, analyze information, and prepare data for Machine Learning.
- It is one of the most essential libraries every Data Scientist and Machine Learning Engineer should know.