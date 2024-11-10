# Employee-Health-Incentive-Dashboard
Project Overview

The Employee Health Incentive Dashboard is a dynamic and insightful tool developed in Power BI. This dashboard aims to analyze employee absenteeism patterns, reasons for absences, and related compensation data. The project is designed to provide HR professionals and management with a comprehensive view of how health incentives might impact employee attendance, helping to make data-driven decisions that enhance workforce wellness and productivity.


Data Processing

To streamline analysis, data from multiple sources was processed and transformed in SQL before being imported into Power BI. This approach allowed for efficient handling of various datasets, including absenteeism records, compensation details, and reasons for absences, all in one unified table.

    Data Integration: The absenteeism, compensation, and reason tables were joined using SQL to form a single table. This integrated table allowed for comprehensive analysis by linking employee IDs across the datasets and matching absenteeism reasons with their descriptions.

    Identifying Key Employee Groups: An additional SQL query was used to identify employees who might be eligible for health incentives. Criteria included non-drinkers, non-smokers, individuals with a healthy BMI, and those with below-average absenteeism hours. This selection aimed to help recognize employees contributing positively to workplace health and attendance.

    Categorizing Data for Enhanced Analysis: The final SQL query consolidated all required data fields into one table, adding categories like BMI Classification (e.g., Underweight, Healthy, Overweight, Obese) and Season of Absence (Winter, Summer, Monsoon, Post-Monsoon/Fall) to help analyze absenteeism trends by health and seasonal factors. This categorization enriched the dataset with additional insights before visualization.

    Importing into Power BI: The joined table was imported into Power BI using Power BI Query. This minimized data handling within Power BI, as all the necessary joins, classifications, and filters were already set in SQL. Consequently, this streamlined import enhanced the performance and usability of the dashboard in Power BI, ensuring quick insights and seamless interaction with the data.
    
Conclusion

The Employee Health Incentive Dashboard provides a foundational tool for organizations to improve their understanding of absenteeism drivers and the role of health incentives. By enabling data-driven decisions, the dashboard supports proactive management of employee wellness.

![HRA_0](https://github.com/user-attachments/assets/02e5eca5-c2f8-4c67-bd5c-be702c59d190)

![HRA_1](https://github.com/user-attachments/assets/a6aec7dc-8039-4c7f-92a7-414f3b4b5818)

![HRA_2](https://github.com/user-attachments/assets/7360e895-af4c-4c3e-a532-135b05e09646)

![HRA_3](https://github.com/user-attachments/assets/7d96e395-8042-4f15-af1c-9794f3e22857)
