
# Assignment 1 – Data Analysis Using NumPy and Pandas

## Project Overview

This project focuses on performing data analysis using **NumPy and Pandas**, two essential Python libraries widely used in Data Science.

The assignment demonstrates numerical computations, data manipulation, indexing, slicing, filtering, and aggregation techniques using real-world temperature and transaction datasets.

## Objectives

- Work with NumPy arrays for numerical computations.
- Create and manipulate Pandas Series and DataFrames.
- Perform indexing and slicing operations.
- Apply conditional filtering using Boolean masks.
- Analyze temperature data using NumPy.
- Explore and manipulate transaction datasets using Pandas.
- Perform statistical calculations and data aggregation.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** NumPy, Pandas
- **Development Environment:** Jupyter Notebook / Google Colab
- **Version Control:** Git and GitHub

## Assignment Tasks

### 1. NumPy Array Operations

The NumPy section focuses on analyzing daily average temperatures recorded over two weeks.

**Topics Covered:**

- Creating 1D NumPy arrays.
- Inspecting array properties:
  - Shape
  - Data type
  - Number of elements
- Converting Celsius temperatures into Fahrenheit.
- Calculating maximum, minimum, and mean temperatures.
- Array indexing and slicing.
- Extracting the first three days, weekends, and middle three days.
- Creating and manipulating 2D NumPy arrays.
- Extracting weekly and weekend temperature data.

### 2. Pandas Series

The Pandas Series section uses student marks with custom ranking indices.

**Topics Covered:**

- Creating Pandas Series.
- Assigning custom indices.
- Integer-based indexing.
- Label-based indexing using `loc`.
- Position-based indexing using `iloc`.
- Boolean masking and filtering.
- Updating Series values.
- Removing elements using `drop()`.
- Performing mathematical operations to calculate CGPA.

### 3. Pandas DataFrame

The DataFrame section focuses on analyzing a sample retail transaction dataset.

**Dataset Information:**

The dataset contains 10 transactions with the following columns:

| Column | Description |
|---|---|
| TransactionID | Unique transaction identifier |
| ProductCategory | Category of purchased products |
| Region | Transaction region |
| Amount | Transaction amount |

**Topics Covered:**

- Creating Pandas DataFrames.
- Exploring datasets using `head()` and `tail()`.
- Inspecting shape, columns, and data types.
- Selecting specific columns.
- Accessing rows and columns using `iloc`.
- Filtering transactions using multiple conditions.
- Counting product categories using `value_counts()`.
- Finding unique regions using `unique()`.
- Calculating regional averages using `groupby()`.
- Updating transaction amounts.
- Creating a discount column.
- Removing records and columns.

## Python Libraries

Install the required libraries using:

```bash
pip install numpy pandas
```

Import the libraries:

```python
import numpy as np
import pandas as pd
```

## Key Learning Outcomes

Through this assignment, I gained practical experience in:

- Understanding NumPy arrays and numerical operations.
- Working with one-dimensional and two-dimensional arrays.
- Understanding Pandas Series and DataFrames.
- Performing data selection, indexing, and slicing.
- Applying conditional filtering techniques.
- Exploring and manipulating structured datasets.
- Performing basic statistical analysis and aggregation.

## Conclusion

This assignment provided hands-on experience with NumPy and Pandas, strengthening my understanding of Python-based data analysis.

It also helped me develop foundational skills in data manipulation, numerical computation, and exploratory data analysis (EDA), which are essential for progressing towards a career in Data Science.

---

**Author:** A Kameshraj

**Project:** NumPy and Pandas – Assignment 1
