# Cleaned Data
 
This folder contains the cleaned and prepared student performance dataset used for analysis.
 
## File
 
- `students_performance_clean.csv` – Cleaned version of the original student performance dataset.
 
## Data Cleaning
 
The raw student performance dataset was uploaded into Google Colab and reviewed and prepared for analysis by:
 
- Reviewing the dataset dimensions, column names, and data types
- Checking for missing values
- Checking for duplicate rows
- Reviewing summary statistics
- Reviewing unique values in categorical variables
- Checking the range of math, reading, and writing scores
- Checking for test scores outside the valid 0–100 range
- Checking categorical variables for extra whitespace
- Creating a copy of the raw dataset for preprocessing
- Verifying the cleaned dataset before saving
 
## Data Quality
 
The dataset contained no missing values or duplicate rows. The test scores were checked to ensure they were within the valid 0–100 range.
 
## Purpose
 
The original dataset is preserved in the `data_raw` folder. The prepared dataset was saved as `students_performance_clean.csv` and is used for the analysis and visualizations in the student performance project.
