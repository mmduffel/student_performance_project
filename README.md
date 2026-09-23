# student_performance_project
 
## Project Overview
 
This project analyzes student performance data using Python in Google Colab. The project includes data quality checks, data preparation, exploratory data analysis, and visualizations examining factors related to student scores in math, reading, and writing.
 
## Project Structure
 
### `data_raw/`
 
Contains the original student performance dataset before data cleaning or preprocessing.
 
- `raw_students_performance_data.csv` – Original dataset used for the project.
 
### `data_clean/`
 
Contains the cleaned and prepared student performance dataset.
 
- `students_performance_clean.csv` – Cleaned version of the original dataset used for analysis.
 
### `results/`
 
Contains the final outputs from the student performance analysis.
 
- `student_performance_analyzed.csv` – Final analyzed dataset, including the overall average score created during the analysis.
- `MMD_ResultsFolders_Student Performance Dataset.pdf` – Contains the written answers and interpretations for the data visualization questions.
- `V1_gender_boxplots.png` – Compares math and reading scores by gender.
- `V2_test_prep_math.png` – Compares average math scores by test preparation course.
- `V3_lunch_performance.png` – Compares mean overall performance by lunch type.
- `V4_subject_correlations.png` – Shows correlations among math, reading, and writing scores.
- `V5_math_reading_test_prep.png` – Shows the relationship between math and reading scores by test preparation course.

### `src/`
 
Contains the Google Colab notebooks used to clean and analyze the dataset.
 
- `src_clean_student_performance_data.ipynb` – Contains the data review, validation, and preparation process.
- `src_student_performance_data_analyze.ipynb` – Contains the data analysis, visualization code, and commands used to save the final outputs.
 
## Data Preparation
 
The dataset was reviewed and prepared by:
 
- Reviewing the dataset dimensions, columns, and data types
- Checking for missing values
- Checking for duplicate rows
- Reviewing summary statistics
- Examining the unique values in categorical variables
- Checking math, reading, and writing score ranges
- Checking for scores outside the valid 0–100 range
- Checking categorical variables for extra whitespace
- Creating and verifying a copy of the dataset for analysis
 
The dataset contained no missing values or duplicate rows, and its original dimensions remained 1,000 rows and 8 columns.
 
## Data Analysis and Visualizations
 
The analysis addresses the following questions:
 
1. Are there gender differences in math and reading scores?
2. Do students who completed the test preparation course score higher in math?
3. Does lunch type relate to overall student performance?
4. How strongly do math, reading, and writing scores move together?
5. How strongly are math and reading scores associated, and does the relationship differ based on test preparation course completion?
 
The analysis also creates an `overall_avg` variable using each student’s math, reading, and writing scores.
 
## Tools and Libraries
 
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- GitHub
