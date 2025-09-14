# DataMining-Project


## Project Description

Our project focuses on exploring and understanding university students’ anxiety.  
It highlights the problem of student anxiety and its potential impact on academic performance,  
and applies data analysis to uncover meaningful patterns in the dataset.

## Project Motivation

University students today face unprecedented levels of psychological pressure due to academic workloads, social expectations, and financial stress. Anxiety, in particular, has become one of the most critical mental health challenges, often going unnoticed until it severely impacts performance and well-being. We chose this topic because identifying anxiety at an early stage can empower universities to provide timely support, reduce dropout risks, and promote healthier learning environments. By leveraging real student data and applying modern data science techniques, our project aims to transform raw survey responses into actionable insights that can help educators, counselors, and policy makers build a more supportive academic community.


## Dataset Description
- **Rows × Columns:** 2028 × 16  
- **Key attributes:**  
  Age, Gender, University, Department, Academic Year, Current CGPA,  
  (GAD-7 items) Q1–Q7 related to anxiety frequency,  
  **Anxiety Value** (numeric score), **Anxiety Label** (class).  
- **Class label:** `Anxiety Label` with 4 levels:  
  Minimal, Mild, Moderate, Severe.  
- **Why suitable for our task:**  
  - Meets Phase 1 requirements (≥500 rows, ≥10 columns, has a class label).  
  - Clear target for **classification** (severity levels).  
  - Rich features (demographic + academic + GAD-7 items) 
