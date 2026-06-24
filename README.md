# Impact-of-AI-on-Students-EDA

## Project Overview

This project focuses on analyzing the impact of Artificial Intelligence (AI) tools on students' academic performance, study habits, skill retention, and overall learning experience. The dataset was cleaned, processed, and analyzed using Python to uncover trends and insights related to AI usage among students.

The project demonstrates essential data science tasks including:

- Data collection and loading
- Data cleaning and preprocessing
- Missing value handling
- Duplicate removal
- Exploratory Data Analysis (EDA)
- Data visualization
- Insight generation

## Dataset Source

**Dataset Name:** AI Student Impact Dataset

The dataset contains information about students' academic backgrounds, AI usage patterns, study habits, GPA, skill retention, burnout levels, and AI dependency.

## Features Included

- Student_ID
- Major_Category
- Year_of_Study
- Pre_Semester_GPA
- Weekly_GenAI_Hours
- Primary_Use_Case
- Prompt_Engineering_Skill
- Tool_Diversity
- Paid_Subscription
- Traditional_Study_Hours
- Perceived_AI_Dependency
- Institutional_Policy
- Anxiety_Level_During_Exams
- Post_Semester_GPA
- Skill_Retention_Score
- Burnout_Risk_Level
- Hours_Bucket

## Data Cleaning Steps

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected data types and dataset structure.
3. Checked for missing values.
4. Handled missing values using:
   - Median imputation for numerical columns.
   - Mode imputation for categorical columns.
5. Identified and removed duplicate records.
6. Verified data consistency and quality.
7. Exported the cleaned dataset for analysis.

---

## Exploratory Data Analysis (EDA)

Several analyses were conducted to understand the relationship between AI usage and student outcomes.

### Visualizations Generated

1. AI Usage by Major Category
2. Pre-Semester GPA vs Post-Semester GPA
3. Burnout Risk Distribution
4. Correlation Matrix of Numerical Features

---

## Key Insights

- AI usage varies across different academic majors.
- Changes in GPA can be observed before and after increased AI adoption.
- Burnout risk levels differ among students.
- AI dependency and study habits show interesting behavioral patterns.
- Correlation analysis highlights relationships between AI usage, GPA, and skill retention.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab


## How to Run the Project

### Run the Data Cleaning Script

```bash
python src/data_cleaning.py
```

This will:

- Load the raw dataset
- Perform data cleaning
- Remove duplicates
- Handle missing values
- Save the cleaned dataset


## Output Files

### Cleaned Dataset

```text
data/cleaned_dataset.csv
```

### Generated Visualizations

```text
images/ai_usage_by_major.png
images/gpa_comparison.png
images/burnout_risk.png
images/correlation_matrix.png
```

---

## Conclusion

This project demonstrates a complete data cleaning and exploratory data analysis workflow on an educational dataset focused on AI adoption among students. The findings provide insights into how AI tools influence academic performance, learning behavior, and student well-being.
