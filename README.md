# Airbnb Data Cleaning with Pandas
Project Overview

This project demonstrates a complete data cleaning workflow using Python and Pandas on an Airbnb dataset. The goal is to transform raw data into a clean and analysis-ready dataset by handling missing values, duplicates, inconsistent formatting, and data type issues.

Technologies Used
Python
Pandas
NumPy
Jupyter Notebook
Data Cleaning Tasks Performed
Removed redundant and unnecessary columns
Renamed columns for better readability
Removed duplicate records
Handled missing (NaN) values
Cleaned text-based columns
Converted data types where required
Transformed boolean values into numeric format
Standardized column names
Verified data quality and consistency
Example Transformations
Boolean to Numeric
Python
1
df['instant_bookable'] = df['instant_bookable'].astype(int)
Show more lines

Output:

True → 1
False → 0
Remove Duplicates
Python
1
df.drop_duplicates(inplace=True)
Show more lines
Handle Missing Values
Python
1
df.dropna(inplace=True)
Show more lines
Project Structure
Plain Text
1
Airbnb-Data-Cleaning/
2
│
3
├── Airbnb_Data_Cleaning.ipynb
4
├── README.md
5
├── dataset.csv
6
└── cleaned_dataset.csv
Show more lines
Key Learning Outcomes
Data preprocessing with Pandas
Data quality assessment
Handling missing and duplicate data
Data transformation techniques
Preparing datasets for analysis and machine learning
Results

The final dataset is cleaner, more consistent, and ready for exploratory data analysis, visualization, and machine learning applications.

Author

Abdul Rehman

Desktop Support Analyst | AI & Machine Learning Enthusiast

GitHub: https://github.com/AbdulR0001
