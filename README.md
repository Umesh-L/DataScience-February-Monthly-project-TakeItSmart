# February Monthly Projects - Take It Smart Internship

This repository contains my February internship projects completed at Take It Smart.

## Projects Included

1. Student Career Path and Placement Analytics
2. Student Performance Analysis

Both projects focus on data cleaning, exploratory data analysis (EDA), and model building using Python in Jupyter Notebooks.

---

## 1) Student Career Path and Placement Analytics

### Objective
Analyze student academic and career-preparation attributes, identify placement drivers, and compare classification models for placement prediction.

### Main Notebook
- `Student_Career_Path_&_Placement_Analytics/Student_Career_Path_&_Placement_Analytics.ipynb`

### Dataset and Files
- Input dataset: `Student_Career_Path_&_Placement_Analytics/CSV files/Input csv file/Placement_Data_Final.csv`
- Output dataset (cleaned/renamed columns): `Student_Career_Path_&_Placement_Analytics/CSV files/Output csv files/Placement_Analysis_Results.csv`
- Model summary: `Student_Career_Path_&_Placement_Analytics/CSV files/Output csv files/Model_Performance_Summary.csv`
- Excel comparison files:
  - `Student_Career_Path_&_Placement_Analytics/CSV files/Excel data comparison files/Internships vs Placement_Status.csv`
  - `Student_Career_Path_&_Placement_Analytics/CSV files/Excel data comparison files/Aptitude_Score vs Placement_Status.csv`
  - `Student_Career_Path_&_Placement_Analytics/CSV files/Excel data comparison files/Placement_Training vs Placement_Status.csv`

### Data Snapshot
- Rows: 10,000
- Key columns include:
  - `CGPA`, `Internships`, `Projects`, `Workshops/Certifications`
  - `AptitudeTestScore`, `SoftSkillsRating`, `ExtracurricularActivities`
  - `PlacementTraining`, `SSC_Marks`, `HSC_Marks`, `PlacementStatus`
  - `Total_Academic_Score`

### Workflow Covered
- Environment setup and library imports
- Data loading and descriptive statistics
- Data cleaning:
  - missing value handling
  - duplicate removal
  - feature renaming for readability
- EDA:
  - univariate, bivariate, multivariate analysis
  - correlation heatmap
  - trends and placement driver interpretation
- Predictive modeling:
  - Logistic Regression
  - Decision Tree Classifier
  - confusion matrix and classification report

### Model Results
From `Model_Performance_Summary.csv`:
- Logistic Regression accuracy: **0.7945**
- Decision Tree accuracy: **0.7280**

### Screenshots
- ![Kaggle Source](Student_Career_Path_%26_Placement_Analytics/Screenshots%20of%20Dataset%20and%20Graphs/Placement%20Prediction%20Dataset%20from%20kaggle.png)
- ![Modified CSV Columns](Student_Career_Path_%26_Placement_Analytics/Screenshots%20of%20Dataset%20and%20Graphs/New%20csv%20file%20generated%20with%20modified%20names.png)
- ![Total Academic Score Formula](Student_Career_Path_%26_Placement_Analytics/Screenshots%20of%20Dataset%20and%20Graphs/Total_Academic_Score%20column%20formula.png)
- ![Internships vs Placement Status](Student_Career_Path_%26_Placement_Analytics/Screenshots%20of%20Dataset%20and%20Graphs/Internships%20vs%20Placement_Status.png)
- ![Aptitude Score vs Placement Status](Student_Career_Path_%26_Placement_Analytics/Screenshots%20of%20Dataset%20and%20Graphs/Aptitude_Score%20vs%20Placement_Status.png)
- ![Placement Training vs Placement Status](Student_Career_Path_%26_Placement_Analytics/Screenshots%20of%20Dataset%20and%20Graphs/Placement_Training%20vs%20Placement_Status.png)

### Video Explanation
- [Student Career Path and Placement Analysis Video](screen%20recordings/Student%20Carrer%20Path%20and%20Placement%20Analysis.mp4)

---

## 2) Student Performance Analysis

### Objective
Perform end-to-end analysis of student performance data and build models for both classification and score prediction.

### Main Notebook
- `Student Performance/Student_Performance.ipynb`

### Dataset
- `Student Performance/Input Dataset/student_performance.csv`

### Data Snapshot
- Rows: 1,000
- Includes columns such as:
  - `StudentID`, `Name`, `Gender`
  - `AttendanceRate`, `StudyHoursPerWeek`, `PreviousGrade`
  - `ExtracurricularActivities`, `ParentalSupport`, `FinalGrade`
  - `Study Hours`, `Attendance (%)`, `Online Classes Taken`

### Workflow Covered
- Data loading and initial inspection
- Data cleaning:
  - duplicate and missing-value handling
  - anomaly fixes for attendance and study-hour fields
  - removal of non-predictive columns
  - column normalization
- EDA:
  - univariate, bivariate, and multivariate visualizations
  - correlation analysis
- Modeling:
  - Multinomial Logistic Regression (classify `FinalGrade` into Low/Medium/High)
  - Linear Regression (predict continuous `FinalGrade`)

### Reported Metrics (from notebook outputs)
- Multinomial Logistic Regression accuracy: **0.3950**
- Linear Regression:
  - R-squared: **-0.0117**
  - MAE: **8.0279**
  - MSE: **90.8419**

### Video Explanation
- [Student Performance Analytics Video](screen%20recordings/Student%20Performance%20Analytics.mp4)

---

## Tech Stack
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- scikit-learn

## How To Run
1. Open the project in Jupyter Notebook or VS Code.
2. Run all cells in:
   - `Student_Career_Path_&_Placement_Analytics/Student_Career_Path_&_Placement_Analytics.ipynb`
   - `Student Performance/Student_Performance.ipynb`
3. Ensure datasets remain in their current folder paths to avoid file-not-found errors.

## Dataset Source Reference
- Kaggle: https://www.kaggle.com/datasets/ruchikakumbhar/placement-prediction-dataset?resource=download

## Internship Context
These projects were completed as part of my February monthly internship work at Take It Smart, focusing on practical analytics, model comparison, and insight generation from educational datasets.
