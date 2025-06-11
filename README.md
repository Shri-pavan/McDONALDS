# McDonald's Business Performance Dashboard

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/McDonald%27s_Golden_Arches.svg/1200px-McDonald%27s_Golden_Arches.svg.png" alt="McDonald's Logo" width="120"/>
</p>

## 🚀 Project Overview

This project features a comprehensive business performance dashboard for McDonald's, providing a snapshot of key metrics across sales, profitability, and customer satisfaction. The dashboard visualizes pre-aggregated data to track performance against targets and compare results over time and across regions.

The repository contains the summarized data sheets that serve as the direct input for the dashboard components. The structure strongly indicates the original analysis and visualization were performed in **Microsoft Excel**.

## 📊 Dashboard & Charts Used

The dashboard is designed for executive-level review, translating raw numbers into actionable insights through a variety of targeted charts and KPIs.

* ### KPI Cards
    * **Description:** Displays the most critical top-line metrics: **Total Sales**, **Total Profit**, and **Total Customers**.
    * **Purpose:** To provide an immediate, at-a-glance understanding of overall business health.

* ### Gauge Charts
    * **Description:** Visualizes the **percentage completion** for Sales, Profit, and Customer targets.
    * **Purpose:** To clearly show how close the actual performance is to the set goal for each key metric.

* ### Grouped Column Chart
    * **Description:** Compares **monthly sales** between **2021 and 2022**. Each month has two bars, one for each year.
    * **Purpose:** To identify seasonal trends and track year-over-year growth on a monthly basis.

* ### Bar Chart
    * **Description:** Ranks **total sales by country** (e.g., Argentina, Colombia, Brazil).
    * **Purpose:** To easily identify the top-performing and underperforming countries in the region.

* ### Progress Bars or Horizontal Bar Chart
    * **Description:** Shows scores for different **customer satisfaction** categories, such as **Speed (54%)**, **Quality (86%)**, and **Hygiene (93%)**.
    * **Purpose:** To pinpoint specific areas of operational strength and weakness from the customer's perspective.

## 🛠️ Tools & Technologies

* **Primary Tool:** Microsoft Excel
* **Key Features Used:**
    * **PivotTables:** For creating the initial summary tables found in the `INPUTS.csv` file.
    * **Dashboarding & Charting:** Using a combination of Excel's charting capabilities to build the visuals.
    * **Formulas:** To calculate performance metrics like `% Complete` and `Remainder`.

## ⚙️ How to Use

1.  **Clone or download the repository.**
2.  **Review the Data:** The `McDonalds.xlsx - INPUTS.csv` file contains the summary tables used for the analysis.
3.  **Open the Master Excel File (if included):** If you have the master `.xlsx` workbook, open it to view the full interactive dashboard.
