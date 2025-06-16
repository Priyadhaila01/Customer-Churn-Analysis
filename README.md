# 📊 Customer Churn Analysis Dashboard

## 💼 Project Overview
This project presents an interactive **Customer Churn Analysis Dashboard** created using **Power BI**.  
👉 Data for this analysis was stored in a **PostgreSQL database**, and Power BI connected directly to PostgreSQL to visualize key churn metrics.  
The dashboard is designed to help identify churn patterns, track customer retention, and support decision-making regarding customer engagement strategies.


## 🛠 Tools & Technologies
- **PostgreSQL**: Used as the data source. Data was loaded into Power BI for building the visuals.
- **Power BI**: Used to create an interactive dashboard including KPIs, charts, and slicers.
- **DAX Measures**: Calculated KPIs like Churn Rate, Average Tenure, and Estimated LTV.



## 🌟 Dashboard Wireframe

+--------------------------------------------------------------+
| Dashboard Title: Customer Churn Analysis |
+--------------------------------------------------------------+
| Filters: plan_type | is_active (slider) |
+--------------------------------------------------------------+
| [ Churn Rate (%) KPI ] [ Avg Tenure KPI ] [ LTV KPI ] |
+--------------------------------------------------------------+
| Pie Chart: Churn Flag Distribution |
| Bar Chart: Churn by Region + Flag |
| Line Chart: Tenure Trend (Sum of Customer ID by Tenure) |
+--------------------------------------------------------------+


## 📝 Annotations

### 🟣 **Dashboard Title**
- Provides clear project context.

### 🟣 **Filters**
- `plan_type`: Filter customers by subscription type (Basic, Premium, Standard).
- `is_active`: Slider to filter based on customer activity status.

### 🟣 **KPIs**
- **Churn Rate (%)**: Percentage of customers who have churned. Quick view of business health.
- **Average Tenure of Churned Customers**: Average duration (in months) customers stayed before churning.
- **Estimated LTV**: Lifetime value estimate = Avg monthly fee × Avg tenure.

### 🟣 **Visuals**
- **Pie Chart (Churn Flag)**: Proportion of active vs churned customers.
- **Bar Chart (Churn by Region + Flag)**: Compare churn distribution across regions.
- **Line Chart (Tenure Trend)**: Show tenure trends over time (customer ID count by tenure months).


## ⚡ Notes
- This is a practice project built for **learning and skill development**.
- Power BI connected to PostgreSQL for live data; however, no saved SQL queries are included in this repo as transformations were done during the analysis session.
- All calculations for KPIs were implemented using **DAX measures** in Power BI.


## 📸 Dashboard Screenshot
<img width="494" alt="cvc" src="https://github.com/user-attachments/assets/9c491de9-f3b3-4d89-bc4b-ddaac7237b7c" />


## 📌 How to Use
1. Open Power BI file provided in this repo (if shared).
2. Connect to your own PostgreSQL or sample data source.
3. Explore filters, KPIs, and charts to analyze churn patterns.


## 📂 Data

You can download the sample data used for this project directly from the code section where the Excel file is shared in this repository.

The data represents customer churn records that were used to create the Power BI dashboard. The Excel file is provided so others can explore or rebuild the dashboard if desired.

⚠ **Note:** The Excel file contains data exported from PostgreSQL for the dashboard analysis. No SQL query files are included.


