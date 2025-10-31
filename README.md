# HR Analytics Dashboard

## Project Overview:
This **HR Analytics Dashboard** is designed to help Human Resources teams and managers gain deep insights into employee attrition patterns across various dimensions. Built using **Power BI**, the dashboard provides a user-friendly and visually appealing way to track and analyze employee metrics like age, salary, education, job roles, and years at the company, which are essential in making data-driven HR decisions.

## Technologies Used:
- **Power BI**: This tool is used for data visualization and creating dynamic, interactive dashboards.
- **Data Modeling**: The underlying data models and relationships between tables were created within Power BI to ensure smooth data flow and accurate metrics.
- **DAX (Data Analysis Expressions)**: For complex calculations like attrition rate, average salary, and turnover prediction.

## Key Metrics:
- **Employee Count**:  
  Total employees in the company: **446**.
  
- **Attrition**:  
  Total employees who left the organization: **92**.  
  Attrition Rate: **20.6%**, indicating the percentage of employees who left relative to the total workforce.

- **Average Age**:  
  The average age of employees: **37 years**.

- **Average Salary**:  
  The average salary of employees: **7,000 (currency unit)**.

- **Average Years at Company**:  
  The average number of years employees have been with the company: **7.3 years**.

## Detailed Data Breakdown:
### 1. **Attrition by Education**:
- Technical Degree: **11%** attrition.
- Medical: **15%** attrition.
- Life Sciences: **32%** attrition.
- Marketing: **38%** attrition.

### 2. **Attrition by Age**:
- 26-35: **41** employees.
- 18-25: **18** employees.
- 46-55: **16** employees.
- 36-45: **17** employees.
- 55+: **16** employees.

### 3. **Attrition by Salary Slab**:
- Upto 5k: **43** employees.
- 5k-10k: **36** employees.
- 10k-15k: **11** employees.
- 15k+: **2** employees.

### 4. **Attrition by Years at Company**:
- 0-5 years: **17** employees.
- 6-10 years: **7** employees.
- 10+ years: **2** employees.

### 5. **Attrition by Job Role**:
- Sales Executive: **57** employees.
- Sales Representative: **33** employees.
- Manager: **2** employees.

## Visualizations and Insights:
- **Pie Charts**: Show the proportion of attrition across various categories such as education level, age group, salary range, and job roles.
- **Bar Graphs**: Display the number of employees who left based on job role, age, and salary.
- **Line Graphs**: Illustrates the trend of employee attrition over the years.

The dashboard's visualizations help identify areas that may require HR intervention, such as roles or age groups with high attrition rates.

## Features of the Dashboard:
### 1. **Interactive Filters**:
- The dashboard allows users to filter data by **Department** (e.g., HR, Sales, Research & Development), enabling dynamic updates of the visualizations to focus on specific departments.

### 2. **User-Centric Design**:
- The dashboard is designed for non-technical HR managers, offering intuitive insights into HR data at a glance.
- Key metrics like **average age**, **attrition rate**, and **salary details** are displayed prominently for quick decision-making.

### 3. **Detailed Segmentation**:
- Segmentation by **Age**, **Salary**, **Education**, and **Job Role** allows HR teams to dig deep into specific factors affecting employee retention.

## Data Insights and Actionable Points:
- **High Attrition in Sales Roles**: A significant percentage of employees in the **Sales Executive** and **Sales Representative** roles have left, indicating a need for changes in sales-related policies or incentives.
- **Salary Influence**: Employees earning **Upto 5k** have the highest attrition rate, signaling a potential need for pay increases or better retention strategies for lower salary brackets.
- **Age Group Insights**: The **26-35 age group** shows the highest turnover, suggesting that this demographic might be looking for career growth opportunities. HR could consider offering career development programs targeted at this age group.
- **Longer Tenure and Lower Attrition**: Employees who have been with the company for over 10 years show very low attrition. HR might explore strategies to retain employees in the first 5 years of their tenure, where attrition is higher.

## How to Use:
1. Clone or Download the repository.
2. Open the `.pbix` Power BI file in **Power BI Desktop** to interact with the dashboard.
3. Filters are available on the top right to adjust the view by **Department** or **Job Role**.
4. **Data Source**: Update the dataset path in Power BI if new data is available.

## Installation Instructions:
1. Install **Power BI Desktop**: [Download Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)
2. Clone this repository or download the `.pbix` file to your local system.
3. Open the Power BI file to start exploring the dashboard.

## Future Enhancements:
- **Real-Time Data Integration**: The dashboard could be connected to live HR data systems for real-time tracking.
- **Predictive Analytics**: Introducing machine learning models to predict future attrition trends and offer proactive solutions.
- **Additional Metrics**: Adding more HR-related metrics like employee engagement scores, training effectiveness, and promotion trends.

## Contributing:
- Fork the repository and submit **pull requests** for any enhancements or features.
- Raise **issues** if you encounter any bugs or would like to suggest new features.
- Contributions are welcome, especially for improving data sources, adding more charts, or integrating predictive models.

## License:
Specify the license under which the project is distributed (e.g., MIT License, GPL-3.0, etc.).
