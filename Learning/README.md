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

# Pandas: Filtering, Sorting, and Grouping Data

This project demonstrates core data manipulation techniques in Pandas to ask and answer specific questions about a dataset. It builds on the data loading and cleaning skills covered in previous projects.

### Key Concepts Covered:

-   **Filtering:** Selecting a subset of data based on a condition using boolean indexing. This includes single and multiple conditions.
-   **Sorting:** Ordering a DataFrame by specific columns using `sort_values()` to find the highest or lowest values.
-   **Grouping:** Splitting data into groups and applying an aggregation function (like `sum()` or `mean()`) to each group using `groupby()`.
-   **Basic Visualization:** Creating simple bar and line plots to visualize the results of data analysis.

This notebook is a practical example of how to extract meaningful insights from a dataset.

### File

* [Data Filtering and Analysis](data_filtering_and_analysis.ipynb)
---

# Pandas: Data Manipulation and Feature Engineering

This project demonstrates professional-level data cleaning and manipulation techniques in the Pandas library. It builds on foundational skills by showing how to handle real-world data challenges.

### Key Concepts Covered:

-   **Handling Missing Data:** Using the `.fillna()` method to replace missing values and preserve data.
-   **Data Type Conversion:** Correcting data types with `.astype()` for proper analysis and efficient storage.
-   **Feature Engineering:** Creating new columns from existing data using mathematical operations and custom functions with the powerful `.apply()` method.

This notebook is a practical example of how to transform raw, messy data into a clean, usable dataset ready for deep analysis.


### File

* [Data Manipulation](Data_manipulation.ipynb)
---

# Pandas: Reshaping and Pivoting Data

This project demonstrates how to use the powerful `pivot_table()` function to summarize and reshape data in a Pandas DataFrame. It shows how to transform a long, detailed dataset into a clear, concise summary table.

### Key Concepts Covered:

-   **Data Reshaping:** Rearranging data from a "long" format (one row per observation) to a "wide" format (summarized table).
-   **Pivot Tables:** Using the `pivot_table()` function to aggregate and summarize data based on multiple categories.
-   **Aggregation Functions:** Specifying different types of aggregation (e.g., sum, mean, count) to analyze data in various ways.

This notebook is a key step in learning how to create insightful reports and dashboards from raw data.


### File

* [Data Pivoting](Data_pivoting.ipynb)
---
# Pandas: Data Merging and Analysis

This project serves as a capstone that demonstrates how to work with multiple datasets by merging them together. It combines skills from previous lessons to perform a complete analysis from start to finish.

### Key Concepts Covered:

-   **Data Merging:** Using the `pd.merge()` function to combine two separate DataFrames based on a common column.
-   **Multi-Source Analysis:** Performing a complete data analysis workflow on a combined dataset.
-   **Professional Workflow:** Simulating a real-world scenario where data is not available in a single, clean file.

This notebook is a great example of how to handle a common and crucial task in data science.

### File

* [Pandas Data Merging](pandas_data_merging.ipynb)

---
# Pandas: String Manipulation and Text Cleaning

This project demonstrates how to work with text data in Pandas using the powerful `.str` accessor. It covers key methods for cleaning and standardizing string columns, which is a crucial skill in data analysis.

### Key Concepts Covered:

-   **Standardizing Text:** Converting strings to a consistent case with `.str.lower()` and `.str.upper()`.
-   **Finding and Replacing:** Using `.str.replace()` to fix typos or standardize names.
-   **Filtering with Text:** Creating a filtered DataFrame based on a string's content using `.str.contains()`.

This notebook is a practical guide to handling and preparing messy text data for analysis.


### File

* [Pandas String Methods](Pandas_string_methods.ipynb)

---
# Pandas: Time-Series Analysis

This project demonstrates how to work with date and time data in Pandas, a crucial skill for analyzing trends and patterns over time. It shows how to convert a standard column into a special time-series object that's ready for analysis.

### Key Concepts Covered:

-   **Converting Data Types:** Using the `pd.to_datetime()` function to convert a column into a time-series data type.
-   **Extracting Time-Based Features:** Using the powerful `.dt` accessor to pull out information like the year, month,day name and day of the week, quarter, and if a year is a leap year with `.year`,`.month`,`.day_name()`,`.dayofweek`,`quarter`,`.is_leap_year`
-   **Time-Series Aggregation:** Grouping data by time-based categories (like day of the week) to find trends.

This notebook is a practical guide to handling and preparing messy text data for analysis.


### Data Source

-   [Walmart Sales Dataset](https://www.kaggle.com/datasets/manjeetsingh/walmart-sales-dataset-forecasting)


### File

* [Pandas Time-Series Analysis](pandas_time_series.ipynb)
---
