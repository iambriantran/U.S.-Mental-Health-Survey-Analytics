# U.S. Mental Health Survey Analysis

This project analyzes mental health trends in the U.S. workplace using data from the "Mental Health in Tech Survey" dataset, processed and visualized in Tableau. It provides insights into demographics, workplace factors, and mental health outcomes.

---

## Project Objective
The objective is to examine patterns in workplace mental health, including demographic factors, treatment-seeking behavior, and company-level influences. The final analysis is presented as an interactive Tableau dashboard, aiming to provide actionable insights for decision-makers and stakeholders.

---

## Dataset Description
### 1. Original Dataset: `survey.csv`
- Raw data from the "Mental Health in Tech Survey."
- Contains 27 columns covering demographics, workplace characteristics, and mental health-related responses.

### 2. Cleaned Dataset: `cleaned_mental_health_in_tech.csv`
- Processed version of the dataset, tailored for visualization and analysis.
- Reduced to 26 columns after cleaning, with added transformations such as categorized age ranges for more concise visualizations.

---

## Tableau Dashboard
![Dashboard Preview](https://github.com/iambriantran/U.S.-Mental-Health-Survey-Analytics/blob/main/Mental%20Health%20Survey%20Analysis.png)
[Click to view dashboard in Tableau Public.](https://public.tableau.com/app/profile/brian3322/viz/U_SMentalHealthSurveyAnalysis/MentalHealthSurveyAnalysis#2)

---

## Key Insights from the Tableau Dashboard
- **Survey Participation**: The dashboard includes data from 742 participants, of which 405 have sought mental health treatment.
- **Demographics**:
  - **Age Distribution**: Majority of respondents fall into the 21–30 and 31–65 age groups.
  - **Gender Breakdown**: Gender-specific analysis of mental health treatment-seeking behavior.
- **Company Characteristics**:
  - Employee count influences mental health resources and treatment-seeking.
  - Larger companies (1000+ employees) reported higher rates of mental health support.
- **Employment Characteristics**:
  - Analysis of self-employment, remote work, and industry type.
- **Geographical Distribution**: Interactive map showing responses by state.

---

## Data Processing Steps
### 1. Data Cleaning (Python/Jupyter Notebook)
- Removed unnecessary columns such as `Timestamp` and `Comments`.
- Removed null and inconsistent values.
- Standardized columns like `Gender` for uniform analysis.
- Added derived fields such as `age_range` for simplified categorization.

### 2. Feature Engineering
- Processed Boolean fields for easier visualization in Tableau.

### 3. Visualization Preparation
- Exported the cleaned dataset (`cleaned_mental_health_in_tech.csv`) to feed into Tableau.

---

## Tools Used
- **Data Processing**: Python, pandas
- **Visualization**: Tableau
- **Development Environment**: Jupyter Notebook

---
