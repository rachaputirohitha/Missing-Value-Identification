# Task 12 – Missing Value Identification

##  Project Overview

This project focuses on identifying and analyzing missing values in the Titanic dataset using Excel and Python (Pandas).

The objective is to identify missing data, calculate the number and percentage of missing values in each column, summarize the findings, and visualize the missing values.

##  Dataset

**Dataset:** Titanic Dataset

- Total Records: 891
- Total Columns: 15
- File: `titanic(1).csv`

##  Tools Used

- Microsoft Excel
- Python
- Pandas
- Matplotlib
- Google Colab

##  Tasks Performed

## 1. Missing Value Identification

Missing values were identified using Excel and Pandas.

Python formula:

df.isnull().sum()

##  Missing Value Summary

The missing values were identified and summarized using Excel and Pandas.

| Column | Missing Values | Missing % |
|---|---:|---:|
| deck | 688 | 77.22% |
| age | 177 | 19.87% |
| embarked | 2 | 0.22% |
| embark_town | 2 | 0.22% |
| Other Columns | 0 | 0.00% |

The `deck` column contains the highest number of missing values, followed by `age`.

##  Visualization

A bar chart was created using Python and Matplotlib to visualize the number of missing values in each column.

The visualization shows that:

- `deck` has 688 missing values.
- `age` has 177 missing values.
- `embarked` has 2 missing values.
- `embark_town` has 2 missing values.

##  Key Findings

1. The Titanic dataset contains 891 records and 15 columns.
2. The `deck` column has the highest missing-value percentage at 77.22%.
3. The `age` column has 177 missing values, representing 19.87% of the dataset.
4. `embarked` and `embark_town` each have 2 missing values.
5. The remaining columns contain no missing values.
6. Missing values should be handled appropriately rather than removed without justification.

## Screenshots
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/036df757-10d4-40f7-9397-5a92db2d9611" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/41f49d18-9b45-4ab4-89c7-468f29ac5a1f" />


