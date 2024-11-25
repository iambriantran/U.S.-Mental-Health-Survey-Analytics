# U.S. Mental Health Survey Analysis

This project analyzes mental health trends in the U.S. workplace using data from the "Mental Health in Tech Survey" dataset, processed and visualized in Tableau. It provides insights into demographics, workplace factors, and mental health outcomes.

---

## Project Objective
The objective is to examine patterns in workplace mental health, including demographic factors, treatment-seeking behavior, and company-level influences. The final analysis is presented as an interactive Tableau dashboard, aiming to provide actionable insights for decision-makers and stakeholders.
- Which age groups are most likely to seek mental health treatment?
- How does gender influence the likelihood of seeking treatment?
- Are remote workers more or less likely to seek mental health support compared to on-site employees?
- What is the relationship between self-employment and treatment-seeking behavior?
- How do workplace policies, such as leave policies or supervisor support, impact mental health treatment rates?
- What role does coworker support play in employees’ mental health outcomes?
- How do mental health issues correlate with company size, job function, or work arrangements?


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
  - Majority of respondents are male (555), then female (179).
- **Company Characteristics**:
  - Employee count influences mental health resources and treatment-seeking.
  - Larger companies (1000+ employees) reported higher rates of mental health support.
  - While there are 405 individuals that seek help, there are only 187 companies that provide resources on how to seek help (25%).
- **Employment Characteristics**:
  - Self-Employed or not, both groups have the same percentage of people who seek treatment (54%).
  - 56% of remote workers seek treatment, while 53% of non-remote workers seek treatment.
  - 55% of the workers in tech seek treatment, while 52% of the workers in non-tech companies seek treatment.
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
