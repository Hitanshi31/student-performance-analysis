# Student Performance Analysis and Predictive Modeling

## Project Overview

This project analyzes the relationship between attendance, early-term grades (G1, G2), and final student performance (G3).

The objectives are to:
- Identify key factors influencing final grades
- Examine statistical relationships between academic indicators
- Build predictive models to estimate final performance

The project progresses from exploratory data analysis (EDA) to supervised machine learning.

---

## Dataset Description

- Dataset: Student Performance Dataset  
- Observations: 395 students  
- Features: Academic, behavioral, and attendance-related attributes  
- Target Variable: G3 (Final Grade)  

Grades range from 0 to 20.

---

## Methodology

### 1. Data Understanding
- Dataset structure and dimensional analysis
- Missing value verification
- Duplicate record check

### 2. Feature Engineering
- `average_grade` – Measures overall academic consistency
- `performance_trend` – Captures improvement or decline from G1 to G3
- `attendance_level` – Categorizes attendance into structured groups

### 3. Exploratory Data Analysis
- Distribution analysis of grades
- Correlation matrix visualization
- Scatter plots with regression lines
- Statistical validation using Pearson correlation tests

### 4. Predictive Modeling

Models implemented:
- Linear Regression
- Ridge Regression (L2 Regularization)

Evaluation Metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Results

- Second-term grade (G2) is the strongest predictor of final performance.
- Attendance shows a negative correlation with final grades.
- Academic performance demonstrates strong consistency across terms.
- Linear Regression achieved:
  - MAE ≈ 1.3
  - R² ≈ 0.79

Approximately 79% of the variance in final grades is explained by early-term grades and attendance.

Ridge regression produced comparable results, indicating minimal overfitting and model stability.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## How to Run the Project

1. Clone the repository:
   ```
   git clone <repository-link>
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```
   jupyter notebook
   ```

---

## Conclusion

This project demonstrates a structured analytical pipeline:

Data Cleaning → Feature Engineering → Statistical Analysis → Predictive Modeling → Model Evaluation

It highlights how early academic indicators can effectively predict final student outcomes using linear modeling techniques.
