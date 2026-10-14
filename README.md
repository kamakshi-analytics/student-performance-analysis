# Student Performance Analysis

## Project Overview

This project analyzes student performance using Python to explore the relationships between study hours, attendance, previous scores, and final scores. The goal is to identify patterns in the data and communicate meaningful insights through statistical analysis and visualizations.

## Objectives

- Explore and understand the student performance dataset.
- Perform data quality checks and descriptive statistical analysis.
- Analyze relationships between study hours, attendance, previous scores, and final scores.
- Create visualizations to communicate key findings.
- Summarize insights, limitations, and conclusions.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset Description

The dataset contains 15 student records and five columns.

| Column | Description |
|---|---|
| `Student_ID` | Unique student identifier |
| `Study_Hours` | Hours spent studying |
| `Attendance` | Student attendance percentage |
| `Previous_Score` | Score obtained previously |
| `Final_Score` | Final examination score |

## Analysis Performed

- Inspected the dataset structure, column names, and data types.
- Checked for missing values and duplicate rows.
- Calculated descriptive statistics, including mean, median, standard deviation, and quartiles.
- Explored the distribution of student scores.
- Examined correlations among study hours, attendance, previous scores, and final scores.
- Created visualizations to communicate patterns in student performance.

## Key Findings

- Average study time was 4.4 hours.
- Average attendance was approximately 78.27%.
- Average final score was approximately 68.87.
- Previous scores showed a very strong positive correlation with final scores (r ≈ 0.997).
- Attendance (r ≈ 0.992) and study hours (r ≈ 0.984) also showed very strong positive correlations with final scores.

These findings describe relationships observed in this dataset and do not establish that any single factor caused higher final scores.

## Limitations

- The dataset contains only 15 student records, limiting the generalizability of the findings.
- Correlation does not imply causation.
- The high correlation values should be interpreted cautiously and validated using a larger, independently collected dataset.

## Conclusion

The analysis identified strong positive relationships between previous scores, attendance, study hours, and final scores within this dataset. Previous scores had the strongest observed correlation with final scores. Further analysis using a larger dataset is needed to assess whether these patterns generalize to other student populations.

## Files in This Repository

- `student_performance_analysis.ipynb` — Jupyter Notebook containing the Python code, data analysis, and visualizations.
- `student_performance_csv (1).xlsx` — Excel dataset used in the analysis.

## How to Run the Project

1. Download or clone this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```

4. Open the notebook in Jupyter Notebook or JupyterLab.
5. Run the notebook cells in order.

## Author

**Kamakshi Kanike** — Aspiring Junior Data Analyst

[GitHub Profile](https://github.com/kamakshi-analytics)

