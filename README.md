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

## Steps followed 
