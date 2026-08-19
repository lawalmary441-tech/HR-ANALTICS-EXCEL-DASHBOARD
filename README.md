# HR-ANALTICS-EXCEL-DASHBOARD
An interactive HR ANALTICS DASHBOARD built primarily with Microsoft EXCEL .

## Project Overview
This project analyzes employee attrition using the IBM HR Analytics Employee Attrition dataset and presents the findings through an interactive Excel dashboard.

The objective is to understand **who is leaving, where attrition is concentrated, and which employee/workplace factors are associated with attrition**.

## Dataset

- **Records:** 1,470 employees
- **Features:** 44 columns
- **Target:** `Attrition`
  - `Yes` = employee left
  - `No` = employee stayed
- **Attrition cases:** 237
- **Active employees:** 1,233
- **Attrition rate:** 16.12%
- **Average age:** approximately 37 years

## Tools Used

- **Excel** — Data inspection, cleaning, interactive dashboard 
- **powerpoint** for reporting

## Project Workflow

1. Loaded the HR Analytics dataset into Excel.
2. Confirmed that the dataset contained 1,470 rows and 44 columns.
3. Checked for duplicate records.
5. Reviewed the distribution of the `Attrition` target.
7. Explored attrition across departments, overtime status, job roles, income and age groups.
9. Built an interactive Excel dashboard to communicate the findings.

## Key Findings

### Department
Research & Development has the largest employee population and also records the highest number of employees who left.

### Overtime
Employees who work overtime show higher attrition, while employees who do not work overtime are more represented among employees who stayed.

### Job Role
Sales Executive has the largest employee population, while Laboratory Technician records the highest number of employees who left.

### Income
The analysis indicates that higher-income employees tend to stay more, while lower-income employees show greater attrition.

### Age
Younger employees tend to leave more, while older employees tend to show stronger retention.

## Correlation Analysis

### Stronger Positive Relationships
- Overtime
- Marital Status
- Distance From Home

### Stronger Negative Relationships
- Total Working Years
- Job Level
- Years in Current Role


## Dashboard

The Excel dashboard contains:

- Total Employees
- Attrition
- Active Employees
- Attrition Rate
- Average Age
- Total Employee by Gender
- Education-wise Attrition
- Attrition by Job Role
- Department-wise Attrition
- Attrition by Age Group
- Attrition by Marital Status
- Education Field and Department filters

## Business Recommendations

1. Review overtime-heavy teams for workload and burnout risks.
2. Create targeted retention initiatives for younger and early-career employees.
3. Investigate high-attrition job roles, especially Laboratory Technician and Sales Executive.
4. Review compensation progression and career-development opportunities.
5. Monitor attrition at department level so HR can intervene earlier.

## Suggested Repository Structure

```text
HR-Analytics-Project/
│
├── README.md
├── HR_Analytics_Dashboard.xlsx
├── HR_Analytics_Project_2_Report.pptx
├── Dataset
│
└── Screenshots/
    └── HR_Analytics_Dashboard.png
```

## Project Outcome

This project demonstrates the ability to:

- inspect and prepare real-world HR data
- perform exploratory data analysis
- identify meaningful employee attrition patterns
- communicate insights through an interactive dashboard
- translate analytical findings into practical HR recommendations

**Project:** HR Analytics — Employee Attrition  
**Focus:** Workforce analytics, employee attrition and data visualization
