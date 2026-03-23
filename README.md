Insurance Policy Analysis Dashboard
📊 Project Overview
This project features an interactive Power BI Dashboard designed to analyze insurance policy data. The goal is to provide actionable insights into policyholder demographics, premium collections, sales team performance, and historical trends. By leveraging data modeling and dynamic filtering, the dashboard helps stakeholders monitor business health and identify growth opportunities.

🛠️ Tools & Technologies
Power Query : For data cleaning 
Power BI Desktop: For data transformation, modeling, and visualization.
DAX (Data Analysis Expressions): Used for creating custom measures and complex calculations.
Data Modeling: Implemented a Star Schema to optimize performance.
Microsoft Excel/CSV: Served as the primary data sources.

🗂️ Dataset Information
The analysis is built on a structured relational model including:
DM_Customer_Details:  (Customer_ID, Name, Gender, State etc.).
DM_Insurance_Agent:   (Agent code, Agent Mail,Sales Agent)
DM_Policy_Protection: (Business code, Number, Policy Code , Policy Name)
DM_Policy_Type: Categorization of insurance products.
DM_Regional/Zonal_Manager: Organizational hierarchy data.
FCT_Insurance_Policy_Transactions: The central fact table containing premium amounts, payments, and dates.

🚀 Key Features
Summary View: High-level KPIs showing total policies (7,299), 
total premium amount (\approx 39.10M), and annual/payable premiums.

Sales & Premium Analysis: Breakdown of premiums by Policy Type, State, and Occupation.

Sales Hierarchy Analysis: A deep dive into performance from Zonal Managers down to individual Sales Agents.

Yearly Trend Analysis: Comparative bar charts showing yearly performance across premium categories.

Interactive Slicers: Dynamic filtering by Year, Quarter, Occupation, and Policy Name.



📈 Dashboard Insights
Customer Segmentation: Identifies high-value customers based on premium contributions.

Geographic Performance: Visualizes which states are driving the highest revenue.

Sales Efficiency: Tracks which agents and managers are meeting targets.

Trend Detection: Monitors how premium payments fluctuate year-over-year.

   
How to Use
Clone this repository.
Open the .pbix file in Power BI Desktop.


Author
Developed by [Ganesh Ingle] Data Analyst | Power BI Developer

 1 Summary of Policy Holders
<img width="1920" height="1080" alt="Screenshot 2026-03-17 140739" src="https://github.com/user-attachments/assets/6b80d478-8a80-426e-aa72-9e7c24832857" />

2 Sales & Premium Analysis
<img width="1920" height="1080" alt="Screenshot 2026-03-17 141057" src="https://github.com/user-attachments/assets/6a556350-1079-4eb2-a570-baf9db97139a" />

3) Sales Hierarchy Analysis 
<img width="1920" height="1080" alt="Screenshot 2026-03-17 141144" src="https://github.com/user-attachments/assets/cb5f0fe0-6a40-4ec8-96d8-d16b8b3cbefb" />


<img width="1920" height="1080" alt="Screenshot 2026-03-17 141159" src="https://github.com/user-attachments/assets/cfbfc3f2-c1c5-4e9e-aa85-f584b6ff3923" />




