# Customer-Demographics-Bike-Sales

## Project Overview
This project presents an end-to-end data analysis solution using Microsoft Excel. The objective was to transform a raw dataset of customer demographics into a clean, structured format and build an interactive dashboard. The dashboard helps identify key factors—such as income, age brackets, and commute distance—that influence a customer's decision to purchase a bike.

##  Repository Structure
* **`Customer_Bike_Sales_Dashboard.xlsx`**: The core Excel workbook containing:
  * `bike_buyers`: The raw, unaltered dataset.
  * `working sheet`: The cleaned data with standardized values and newly engineered features.
  * `pivot table`: Aggregated data architectures driving the charts.
  * `dashboard`: The final interactive visual workspace for stakeholders.

---

## 🛠️ Data Architecture & Cleaning Process
Before building any visuals, the raw data underwent a thorough preparation process in the **working sheet** to ensure absolute data integrity:

1. **Duplicate Management:** Identified and removed redundant rows to avoid skewing metrics.
2. **Value Standardization:** 
   * Transformed the `Marital Status` column (`M` / `S`) to clear full text (`Married` / `Single`).
   * Transformed the `Gender` column (`M` / `F`) to full text (`Male` / `Female`).
3. **Data Type Correction:** Converted the `Income` field to a proper currency format for accurate mathematical calculations.
4. **Feature Engineering (Age Brackets):** Grouped the continuous `Age` column into distinct custom categories using conditional logic to make demographic tracking cleaner:
   * **Adolescent:** Under 30
   * **Middle Age:** 31–54
   * **Old:** 55+

---

##  Dashboard Features & Insights
The **dashboard** sheet integrates aligned PivotCharts and dynamic Slicers, allowing users to filter data seamlessly by region, education, or marital status. Key focus areas include:

* **Average Income Per Person:** Breaks down the financial profile of bike buyers vs. non-buyers, segmented by gender.
* **Customer Age Brackets:** Pinpoints which age demographics have the highest conversion rates (with Middle-Aged individuals showing strong purchasing patterns).
* **Customer Commute Distance:** Visualizes how daily travel distance correlates with bike buying behavior, showing distinct drops in sales as commute distances increase past 5–10 miles.

---

##  Key Takeaways & Skills Demonstrated
* **Data Cleansing:** Handling missing entries, duplicate extraction, and structural text transformations.
* **Analytical Modeling:** Building functional PivotTables and engineering custom criteria fields.
* **UX/UI Dashboard Design:** Applying layout principles, unified color choices, object alignment, and interactive slice filters for stakeholder usability.
