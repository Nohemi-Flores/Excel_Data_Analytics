# Project 2 Analysis

**Introduction**

I set out to understand what skills top employers request and how to land more pay.

**Questions to Analyze:**

1. Do more skills get you better pay?
2. What’s the salary for data jobs in different regions?
3. What are the top skills of data professionals?
4. What’s the pay for the top 10 skills?
Excel Skills Used

**Excel skills utilized for analysis:**
* Pivot Tables
* Pivot Charts
* DAX (Data Analysis Expressions)
* Power Query
* Power Pivot

**Data Jobs Dataset**

The dataset used for this project contains real-world data science job information from 2023. Data available from [Luke Barousse's Excel course](https://www.lukebarousse.com/excel)  

It includes detailed information on:
* 👨‍💼 Job titles
* 💰 Salaries
* 📍 Locations
* 🛠️ Skills

## 1️⃣ Do more skills get you better pay?

**🔍 Skill: Power Query (ETL)**

**📥 Extract**

* Power Query used to extract the original data (data_salary_all.xlsx) and create two queries:
    * First one with all the data jobs information.
    * The second listing the skills for each job ID.

**🔄 Transform**

* Each query transformed by changing column types, removed unnecessary columns, cleaned text to eliminate specific words, and trimmed excess whitespace.
 
**🔗 Load**

* Both transformed queries were loaded into the workbook, setting the foundation for subsequent analysis.

📊 **Analysis**

  **Insights**

* Existence of positive correlation between the number of skills requested in job postings and the median salary, particularly in roles like Senior Data Engineer and Data Scientist.
* Roles that require fewer skills, like Business Analyst, tend to offer lower salaries, suggesting that more specialized skill sets command higher market value. 

![skills-pay](https://github.com/user-attachments/assets/f295ae85-93e7-477b-b06b-98b40d78e4e1)
  
**🤔 So What**

* The value of acquiring multiple relevant skills is emphasized, particularly for individuals aiming for higher-paying roles.
  
## 2️⃣ What’s the salary for data jobs in different regions?

**🧮 Skills: PivotTables & DAX**

**📈Pivot Table**

* PivotTable created using the Data Model built with Power Pivot.
* Job_title_short moved to the rows area and salary_year_avg into the values area.
* New measure added to calculate the median salary for United States jobs.

**🧮 DAX**

* To calculate the median year salary, DAX was used.

**📊 Analysis**

**Insights**

* Job roles like Senior Data Engineer and Data Scientist command higher median salaries both in the US and internationally, which showcases the global demand for high-level data expertise.
* The salary disparity between US and Non-US roles is notable in high-tech jobs, which might be influenced by the concentration of tech industries in the US. 

![nonus](https://github.com/user-attachments/assets/637043cb-e385-4922-9fd6-fde9d9ab36cc)

**🤔 So What**

* These salary insights are important for planning and salary negotiations, which helps professionals and companies align their offers with market standards while considering geographical variations.

## 3️⃣ What are the top skills of data professionals?

**🔧 Skill: Power Pivot**

**💪 Power Pivot**

* A data model by was created by integrating the data_jobs_all and data_jobs_skills tables into one model.
* Power Pivot then created a relationship between these two tables.

**🔗 Data Model**

* A relationship was created between the two tables using the job_idcolumn. 
  
**📃 Power Pivot Menu**

* The Power Pivot menu was used to refine my data model and makes it easy to create measures. 
  
**📊Analysis**

**Insights**

* SQL and Python dominate as top skills in data-related jobs.
* Emerging technologies like AWS and Azure also show significant presence, which highlights the industry's shift towards cloud services and big data technologies. 

![top_skills](https://github.com/user-attachments/assets/3ceb7993-684c-4f36-a7c2-e75c275e8cb5)

**🤔So What**

* Professionals stay competitive, and training and educational programs are guided into focusing on the most impactful technologies.

## 4️⃣ What’s the pay of the top 10 skills?

**📊 Skill: Advanced Charts (Pivot Chart)**

**📈 PivotChart**

*  A combo PivotChart was created to plot median salary and skill likelihood (%) from my PivotTable.
    * Primary Axis: Median Salary (as a Clustered Column)
    * Secondary Axis: Skill Likelihood (as a Line with Markers)
* To customize the chart, I added a title axis title, removed the lines (skill likelihood), and changed the markers to diamonds.

**📊 Analysis**

**Insights**

* Higher median salaries are associated with skills like Python, Oracle, and SQL.
* Skills including PowerPoint and Word have the lowest median salaries and likelihood.

![top_10](https://github.com/user-attachments/assets/41365a4a-a4f0-4a79-a92b-0179cb28f9ab)

**🤔So What**

* The chart highlights the importance of investing time in learning high-value skills like Python and SQL, which are evidently tied to higher paying roles, especially for those looking to maximize their salary in the tech industry.

## Conclusion

By exploring Excel features like charts, Power Query, PivotTables and DAX, key correlations between multiple skills and higher salaries, particularly in Python, SQL, and cloud technologies were found. And all using a dataset involving data science job postings from 2023.
