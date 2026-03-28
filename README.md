# 📊 Strategic Online Sales Performance Dashboard

![Dashboard Preview](images/sales_dashboard.png)

## 📌 Project Overview
This project is an interactive, executive-level (C-Level) dashboard developed in Power BI. It is designed to monitor and analyze the strategic online and in-store sales performance for the company "AMC". The primary focus was combining robust data analysis with clean, minimalist UI/UX design principles to deliver actionable insights at a glance.

## 🚀 Key Features
* **Minimalist UI/UX Design:** Implementation of a strict corporate color palette (Deep Corporate Navy `#002D56`, Pure White, and Silver) to eliminate traditional Power BI visual clutter and enhance readability.
* **Dynamic Analytical Intelligence:** A responsive average line on the trend chart that automatically recalculates based on the selected timeframe and active filters.
* **Advanced DAX Conditional Formatting:** Utilization of the `RANKX` function to dynamically highlight the #1 top-selling category in the corporate brand color, automatically updating as filters change.
* **Seamless Navigation Panel:** Custom redesign of native slicers to act as a modern, fluid left-side navigation sidebar.
* **Data Trust Seal:** Integration of a custom Power Query script (`DateTime.LocalNow()`) to display the exact timestamp of the latest data refresh directly on the dashboard.

## 🛠️ Technologies Used
* **Data Visualization:** Microsoft Power BI Desktop
* **Data Transformation (ETL):** Power Query
* **Calculations & Logic:** DAX (Data Analysis Expressions) for advanced conditional formatting and BI metrics.

## 💡 Interactivity Demo

https://github.com/user-attachments/assets/ad390ce9-f56d-4d17-b075-8820c040483c

*Note: Notice how cross-filtering instantly updates the KPIs and the global map, and how the DAX-driven conditional formatting automatically highlights the category leader in real-time depending on the selected filters.*

## 📂 Data Structure
The underlying data model processes multidimensional sales transactions, including:
* **Metrics:** Net Revenue, Total Sales, Total Quantity, Return Status.
* **Dimensions:** Timeframe (Month/Year), Geography (Countries), Product Categories, and Sales Channels (Online vs. In-Store).

---
*This project was developed as an academic assignment, with a primary focus on UI/UX design, DAX functionality, and data visualization, rather than extensive data cleaning. The original dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset).*
