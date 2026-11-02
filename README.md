# Student Academic Performance Analysis & Prediction

**IBM SPSS Modeler | Predictive Analytics | Data Mining**

---

## Project Overview

This project focuses on analyzing student-related data and exploring the factors associated with academic performance using **IBM SPSS Modeler**.

The main objective is to identify meaningful patterns in student data and examine how academic and personal factors relate to student performance.

The project includes data preparation, data exploration, and predictive modeling using a **CHAID Decision Tree** approach.

## Project Objectives

- Prepare and clean student data for analysis.
- Identify missing or inconsistent values.
- Explore relationships between student characteristics and academic outcomes.
- Apply predictive modeling techniques.
- Identify important factors associated with student performance.
- Explore classification rules using decision tree analysis.

## Dataset & Variables

The dataset contains student-related information, including the following variables:

| Variable | Description |
|:---|:---|
| Gender | Student gender |
| Faculty | Student faculty |
| Age | Student age |
| StudyHours | Hours spent studying |
| Attendance | Student attendance |
| StressLevel | Student stress level |
| AssignmentScore | Assignment score |
| Performance | Student academic performance category |

**Target Variable:** `Performance`

The target variable includes three categories:

- High
- Medium
- Low

## Project Workflow

### 1. Data Preparation

- Imported student data into IBM SPSS Modeler.
- Reviewed data fields and variable types.
- Examined the dataset structure.
- Prepared the data for further analysis and modeling.

### 2. Data Exploration

- Examined student-related variables.
- Explored study hours, attendance, stress levels, and assignment scores.
- Investigated relationships between input variables and academic performance.

### 3. Predictive Modeling

- Applied classification techniques using IBM SPSS Modeler.
- Used the CHAID algorithm to classify student academic performance.
- Explored decision rules and relationships between input variables and the target variable.

### 4. Feature Importance

The model's variable importance results indicate that **StudyHours** is the most influential input variable in the model.

Other variables contributing to the classification include:

- StressLevel
- AssignmentScore
- Attendance
- Age
- Gender

## Tools & Technologies

- **IBM SPSS Modeler**
- **CHAID Decision Tree**
- **Predictive Analytics**
- **Data Mining**
- **Classification**

## Key Findings

Based on the CHAID model's variable importance results:

- StudyHours has the highest relative importance.
- StressLevel is the second most influential variable.
- AssignmentScore and Attendance also contribute to the model.
- Age and Gender have comparatively lower importance.

These findings describe the model's variable importance, not necessarily causal relationships.

## Repository Structure

```text
student-academic-performance-analysis-spss/
│
├── Project_september.str
└── README.md
```

## How to Run

1. Download or clone this repository.
2. Open IBM SPSS Modeler.
3. Open the `Project_september.str` file.
4. Review the stream and its connected nodes.
5. Check the input data source path and update it if necessary.
6. Run the stream to execute the workflow.

## Author

**Aysu Qadirova**

Data Analytics Enthusiast

---

*Exploring student data to discover meaningful patterns in academic performance.*
