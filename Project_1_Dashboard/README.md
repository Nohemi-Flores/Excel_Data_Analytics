# Project 1 Dashboard
***I was able to complete this Excel project with the guidance of [Luke Barousse's Excel course](https://www.lukebarousse.com/excel). Files used in project are found in the aforementioned website.***

## Salary Dashboard
This dashboard was created to help job seekers assess fair compensation for their desired data roles.
[Check out the dashboard!](Project_1_Salary_Dashboard.xlsx)

![Salary Dashboard](https://github.com/user-attachments/assets/c15b887e-6a3c-43ed-b70c-e9babfe287a3)

### Introduction
The data used in this [project](Project_1_Salary_Dashboard.xlsx) includes information on job titles, salaries, locations, and essential skills showcased here. Again, [Barousse's Excel course](https://www.lukebarousse.com/excel) has the files containing the data.

### Excel Skills Used
- 📊 Charts
- <> Formulas and Functions
- ❌ Data Validation

### Data Jobs Dataset 
The dataset involves real-world data science job information from 2023. Dataset includes:
- 👩‍💻 Job Titles
- 💵 Salaries
- 📍 Locations
- 🔧 Skills

### Dashboard Build
📈 **Charts**

📊 **Data Science Job Salaries - Bar Chart**
![chart](https://github.com/user-attachments/assets/3358a899-dbb1-453f-ba99-f674ee77471c)

- **Excel Features:** Used bar chart and optimized layout for clarity.
- **Design Choice:** Horizontal bar chart for comparison of median salaries.
- **Data Organization:** Job titles sorted by descending salary for better readability.
- **Insights Gained:** Quick identification of salary trends, noting that Senior roles and Engineers are higher-paying than Analyst roles.

🌎 **Country Median Salaries - Map Chart**

![map](https://github.com/user-attachments/assets/588e6300-63fe-491d-bcc6-b6805b43ab22)

- **Excel Features:** Used Excel's map chart feature to plot median salaries across the globe.
- **Design:** Map was color-coded to differentiate salary levels across regions.
- **Visual Enhancenment:** Better readability and immediate understanding of geographic salary trends.
- **Insights Gained:** Quick grasp of global salary disparities and highlights high/low salary regions.

🧮 **Formulas and Functions**

![median](https://github.com/user-attachments/assets/5361b49e-2b00-4bb1-a7b4-689549a1ceab)

**Median Salary by Job Titles**
- **Multi-Criteria Filtering:** Job title, country, schedule type checked. Blank salaries excluded.
- **Array Formula:** Uses MEDIAN() function with nested IF() statement in order to analyze an array.
- **Tailored Insights:** Specific salary information for job titles, regions, and schedule types provided.
- **Formula Purpose:** To populate table below, returning median salary based on job title, country, and type specified.

![table](https://github.com/user-attachments/assets/1af0d697-1d3a-4aa0-9709-1486ac266977)

**Dashboard Implementation**

![title](https://github.com/user-attachments/assets/b5868b84-742f-47b1-a200-58b24c6ca2a9)

**Count of Job Schedule Type**

![title](https://github.com/user-attachments/assets/9cbe3a72-aa09-4c6b-b326-49d94589b3c0)

**Unique List Generation:** This Excel formula below uses the FILTER() function to exclude entries containing "and" or commas, and omit zero values.
**Formula Purpose:** Populates table below, which provides a list of unique job schedule types.

![title](https://github.com/user-attachments/assets/83a555cf-2540-4ede-b219-3dd55dec3ff8)

**Dashboard Implementation:**

![type](https://github.com/user-attachments/assets/cb73edbe-158d-4b52-b10e-3cadc4beec6e)

## Data Validation

- **Enhanced Data Validation:** Implementing filtered list as a data validation rule under JOB TITLE, COUNTRY, and TYPE option ensures:
    - User input is restricted to predefined, validated schedule types
    - Prevention of incorrect or inconsistent entries
    - Enhancement of dashboard's overall usability

  ![type](https://github.com/user-attachments/assets/f0e1dae3-1c91-42f5-9e42-88897a2a4cb0)

  ## Conclusion
  By exploring the functionalities to understand how location and job type influence salaries, this dashboard allows users to make informed decisions regarding their career paths.
