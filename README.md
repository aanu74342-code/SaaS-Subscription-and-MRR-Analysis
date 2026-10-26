1. Project Overview

The **SaaS Subscription & MRR Analysis** project is a data analytics dashboard developed using Microsoft Power BI. It analyzes subscription revenue, customer activity, subscription plans, IT support tickets, and service downtime.

The dashboard helps businesses understand their Monthly Recurring Revenue (MRR), monitor customer subscriptions, identify support issues, and analyze service performance.

2. Objectives

* Analyze Monthly Recurring Revenue (MRR).
* Monitor active and inactive customers.
* Compare revenue across subscription plans.
* Analyze subscription status.
* Track IT support tickets by priority.
* Monitor service downtime and its causes.
* Present business insights through interactive visualizations.

 3. Tools and Technologies

* **Microsoft Power BI Desktop** – Dashboard development
* **Power Query** – Data cleaning and transformation
* **DAX** – Calculated measures and KPIs
* **Microsoft Excel / CSV** – Dataset source

*This project uses Power BI features only; SQL and Python are not required.*

4. Dataset Description

The project contains five datasets:

| Dataset       | Description                                                      |
| ------------- | ---------------------------------------------------------------- |
| Customers     | Customer details, industry, region, and signup date              |
| Subscriptions | Subscription plans, prices, billing cycles, and payment status   |
| MRR Snapshot  | Monthly revenue, customer activity, and subscription information |
| IT Tickets    | Support tickets, priority, status, and resolution details        |
| Downtime      | Service downtime, affected services, severity, and root causes   |

The sample data is synthetic and intended for educational and demonstration purposes.

 5. Dashboard Features

* Total MRR KPI card
* Active Customers KPI card
* Monthly MRR trend line chart
* MRR by subscription plan bar chart
* Subscription status donut chart
* IT tickets by priority chart
* Downtime by service chart
* Interactive slicers for filtering and analysis

6. Methodology

1. Import the Excel or CSV datasets into Power BI Desktop.
2. Clean and transform data using Power Query.
3. Check column names and data types.
4. Create the required data relationships.
5. Create DAX measures for KPIs.
6. Build charts, cards, and slicers.
7. Format the dashboard with titles, colours, and borders.
8. Analyze the results and identify useful business insights.

7. Key Performance Indicators

* Total MRR:** Total monthly recurring revenue.
* Active Customers:** Number of active customers.
* Subscription Distribution:** Breakdown by subscription status and plan.
* Ticket Count:** Number of IT support tickets by priority.
* Total Downtime:** Total service downtime in minutes.

 8. Expected Outcomes

The dashboard provides a clear view of subscription revenue, customer activity, support ticket patterns, and service downtime. It helps users explore business performance and make data-driven decisions.

 9. How to Run the Project

1. Install Microsoft Power BI Desktop.
2. Download or clone this GitHub repository.
3. Open the provided Excel dataset.
4. Open the `.pbix` Power BI report file, if included.
5. If no `.pbix` file is included, open Power BI Desktop and import the dataset.
6. Refresh the data if necessary.
7. Explore the dashboard using charts and slicers.

 10. Project Structure

```text
SaaS-Subscription-MRR-Analysis/
│
├── Dataset/
│   └── saas_sample_dataset.xlsx
│
├── Dashboard/
│   └── SaaS_MRR_Analysis.pbix
│
├── Screenshots/
│   └── dashboard.png
│
└── README.md
```

11. Conclusion

This project demonstrates how Microsoft Power BI can transform subscription and IT operations data into an interactive analytical dashboard. It combines revenue analysis, customer monitoring, ticket analysis, and downtime tracking in one report.

Tools: Power BI Desktop, Power Query, DAX, Excel
