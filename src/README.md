# Source Code
 
This folder contains the Google Colab notebooks used to clean, prepare, analyze, and visualize the student performance dataset.
 
## Files
 
- `src_clean_student_performance_data.ipynb` – Contains the Python code used to review, validate, and prepare the raw student performance dataset.
- `src_student_performance_data_analyze.ipynb` – Contains the Python code used to analyze the cleaned dataset, create the required visualizations, and save the final analyzed dataset.
 
## Data Cleaning
 
The data cleaning notebook includes:
 
- Reviewing the dataset dimensions, column names, and data types
- Checking for missing values
- Checking for duplicate rows
- Reviewing summary statistics
- Reviewing unique values in the categorical variables
- Checking the range of math, reading, and writing scores
- Checking for test scores outside the valid 0–100 range
- Checking categorical variables for extra whitespace
- Creating a copy of the dataset for preprocessing
- Verifying the cleaned dataset
- Saving the cleaned dataset as `students_performance_clean.csv`
 
## Data Analysis and Visualizations
 
The analysis notebook includes:
 
- Reshaping math and reading scores for comparison by gender
- Creating boxplots to compare math and reading scores by gender
- Calculating average math scores by test preparation course
- Creating a bar graph to examine the impact of test preparation on math scores
- Calculating each student’s average score across math, reading, and writing
- Creating a bar graph to compare mean overall performance by lunch type
- Calculating correlations among math, reading, and writing scores
- Creating a heatmap of the subject-score correlations
- Creating a scatter plot with trend lines to examine the relationship between math and reading scores by test preparation group
- Saving the final analyzed dataset as `student_performance_analyzed.csv`
 
## Tools and Libraries
 
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
 
## Purpose
 
The cleaning and analysis processes are stored in separate Google Colab notebooks to keep each stage of the student performance project organized and clearly documented.
