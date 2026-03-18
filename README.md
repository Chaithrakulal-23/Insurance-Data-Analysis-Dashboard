# Insurance Data Analysis Dashboard – Prism Insurance Pvt. Ltd.

### Dashboard Link : https://app.powerbi.com/links/mQEOwcTfN1?ctid=51697115-1ecd-42b5-b509-2d62c3919f76&pbi_source=linkShare

##  Project Overview
This project focuses on analyzing insurance data to understand customer behavior, policy distribution, and claim patterns.  
An interactive dashboard was built using Power BI to provide insights into premium amounts, claim status, and customer segmentation.

## Objectives
- Analyze insurance policies and claims data  
- Identify trends in premium and claim amounts  
- Segment customers based on age and activity status  
- Provide business insights for better decision-making  

---

##  Dataset Information
- Source: Excel File  
- Total Records: 10,000+ rows  
- Data includes:
  - Policy Number  
  - Claim Number  
  - Customer ID  
  - Premium Amount  
  - Coverage Amount  
  - Claim Amount  
  - Claim Status  
  - Gender  
  - Age  

---

##  Tools & Technologies Used
- SQL Server (Data Storage)
- Power BI (Dashboard & Visualization)
- Power Query (Data Cleaning & Transformation)

---


### Steps followed 

- Step 1 : Imported data from Excel into SQL Server 
- Step 2 : Load data into Power BI Desktop.
- Step 3 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : Created a conditional column for Age Group segmentation to analyze claim patterns across different age groups

![Age Group Column](https://github.com/Chaithrakulal-23/Insurance-Data-Analysis-Dashboard/blob/fc9b33dd7e3b61321aec2e76f2c5acc341568143/agegrp%20-%20Copy.png)
- Step 6 : Created a conditional column for  Active/Inactive customer classification  for count of active/inactive by active/inactive
![Active/Inactive Column](https://github.com/Chaithrakulal-23/Insurance-Data-Analysis-Dashboard/blob/fb321a3d3205169dbe7e6a496d638d77501930c0/activeinactive%20-%20Copy.png)

- Step 7 : Added slicers for Policy Number, Claim Number, and Customer ID to enable dynamic filtering of the dashboard

- Step 8 : Created KPI card visuals to display Total Premium Amount, Coverage Amount, and Claim Amount for quick insights

- Step 9 : Used a multi-row card visual to represent total number of male and female customers

- Step 10 : Added a ribbon chart to analyze distribution of different claim statuses

- Step 11 : Created a bar chart to visualize Premium Amount by Policy Type for identifying high-value policies

- Step 12 : Built a line chart to analyze Claim Amount trends across different age groups

- Step 13 : Added a donut chart to show distribution of Active vs Inactive customers

- Step 14 : Created a table visual to display Policy Type vs Claim Status with Coverage Amount

- Step 15 : Implemented drill-through functionality on Policy Type to enable detailed analysis on a separate page


![Drill Through](https://github.com/Chaithrakulal-23/Insurance-Data-Analysis-Dashboard/blob/4403898dd57c3605d3d937f58c0ae79c436f281d/drillthrough.png)

Two page report was created on Power BI Desktop & it was then published to Power BI Service.
 
![Publish_Message](https://github.com/Chaithrakulal-23/Insurance-Data-Analysis-Dashboard/blob/12a969801c18cbf8fcf1b11ab16d86f8285bb0a8/publisa.png)

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://user-images.githubusercontent.com/102996550/174096257-11f1aae5-203d-44fc-bfca-25d37faf3237.jpg)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://user-images.githubusercontent.com/102996550/174074051-4f08287a-0568-4fdf-8ac9-6762e0d8fa94.jpg)

# Insights
- Identified high premium generating policy types  
- Active customers contribute significantly to claim amounts  
- Certain age groups show higher claim trends  
- Claim status distribution highlights risk patterns  



