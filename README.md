# Task 5 – Data Cleaning with Python (Pandas)

## Project Overview
This project demonstrates basic data cleaning and preprocessing using Python and Pandas on the Titanic dataset.  
The objective of the task was to show understanding of loading data, inspecting structure, handling missing values, performing simple transformations, and exporting a cleaned dataset.

---

## Tools and Libraries Used
- Python  
- Google Colab  
- Pandas  
- NumPy  

---

## Dataset
- Titanic Dataset (CSV format)

---

## Tasks Performed
- Loaded the dataset using `pandas.read_csv()`
- Explored the dataset using `head()` and `info()`
- Identified missing values using `isnull().sum()`
- Handled missing values:
  - Filled missing values in the Age column using median
  - Filled missing values in the Embarked column using mode
  - Dropped the Cabin column due to a large number of missing values
- Removed duplicate rows using `drop_duplicates()`
- Converted the datatype of the Survived column to categorical
- Created a new feature called FamilySize using SibSp and Parch
- Exported the cleaned dataset to `cleaned_data.csv`

---

## Files added
- Task5_Cleaning.ipynb – Jupyter notebook containing the code and explanations  
- cleaned_data.csv – Final cleaned dataset  
- README.md – Project documentation  



