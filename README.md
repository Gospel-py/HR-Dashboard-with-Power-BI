# HR-Dashboard-with-Power-BI

## **Overview**  
This project focuses on building an HR Analytics Dashboard for a fictitious company called Atlas Labs. The dashboard is designed to provide insights into different aspects of the workforce, such as employee demographics, attrition trends, job roles, and performance metrics. The goal is to turn raw HR data into clear and useful information that can help the company make better decisions about employee retention, diversity, and workforce management.

## **Project Objectives**  
The goal of this project is to:  
✅ Analyze **employee performance trends** using different rating levels.  
✅ Track **attrition rates** to identify factors contributing to employee turnover.  
✅ Explore **employee satisfaction** across different departments.  
✅ Provide insights into **diversity metrics** and **demographic distributions**.  
✅ Develop an interactive **Power BI dashboard** for easy data exploration.  

## **Datasets Used**  
The project uses multiple CSV files containing HR-related data:  
- **Educationlevel.csv** – Employee education levels.  
- **Employee.csv** – General employee information.  
- **performancerating.csv** – Employee performance scores.  
- **RatingLevel.csv** – Performance rating levels.  
- **SatisfyLevel.csv** – Employee satisfaction ratings.  

## **Key Features & Steps**  
1️⃣ **Data Preparation:**  
   - Imported datasets into **Power BI**.  
   - Created a **DimDate** table for handling date-based analysis.  
   - Established relationships between tables for proper data integration.  

2️⃣ **Data Modeling & Measures:**  
   - Defined **calculated measures** for attrition rate, average performance, and employee count using **DAX**.  
   - Created necessary **relationships** between fact and dimension tables.  

3️⃣ **Dashboard Design:**  
The dashboard consists of **four key pages**:  
🔹 **Overview:** High-level insights into key HR metrics.  
🔹 **Demographics:** Breakdown of employee distribution by gender, department, and education.  
🔹 **Performance Tracker:** Visualization of performance ratings and trends.  
🔹 **Attrition Analysis:** Factors influencing employee attrition and retention.  

4️⃣ **Visualizations & Insights:**  
   - **Stacked Column Charts** – To compare attrition rates across departments.  
   - **Treemaps** – To analyze performance by department.  
   - **Line Charts** – To track performance trends over time.  
   - **KPI Cards** – To highlight key HR metrics at a glance.

![Image](https://github.com/user-attachments/assets/a7156dc8-1f05-4fa6-bf47-d12a11f94965)

![Image](https://github.com/user-attachments/assets/a8b7e085-db91-4a31-8011-fed1b1ba0404)

![Image](https://github.com/user-attachments/assets/7431c3a9-a2da-44f3-96d8-830c2a228000)

![Image](https://github.com/user-attachments/assets/fe4e433f-fdcb-4201-acf6-81ef49c4f0c4)

## **Results & Findings**  
- Atlas Labs has a total workforce of 1,470 employees.
- Out of these, 1,233 employees are currently active, while 237 employees have left the company.
- The Technology department has the highest number of active employees. However, when categorized by job role, Sales Executives have the most active employees, followed by Software Engineers.
- The company's attrition rate stands at 16%, indicating the percentage of employees who have left the organization.
- The youngest employee at Atlas Labs is 18 years old, while the oldest is 51.
- The majority of employees fall within the 20–29 age range.
- Both male and female employees are well-represented across all age groups. However, males dominate among employees aged 50 and above, while females are more prevalent among those aged 20 and below.
- Most employees are married, followed by single employees, with divorced employees being the least represented.
- White employees earn the highest salaries, while Native Hawaiians and employees from other ethnic backgrounds earn the lowest.
- The overall attrition rate at Atlas Labs is 16.1%.
- Sales Representatives experience the highest attrition rate among all job roles.
- Employees with a tenure of 0–1 year have the highest attrition rate compared to other tenure groups.
- Employees hired in 2016 and 2020 had the highest turnover rates.
- Employees required to work overtime had a higher attrition rate than those who didn't.
- Employees with frequent travel requirements had the highest attrition rate, followed by those with some travel requirements. Employees with no travel requirement had the lowest attrition rate. However, the largest share of employees fell into the "some travel" category, while the "no travel" category had the fewest employees.

## **How to Use the Dashboard**  
1️⃣  Open **Power BI Desktop**.  
2️⃣  Load the provided datasets.  
3️⃣  Open the **HR Analytics Dashboard** file (.pbix).  
4️⃣  Interact with filters and visualizations to explore insights.  

## **Tools & Technologies Used**  
🟢 **Power BI** – Data modelling, Data visualization & dashboard creation.  
🟢 **DAX (Data Analysis Expressions)** – For calculated measures.  

