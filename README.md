# Coffee-analysis-Excel
End-to-End Dynamic Coffee Sales Dashboard in Excel

# Coffee Sales Analysis Dashboard

## Project Objective

End-to-end Excel solution transforming 1,000+ raw transactional logs into a dynamic decision-support tool. The project focused on data normalization, relational mapping, and multi-axis visualization of sales performance.

## Technical Implementation

### Data Engineering & ETL

Consolidated three disparate datasets (Orders, Customers, Products) into a unified fact table using **XLOOKUP** and **INDEX/MATCH**.
Implemented two-way matrix lookups (INDEX & Double MATCH) to automate attribute retrieval for Product IDs and Column Headers, reducing manual data entry requirements.
Applied nested **IF** logic to standardize categorical variables and handle null values/zeros in the customer email and product fields.
Converted flat ranges into **Excel Tables** to ensure 100% dynamic range expansion for all downstream pivot dependencies.

Pivot Tables Architecture:
Structured multiple pivot tables to aggregate sum of sales by coffee species, geographic region (US, UK, Ireland), and customer volume.

Connected 3 **Slicers** (Roast Type, Size, Loyalty Status) and 1 **Timeline** via Report Connections to enable synchronized filtering across all visual components.

## Impact

* **Reporting Efficiency:** Reduced manual data aggregation time by an estimated **90%** through automated lookup arrays and pivot table refresh logic.
* **Data Integrity:** Eliminated **duplicate entries** and standardized 4 distinct product categories via nested logical functions.
* **Scalability:** System architecture supports **infinite data row expansion** without requiring formula rewrites due to structured table referencing.
* **Dimensional Analysis:** Enabled instantaneous cross-sectional analysis across **4 coffee species, 3 roast types, 4 package sizes, and 3 international markets**.


## Dashboard
<img width="1328" height="645" alt="image" src="https://github.com/user-attachments/assets/17c68a79-396d-46c5-aa56-bee693830d89" />






**Would you like me to condense this further into a 3-bullet "Projects" entry for your resume?**
