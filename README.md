# Predicting Diabetes in Patients<br>

Dataset: NHANES glycohemoglobin data (https://hbiostat.org/data)<br>
Data Dictionary: https://hbiostat.org/data/repo/nhgh

## Problem Statement
Develop and optimize 3 machine learning models (logistic regression, decision tree and random forest) to predict those who have diabetes (gh >= 6.5%) using Python in a Jupyter notebook. Thereafter, please interpret and compare the fine-tuned models.

## Table of Contents
### [Part 1 - Source Data Import (into SQLite3), Cleaning, and Transformation](./assessment/Part%201%20-%20Source%20Data%20Import%20(into%20SQLite3)%2C%20Cleaning%2C%20and%20Transformation.ipynb)

This notebook covers the initial steps of the data science pipeline. It includes the import of source data into a SQLite3 database, followed by data cleaning and transformation processes to prepare the data for further analysis.

### [Part 2 - Exploratory Data Analysis and Feature Engineering/Selection](./assessment/Part%202%20-%20Exploratory%20Data%20Analysis%20and%20Feature%20Engineering_Selection.ipynb)

In this notebook, exploratory data analysis was performed to understand the underlying patterns and relationships within the data. This is followed by feature engineering and selection processes to identify the most relevant features for our predictive model.

### [Part 3 - Modelling](./assessment/Part%203%20-%20Modelling.ipynb)

The final notebook in this series focuses on building a predictive model based on the features selected in the previous notebook. It includes the process of model training, validation, and evaluation of 3 models, namely, logistic regression, decision tree and random forest.

## Prerequisites

### Python Libraries

This project requires Python and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [sqlite3](https://docs.python.org/3/library/sqlite3.html)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

### Specifications:<br>
This code was run on a Windows 10 machine. Please note that code might break when run on a Linux/MacOS machine (due to SQLite3 folder path convention). The time taken to execute the code will differ machine-to-machine depending on the specifications. Please refer to the list below for comparison.

CPU: AMD Ryzen 9 3950X 16-Core Processor 3.49 GHz<br>
RAM: 64 GB Crucial 3200MHz CL16<br>
GPU: NVIDIA RTX3080Ti<br>
Storage: ADATA SX8200 1TB NVME Gen 3<br>
