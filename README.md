# Pandas Introduction
Pandas is a powerful and open-source Python library. The Pandas library is used for data manipulation and analysis. Pandas consist of data structures and functions to perform efficient operations on data.
Pandas is well-suited for working with tabular data, such as spreadsheets or SQL tables.

## What is Python Pandas used for?
The Pandas library is generally used for data science, but have you wondered why? This is because the Pandas library is used in conjunction with other libraries that are used for data science. It is built on top of the NumPy library which means that a lot of the structures of NumPy are used or replicated in Pandas.
The data produced by Pandas is often used as input for plotting functions in Matplotlib, statistical analysis in SciPy, and machine learning algorithms in Scikit-learn.
Here is a list of things that we can do using Pandas.
* Data set cleaning, merging, and joining.
* Easy handling of missing data (represented as NaN) in floating point as well as non-floating point data.
* Columns can be inserted and deleted from DataFrame and higher-dimensional objects.
* Powerful group by functionality for performing split-apply-combine operations on data sets.
* Data Visualization.

# Getting Started with Pandas
## Installing Pandas
The first step in working with Pandas is to ensure whether it is installed in the system or not.  If not, then we need to install it on our system using the pip command.

```bash
    pip install pandas
```

## Importing Pandas
After the Pandas have been installed in the system, we need to import the library. This module is generally imported as follows:

```bash
    import pandas as pd
```
Here, pd is referred to as an alias for the Pandas. However, it is not necessary to import the library using the alias, it just helps in writing less code every time a method or property is called. 


# Data Structures in Pandas Library
Pandas generally provide two data structures for manipulating data. They are:
* Series
* DataFrame

## Pandas Series
A Pandas Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, Python objects, etc.). The axis labels are collectively called indexes.

### How to Create a Series ?
Pandas Series is created by loading the datasets from existing storage (which can be a SQL database, a CSV file, or an Excel file).
Pandas Series can be created from lists, dictionaries, scalar values, etc.

## Pandas DataFrame
Pandas DataFrame is a two-dimensional data structure with labeled axes (rows and columns).

### Creating DataFrame
Pandas DataFrame is created by loading the datasets from existing storage (which can be a SQL database, a CSV file, or an Excel file).
Pandas DataFrame can be created from lists, dictionaries, a list of dictionaries, etc.

