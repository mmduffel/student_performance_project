# Source Code
 
This folder contains the Google Colab notebooks used to clean, prepare, analyze, and visualize the student performance dataset.
 
## Files
 
- `src_clean_student_performance_data.ipynb` – Contains the Python code used to review, validate, and prepare the raw student performance dataset.
- `src_student_performance_data_analyze.ipynb` – Contains the Python code used to analyze the cleaned student performance dataset, create and save the required visualizations, and produce the final analyzed dataset.
 
## Data Cleaning
 
The data cleaning notebook includes:
 
- Reviewing the dataset dimensions, column names, and data types
- Checking for missing values
- Checking for duplicate rows
- Reviewing summary statistics
- Reviewing unique values in categorical variables
- Checking the range of math, reading, and writing scores
- Checking for test scores outside the valid 0–100 range
- Checking categorical variables for extra whitespace
- Creating a copy of the dataset for preprocessing
- Verifying the cleaned dataset
- Saving the cleaned dataset as `students_performance_clean.csv`
 
## Data Analysis and Visualizations
 
The data analysis notebook includes:
 
- Reshaping math and reading scores for comparison by gender
- Creating and saving boxplots comparing math and reading scores by gender
- Calculating average math scores by test preparation course
- Creating and saving a bar graph comparing average math scores by test preparation course
- Calculating each student's overall average across math, reading, and writing scores
- Creating and saving a bar graph comparing mean overall performance by lunch type
- Calculating correlations among math, reading, and writing scores
- Creating and saving a correlation heatmap for the three subject scores
- Creating and saving a scatter plot with trend lines comparing math and reading scores by test preparation course
- Saving the final analyzed dataset as `student_performance_analyzed.csv`
 
## Visualization Outputs
 
The analysis notebook creates the following visualization files:
 
- `V1_gender_boxplots.png`
- `V2_test_prep_math.png`
- `V3_lunch_performance.png`
- `V4_subject_correlations.png`
- `V5_math_reading_test_prep.png`
 
The final visualization files are stored in the `results` folder.
 
## Tools and Libraries
 
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
 
## Purpose
 
The cleaning and analysis processes are stored in separate Google Colab notebooks to keep each stage of the student performance project organized and clearly documented. The analysis notebook generates the final dataset and visualization outputs stored in the `results` folder.
