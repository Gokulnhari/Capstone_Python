# Employee Data Analysis Project

## Overview
This project aims to analyze employee data, uncovering trends and patterns related to demographics, team structures, and salary expenditures. Key insights include distribution of employees, predominant age groups, salary correlations, and salary expenditure trends across teams and positions.

---

## Preprocessing Steps
- **Dataset Loading**: The dataset was read using `pandas`. A `FileNotFoundError` was handled to ensure smooth execution.
- **Data Correction**: A `height` column was generated using random integer values (150-180 cm) for all records to demonstrate preprocessing.

---

## Analysis Tasks
### 1. Employee Distribution Across Teams
- Computed the distribution of employees across various teams.
- Calculated percentage splits for better visualization of team composition.

### 2. Segregation by Position
- Identified and listed all unique positions held by employees within the organization.

### 3. Predominant Age Group
- Categorized employees into age groups (e.g., 18-22, 23-27, etc.) using `pandas.cut`.
- Determined the age group with the highest number of employees.

### 4. Salary Expenditure by Team and Position
- Calculated total salary expenditures for each team and position using `groupby`.
- Identified the team and position with the highest salary expenditure.

### 5. Correlation Between Age and Salary
- Calculated the correlation coefficient to understand the relationship between age and salary.

---

## Graphical Representations
1. **Scatter Plot**: Visualized the relationship between age and salary using `seaborn.scatterplot`.
2. **Bar Plot**: Showed the distribution of employees across teams using a bar chart.

---

## Insights Gained
1. **Team Composition**: Observed team size distribution and percentage contributions.
2. **Positions Overview**: Gained clarity on diverse roles within the organization.
3. **Age Demographics**: Identified the predominant age group.
4. **Salary Trends**: Noted which teams and positions had the highest salary expenditures.
5. **Age-Salary Correlation**: Found a statistical relationship (positive/negative/neutral) between age and salary.

---

## Future Analysis Ideas
- Explore the impact of position, team, and age group on salaries.
- Analyze geographical diversity if location data is available.
- Use machine learning models to predict salaries based on age, team, and position.







