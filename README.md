# HR Employee Attrition Analytics Project
## Data Driven Employee Attrition Insight

## Introduction
Employee attrition is more than just a turnover rate status; it’s a reflection of workplace culture, employee satisfaction, and organizational health. High attrition rates can lead to increased recruitment costs, loss of talent, and reduced team morale. As companies strive to retain top performers, understanding the factors driving employees to leave is crucial.

In this project, I analyzed the **IBM HR Employee Attrition dataset** to uncover hidden patterns behind employee turnover. Using **Power BI** as the primary tool, I transformed raw data into actionable insights through an interactive dashboard. This article walks through my approach, key findings, and how data-driven decisions can improve employee retention.

---

## Project Overview
### Objectives
- Provide insight into key factors causing attrition in the organization.
- Offer actionable insights to help HR teams improve retention rates.

### Dataset Used
The dataset was sourced from **Kaggle**: [IBM HR Analytics Employee Attrition and Performance Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).  
It contains comprehensive employee data, including attrition status, making it a valuable resource for analyzing factors contributing to turnover.

---

## Tools and Methodology
- **Power BI**: For building comprehensive charts and dashboards.
- **Python**: For data manipulation and exploration.
- **Google Sheets**: For data preprocessing.
- **Figma**: For designing dashboard backgrounds.

---

## Data Cleaning Process
### Using Google Sheets
- Utilized **Find and Replace** to decode coded values in specific columns for better interpretability.
- Formatted numerical values in money-related columns for consistent currency representation.  
[View Refined Google Sheet Dataset](https://docs.google.com/spreadsheets/d/1gne8ytDMMpoqgPmXkxd_wr5d7fbJD3mozyC8OyKTJqQ/edit?pli=1&gid=516561653#gid=516561653)

### Using Python
- Imported cleaned data into Python using the **pandas** library.
- Performed **Exploratory Data Analysis (EDA)** with functions like `.shape`, `.head()`, `.info()`, and `.describe()` for statistical insights.
- Checked for missing or duplicate values (none found).
- Created quick visualizations using **matplotlib** and **seaborn** to assess attrition counts.  
[View Python Data Manipulation and Exploration Process](https://github.com/felido01/Employee_Attrition_Analytics/blob/7de1303587f9c5dbb131a6cf1a38e7882628efe6/Employee%20Attrition%20Analysis-checkpoint.ipynb)

---

## Dashboard Design Process
- Built a comprehensive dashboard in **Power BI** to visualize factors influencing attrition.
- Designed a custom background in **Figma** to enhance visual appeal and layout.
- Incorporated key metrics and charts to analyze attrition factors.
- Used **DAX (Data Analysis Expressions)** to calculate measures like total attrition, employee count, and gender distribution.
- Applied **Power Query** for data transformation to optimize visualization.  
[View Live Dashboard](https://app.powerbi.com/groups/me/reports/53cda70a-db29-43c3-80cd-440f9cdc4121/a2849a1365d89e7978c7?experience=power-bi)

---

## Key Insights and Observations
Based on the analysis from the dashboard, Total Attrition is 16.12% of Total Employee. Several key factors contributing to employee attrition were also identified:
- **Age Group**: A significant portion of attrition occurs among younger employees and recent recruits, indicating that younger staff are more likely to leave the organization.
  
- **Department**: The Research and Development department has the highest attrition rate compared to other departments, suggesting potential department-specific challenges
  
- **Job Role**: Within the Research and Development department, the role of Laboratory Technician experiences the highest attrition rate, highlighting the need for a closer review of job-specific factors affecting employee retention
  
- **Job Satisfaction**:  Interestingly, employees with high job satisfaction also exhibit notable attrition rates, which is unexpected. However, as anticipated, employees with low job satisfaction show even higher attrition rates, aligning with common retention trends
  
- **Gender**: Male employees exhibit a higher attrition rate compared to female employees. This trend is consistent across other influencing factors such as age, department, and job role
  
- **Job Level**: Employees at Job Level 1 have a significantly higher attrition rate compared to other job levels. This pattern aligns with the earlier observation that young recruits and entry-level employees are more likely to leave the organization, suggesting potential challenges in onboarding, career growth opportunities, or job expectations at the early stages of employment.
  
- **Compensation Insight**: When analyzing the relationship between monthly income and attrition rate, it was observed that employees earning between $1,000 and $5,000 per month have the highest attrition rates. This suggests that compensation may be a contributing factor to employee turnover, particularly among those in the lower to mid-income brackets

---

## Recommendations and Actionable Insights
1. **Young Employees and Job Level 1**:
   - There is a significant pattern of attrition among younger employees and those at Job Level 1. To address this, targeted retention programs for these groups should be developed. Implementing clear career progression paths, offering mentorship opportunities, and enhancing training programs could support their development and reduce early-stage turnover
3. **Research and Development Department**:
   - The high attrition rate within the Research and Development department suggests that department-specific issues may be contributing to turnover. Conducting exit interviews and employee surveys will help identify specific challenges such as workload, job satisfaction, or team dynamics. This insight can lead to strategies that improve retention, such as enhancing work-life balance or fostering better collaboration within teams
4. **Laboratory Technician Role**:
   - Laboratory Technicians in the R&D department have the highest attrition rates, highlighting a need for a deeper review of their roles. This could include offering job rotation, additional training, and more career development opportunities to enhance job satisfaction and reduce attrition.
5. **Job Satisfaction**:
   - While high job satisfaction doesn't seem to correlate with lower attrition, low job satisfaction is a significant factor. Regularly measuring job satisfaction through surveys and focus groups will help identify pain points. Addressing concerns such as workload, management style, or lack of growth opportunities will improve overall employee engagement and retention
6. **Male Employees**:
   - With male employees showing higher attrition rates, it's important to understand the underlying reasons for this trend. Conducting focused surveys with male employees could uncover specific issues affecting their job satisfaction. Tailored retention strategies such as improved career development or work-life balance initiatives could help reduce turnover among this group.
7. **Compensation**:
   - Employees earning between $1,000 and $5,000 per month have the highest attrition rates, indicating that compensation may be a contributing factor. A competitive salary review for this group should be conducted to ensure that their pay aligns with industry standards. Offering additional benefits, performance incentives, or career progression opportunities could help retain employees in this income range.
By addressing these factors, the organization can take a targeted approach to improve employee retention, ensuring a more stable and engaged workforce.

---

## Challenges
- **Resistance to Participation**: Employees or managers may resist new retention initiatives.
- **Resource Constraints**: Limited time and budget may hinder program development.
- **Low Survey Participation**: Inaccurate or insufficient data could lead to unreliable insights.

---

## Conclusion
In conclusion, addressing employee attrition requires a targeted approach, focusing on key factors like age, department, job satisfaction, and compensation. By implementing tailored retention strategies and overcoming challenges such as resource limitations and resistance to change, the organization can effectively reduce turnover and improve employee satisfaction, leading to a more stable and engaged workforce.
