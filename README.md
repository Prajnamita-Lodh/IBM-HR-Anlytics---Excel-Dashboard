# IBM HR Anlytics - Excel-Dashboard


## Problem Statement

This project aims to create an interactive Excel dashboard that contains data from EmployeeNumber, Age, Attrition, BusinessTravel, DailyRate, Department, DistanceFromHome, Education, EducationField, EnvironmentSatisfaction, Gender, HourlyRate, JobInvolvement, JobLevel, JobRole, JobSatisfaction, MaritalStatus, MonthlyIncome, MonthlyRate, NumCompaniesWorked, OverTime, PercentSalaryHike, PerformanceRating, RelationshipSatisfaction, StandardHours, StockOptionLevel, TotalWorkingYears, TrainingTimesLastYear, WorkLifeBalance, YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion, and YearsWithCurrManager. Users can easily filter and analyze the data, gaining insights into attrition prediction, employee satisfaction, and workforce planning, empowering effective decision-making and improving overall resource performance.

### DB Sheet:
DB sheet is the main database from where the dashboard is prepared. 
- EmployeeNumber: Unique ID for the employee (e.g., 1). Age: Employee's age (e.g., 41).
- Attrition: Indicates if the employee has left the company (Yes/No).
- BusinessTravel: Frequency of business travel (e.g., "Travel_Rarely").
- DailyRate: Employee’s daily pay rate (e.g., 1102).
- Department: The department the employee works in (e.g., "Sales").
- DistanceFromHome: Distance from home to work (e.g., 1 mile).
- Education: Education level on a scale (e.g., 2).
- EducationField: Employee's field of study (e.g., "Life Sciences").
- EnvironmentSatisfaction: Satisfaction level with the work environment (e.g., 2).
- RelationshipSatisfaction: Satisfaction with workplace relationships (e.g., 1).
- StandardHours: Standard work hours per week (e.g., 80).
- StockOptionLevel: Employee's stock options (e.g., 0).
- TotalWorkingYears: Total years of work experience (e.g., 8).
- TrainingTimesLastYear: Number of training sessions attended (e.g., 0).
- WorkLifeBalance: Work-life balance rating (e.g., 1).
- YearsAtCompany: Number of years spent at the company (e.g., 6).
- YearsInCurrentRole: Years spent in the current role (e.g., 4).
- YearsSinceLastPromotion: Years since the last promotion (e.g., 0).
- YearsWithCurrManager: Years working with the current manager (e.g., 5).

### Other Sheets:
The "db" sheet serves as the primary database from which all other sheets are derived. It contains raw employee data that is analyzed and segmented into different categories, such as gender distribution, income levels, work-life balance, job satisfaction, and training statistics, to generate meaningful HR insights.
- Gender by dep – Gender distribution across departments.
- Income by dep – Income distribution by department.
- Travel by role – Travel frequency by role.
- Satisfaction – Employee satisfaction data.
- Training – Training-related data.
- Work life by status – Work-life balance based on employment status.
- Insight –  Summary data based on gender.
- Divorced – Detailed information about divorced employee.
- HR dashboard – The main dashboard for IBM HR Analytics.

## Key Features of Dashboard:
🔄 **Data Consolidation**:
The dashboard integrates multiple HR metrics into a unified view, providing a comprehensive analysis of employee demographics, satisfaction, and performance.

🎛 **Interactive Slicers**:
Users can filter data dynamically based on Gender, Department, Overtime, Job Satisfaction, Job Involvement, and Attrition, enabling deeper insights into specific employee groups.

📈 **Visual Representation**:
A combination of bar charts, pie charts, radar charts, and line graphs visually represents key HR metrics, making it easier to identify trends and patterns.

🏆 **Employee Satisfaction & Turnover Insights**:
Analyze Job Satisfaction, Involvement, and Attrition Rates to assess workforce engagement and predict potential turnover risks.

🌍 **Business Travel & Work-Life Balance Analysis**:
Provides a breakdown of travel frequency across job roles and examines work-life balance based on marital status.

💰 **Compensation & Departmental Comparisons**:
Visualizes monthly income across departments, helping HR teams identify salary trends and disparities.

⚡ **User-Friendly & Customizable**:
Designed with an intuitive interface, ensuring easy navigation. Users can customize reports and charts based on specific business needs.

🔄 **Real-Time Updates**:
The dashboard stays connected to the data source, updating automatically whenever new HR data is added or modified.

📊 **Strategic HR Insights**:
Empowers decision-makers with valuable insights into employee retention, performance trends, and workforce distribution, aiding in better HR planning.

## Steps followed 

- Step 1 : Get the dataset for IBM Employee from "Kaggle".
- Step 2 : Select the whole data range and go to "Insert". After the clicked on ""PivotChart and PivotTable". The pivot was created in the new sheet which is named as **"Gender by dep"**. To create the pivot chart and table, "Gender" is palced in _Columns_, "Department" is plotted as _Rows_ and "Count of EmployeeNumber" is placed as _Value_.
![Image](https://github.com/user-attachments/assets/081d5c50-e6e6-483d-9700-630cfac6df16)
- Step 3 : Another new sheet was created by the name **"Travel by role"**. To create the pivot chart and table, "BusinessTravel" is palced in _Columns_, "JobRole" is plotted as _Rows_ and "Count of EmployeeNumber" is placed as _Value_.
![Image](https://github.com/user-attachments/assets/8b9b4c9a-0377-4a1f-9695-e387ec7ff0eb)
- Step 4 : Job Satifaction is diplayed through the Pie chart through the pivot table and chart. To create the pivot pie chart and table, "JobSatisfaction" is plotted as _Rows_ and "Count of EmployeeNumber" is placed as _Value_.
![Image](https://github.com/user-attachments/assets/1ffa968f-b339-4c2a-b6bf-d25e00ca0a16)






![Image](https://github.com/user-attachments/assets/07b440aa-7984-41f6-b342-d3350322d89d)
