# IBM HR Analytics

![Image](https://github.com/user-attachments/assets/07b440aa-7984-41f6-b342-d3350322d89d)

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
- Step 5 : New pivot table is created to represent **"Income by dep"**. In time of creating the pivot chart and table, "Gender" is palced in _Columns_, "Department" is plotted as _Rows_ and "Average of MonthlyIncome" is placed as _Value_.
![Image](https://github.com/user-attachments/assets/cf97df4b-e090-4f5e-bc95-88c66da75c6f)
- Step 6 :By selecting the total data range, **"Work life by status"** sheet is created where "MaritalStatus" is palced in _Columns_, "WorkLifeBalance" is plotted as _Rows_ and "Count of EmployeeNumber" is placed as _Value_. Here is the selected chart is "Radar".
![Image](https://github.com/user-attachments/assets/d39b5273-413d-4504-9556-c4f7a96ae9ce)
- Step 7 : **"Training"** is diplayed through the Line chart through the pivot table and chart. To create the pivot chart and table, "Department" is palced in _Columns_, "TrainingTimesLastYear" is plotted as _Rows_ and "Count of EmployeeNumber" is placed as _Value_.
![Image](https://github.com/user-attachments/assets/3902b981-a425-4569-b672-30a2cf771c04)
- Step 8 : The new sheet is created to identify the "Divorced" employee in **"Divorced"**. This data is prepared by filtering from the original dataset. 
- Step 9 : All key **"Insights"** is created to calculate "Total Employee Count", "Average of JobSatisfaction", "Average of Age", and "Marital Status".

![Image](https://github.com/user-attachments/assets/5738100d-1bfb-4902-8a88-448364790099)

- Step 10 : To create the interactive HR Dashboard, slicer for department, gender, over time, job satisfection, job involvement, and attrition is placed in the left side. Displayed total employee number, average age, turnover rate and job satisfection at the top. Other created charts are also placed in the dashboard to display all insights at one place.
![Image](https://github.com/user-attachments/assets/07b440aa-7984-41f6-b342-d3350322d89d)

# Used Formula in IBM HR Dashboard:
- Total Employee Number:

        Total Employee Number = GETPIVOTDATA("EmployeeNumber",Insight!$A$2)
- Total Male Employee Number:

        Total Male Employee Number = GETPIVOTDATA("EmployeeNumber",Insight!$A$2,"Gender","Male")
- Total Female Employee Number:

        Total Female Employee Number = GETPIVOTDATA("EmployeeNumber",Insight!$A$2,"Gender","Female")
- Average Turnover Rate:

      Average Turnover Rate = Insight!H16

- Average Turnover Rate for Male:

        Average Turnover Rate for Male = Insight!H18 
- Average Turnover Rate for Female:

        Average Turnover Rate for Female = Insight!H16
- Average Age of the Employee:

        Average Age of the Employee = GETPIVOTDATA("Age",Insight!$A$14)
 - Average Age of Male:

        Average Age of Male = GETPIVOTDATA("Age",Insight!$A$14,"Gender","Male")
- Average Age of Female:

        Average Age of Female = GETPIVOTDATA("Age",Insight!$A$14,"Gender","Female")

 # Usage of the HR Dashboard:

The HR Analytics Dashboard is designed to help HR professionals, managers, and decision-makers gain valuable insights into workforce trends, employee satisfaction, and organizational performance. By leveraging interactive filters, users can analyze key metrics such as gender distribution, job satisfaction, attrition rates, and business travel patterns across different job roles. The dashboard enables easy comparison of departmental performance, monthly income trends, and training investments, allowing HR teams to make data-driven decisions. With real-time updates and a user-friendly interface, this dashboard streamlines HR analytics and enhances workforce planning.
