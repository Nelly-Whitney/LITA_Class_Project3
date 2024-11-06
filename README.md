# LITA_Class_Project3
Documentation of my class project while learning data analysis with Imcubato Hub
## PROJECT: LITA_Capstone_Project
### Project 3
### Outline
[Project Title](#Project-Title)

[Project Overview](#Project-Overview)

[Goals](#Goals)

[Data Sources](#Data-Sources)

[Tools Used](#Tools-Used)

[Data Cleaning and Preparation](#Data-Cleaning-and-Preparation)

[Data Overview](#Data-Overview)

[Exploratory Data Analysis](#Exploratory-Data-Anaysis)

[Data Analysis](#Data-Analysis)

[Data Visualization](#Data-Visualization)

[Findings](#Findings)

[Recommendations](#Recommendations)

[Conclusion](#Conclusion)


#### Project Title: Analysis Of HR Data
#### Project Overview 
This report analyzes employee attritin rates within the company to identify trends, factors contributing to employee turnover, and actionable recommendations to improve retention. The analysis focuses on key demographics, performance metrics and employee satisfaction indicators.

#### Goals
### Goal of Analysis of HR Data Dataset

The primary goal of analyzing the HR Data dataset focusing on employee attrition is to gain insights into the factors that influence employee turnover within the organization. This analysis aims to achieve the following objectives:

1. **Identify Attrition Rates**: 
   - Calculate the overall attrition rate and compare it across different departments, job roles, and demographic groups.

2. **Understand Key Factors Influencing Attrition**:
   - Investigate various factors that may contribute to employee attrition, such as:
     - Employee demographics (age, gender, marital status)
     - Job characteristics (job role, salary, work environment)
     - Performance metrics (job satisfaction, performance ratings)
     - Tenure and promotion history

3. **Visualize Patterns and Trends**:
   - Create visualizations (e.g., bar charts) to illustrate trends and relationships in the data, making it easier to spot patterns related to attrition.

By achieving these goals, the analysis will help the organization better understand its workforce dynamics, identify areas for improvement, and implement strategies to enhance employee retention.

#### Data Sources
The dataset for this analysis was provided by the Incubator Hub

#### Tools Used
- Microsoft Excel
   - Data Cleaning
   - Data Analysis
   - Data Visualization
- Power Bi Desktop for Visualization[Download Here](https://www.google.com/url?client=internal-element-cse&cx=012684331380167808104:oe5oj--md1a&q=https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads&sa=U&ved=2ahUKEwjQubqQr8GJAxUvUaQEHV7fEFkQFnoECBUQAQ&usg=AOvVaw1759XFBNl5AM71b9k88zga)
- GitHub for Portfolio Building amd Reporting of anaylsis

#### Data Cleaning and Preparation

In the initial phase of the data cleaning and preparations, I performed the following actions;

- Data Loading and Inspection
- Data Assessment where a preliminary review of the data set was conducted to understand the structure, completeness and identify any potential issues as regards the data set.
- Handling Missing Variables
- Data Cleaning and Formatting
- Data Consistency to ensure consistency in data formats across the data set and identify and eliminate duplicate records to enhance data integrity

#### Data overview

This dataset includes the following attributes 
- **Employee Number**: Unique identifier for each employee
- **Age**: Age of the employee
- **Gender**: Gender of the employee
- **Department**: Department where the employee works
- **Job Role**: Specific job title of the employee
- **Salary**: Annual salary of the employee
- **Performance Rating**: Annual Performance rating 
- **Years at Company**: Duration of employment at the company
- **Attrition**: Indicates if the employee has left the company (Yes/No)
- **Job Satisfaction**: Employee's self-reported job satisfaction (scale of 1 to 5)
- **Work-Life Balance**: Employee's self-reported work-life balance (scale of 1 to 5)

#### Exploratory Data Analysis 
EDA for this dataset involves 
- Calculating attrition rate
- Visualization of attrition by gender
- Job satisfaction analysis 
- Attrition by Job Role

#### Data Analysis
Here will be shown basic DAX expression used in the analysis of the dataset
1. For the creation of a measure for attrition rate
```DAX
Attrition rate= SUM('HR data'[Attrition Count])/SUM('HR data'[Employee Count]
```
2. For the creation of measure for average age of employee
```DAX
Average Age of Employee= SUM('HR data'[Age])/ SUM('HR data'[Employee Count])
```
#### Data Visualization
This is the interactive dashboard created using Power BI for visualization of analyzed data.
It includes
- Attrition By Department
- Attrition By Education Field
- Age Group Analysis
- Attrition By Gender

![HR data Bi](https://github.com/user-attachments/assets/eec3afae-6dc9-4bb1-8f61-ccdea6842087)

![HR data Bi 2](https://github.com/user-attachments/assets/48d12284-9707-4499-9240-afd6c418fe8e)

##### Findings
1. Attrition Overview
   - **Total Employees Analyzed**: 1470
   - **Total Attrition**: 237
   - **Attrition Rate**: 16.1%
2. Demographic Analysis
   - **Attrition By Gender**:
      - Male: 63.29%
      - Female: 36.71%
   - **Attrition By Age Group**:
      - Under 25: 16.03%
      - 25 - 34: 47.26%
      - 35 - 44: 21.52%
      - 45 - 54: 10.55%
      - Over 55: 4.64%
3. Departmental Analysis
   - **Department with the Highest Attrition**
      - R&D: 56.1%
   - **Department with the Lowest Attrition**
      - HR: 5.1%
4. Performance and Satisfaction Metrics
   - **Average Performance Rating of Departed Employees**: 3.16
   - **Average Job Satisfaction of Departed Employees**: 2.47
   - **Average Work-Life Balance of Departed Employees**: 2.66
5. Years at Company
   - **Average Tenure of Departed Employees**: 5.13
   - **Tenure with Highest Attrition**:
      - 1 year: 28.89%

#### Recommendations

1. **Targeted Retention Strategies**:
   - Departments with the high attrition rates should be focused on to develop specific retention programs.
   - Implement mentorship systems for new hires to improve integration and job satisfaction.
2. **Enhance Employee Engagement**:
   - Conduct regular employee satisfaction surveys to monitor job satisfaction and work-life balance.
   - Organize workshops and programs which improve team spirit to foster positive work environment.
3. **Career Development Opportunities**: Create clear pathways for career advancement to motivate empoyees stay longer.

#### Conclusion

The analysis reveals significant insights into factors affecting employee attrition within the company. By focusing on the recommendations provided above to enhance employee retention, the company can reduce attrition rates and foster a more stable workforce.
                              


