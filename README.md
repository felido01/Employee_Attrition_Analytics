# HR Employee Attrition Analytics Project


## Data Driven Employee Attrition Insight

### Content
- Introduction
- Projects Overview
- Tools and Methodology
- Data Cleaning Process
- Dashboard Design Process
- Key Insight and Observation
- Recommendations and Actionable Insights
- Challenges
- Conclusion

---

## Introduction
Employee attrition is more than just a turnover rate status; it’s a reflection of workplace culture, employee satisfaction, and organizational health. High attrition rates can lead to increased recruitment costs, loss of talent, and reduced team morale. As companies strive to retain top performers, understanding the factors driving employees to leave is crucial.

In this project, I analyzed the **IBM HR Employee Attrition dataset** to uncover hidden patterns behind employee turnover. Using **Power BI** as the primary tool, I transformed raw data into actionable insights through an interactive dashboard. This article walks through my approach, key findings, and how data-driven decisions can improve employee retention.

---

## Project Overview
### Objectives
- Provide insight into key factors causing attrition in the organization.
- Offer actionable insights to help HR teams improve retention rates.

### Dataset Used
The dataset was sourced from **Kaggle**: [IBM HR Analytics Employee Attrition and Performance Dataset](#).  
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
[View Refined Google Sheet Dataset](#)

### Using Python
- Imported cleaned data into Python using the **pandas** library.
- Performed **Exploratory Data Analysis (EDA)** with functions like `.shape`, `.head()`, `.info()`, and `.describe()` for statistical insights.
- Checked for missing or duplicate values (none found).
- Created quick visualizations using **matplotlib** and **seaborn** to assess attrition counts.  
[View Python Data Manipulation and Exploration Process](#)

---

## Dashboard Design Process
- Built a comprehensive dashboard in **Power BI** to visualize factors influencing attrition.
- Designed a custom background in **Figma** to enhance visual appeal and layout.
- Incorporated key metrics and charts to analyze attrition factors.
- Used **DAX (Data Analysis Expressions)** to calculate measures like total attrition, employee count, and gender distribution.
- Applied **Power Query** for data transformation to optimize visualization.  
[View Live Dashboard](#)

---

## Key Insights and Observations
- **Total Attrition**: 16.12% of total employees.
- **Age Group**: Younger employees and recent recruits show higher attrition rates.
- **Department**: Research and Development (R&D) has the highest attrition rate.
- **Job Role**: Laboratory Technicians in R&D experience the highest attrition.
- **Job Satisfaction**: Employees with low job satisfaction have high attrition rates, but surprisingly, high job satisfaction also shows notable attrition.
- **Gender**: Male employees have a higher attrition rate than female employees.
- **Job Level**: Job Level 1 employees exhibit significantly higher attrition.
- **Compensation**: Employees earning $1,000–$5,000/month have the highest attrition rates, suggesting compensation as a factor.

---

## Recommendations and Actionable Insights
1. **Young Employees and Job Level 1**:
   - Develop targeted retention programs with clear career paths, mentorship, and enhanced training to reduce early-stage turnover.
2. **Research and Development Department**:
   - Conduct exit interviews and surveys to identify specific challenges (e.g., workload, team dynamics).
   - Improve work-life balance and team collaboration.
3. **Laboratory Technician Role**:
   - Offer job rotation, additional training, and career development opportunities to boost satisfaction.
4. **Job Satisfaction**:
   - Regularly measure satisfaction via surveys and focus groups to address pain points like workload or lack of growth opportunities.
5. **Male Employees**:
   - Conduct surveys to uncover specific issues affecting male employees.
   - Implement tailored strategies like improved career development or work-life balance initiatives.
6. **Compensation**:
   - Review salaries for employees earning $1,000–$5,000/month to align with industry standards.
   - Offer additional benefits or performance incentives.

---

## Challenges
- **Resistance to Participation**: Employees or managers may resist new retention initiatives.
- **Resource Constraints**: Limited time and budget may hinder program development.
- **Low Survey Participation**: Inaccurate or insufficient data could lead to unreliable insights.

---

## Conclusion
Addressing employee attrition requires a targeted approach focusing on factors like age, department, job satisfaction, and compensation. By implementing tailored retention strategies and overcoming challenges like resource limitations and resistance to change, organizations can reduce turnover, improve employee satisfaction, and foster a stable, engaged workforce.
