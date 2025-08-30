## My Pandas Learning Journey
This repository documents my progress in learning the pandas library for data analysis in Python. It includes code and projects ranging from basic Series and DataFrame creation to more advanced data manipulation techniques.

# Pandas Series Introduction

This project demonstrates the basics of creating a Pandas Series. A Series is a one-dimensional array-like object that can hold various data types.

The first task shows how to create a basic Series with a default numeric index. The second task highlights the importance of using a **custom index**, which makes the data more readable and meaningful by providing descriptive labels instead of generic numbers.

### Projects

* [Pandas Series Basics](pandas_series_basics.ipynb)

---


# Pandas DataFrames: Creation and Selection

This project focuses on the core concepts of the Pandas DataFrame, a two-dimensional data structure that's essential for data analysis in Python.

It demonstrates how to:
- Create a DataFrame from a Python dictionary.
- Select a single column, which returns a Pandas Series.
- Select a specific row by its index using the `.loc` accessor.
- Select multiple columns at once, which returns a new DataFrame.

This project is a key step in understanding how to access and manipulate data in Pandas.

### Projects

* [DataFrame Basics](DataFrame_basics.ipynb)

---

# Pandas: Data Loading, Cleaning, and Exploration

This project documents the essential first steps of a data analysis workflow using the Pandas library in Python. It uses a real-world dataset of video game sales to demonstrate key skills.

### Key Concepts Covered:

-   **Data Loading:** How to load data from an external CSV file into a Pandas DataFrame using `pd.read_csv()`.
-   **Initial Inspection:** Using `.head()` and `.info()` to get a quick overview of the data's structure, data types, and missing values.
-   **Data Cleaning:** Handling missing data by dropping rows with `dropna()` to prepare the dataset for analysis.
-   **Basic Exploration:** Generating summary statistics of numerical data with `.describe()` and analyzing the distribution of categorical data with `.value_counts()`.

This notebook serves as a practical example of how to begin any data-driven project.

### Data Source

-   [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)

### Project

* [Video Game Sales Analysis](data_cleaning_and_exploration.ipynb)

---
