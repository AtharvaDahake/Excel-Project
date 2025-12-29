# Excel-Project

Sales Performance Dashboard (Excel)
An interactive Excel dashboard to track sales performance by city and by sales executive, with KPIs for target achievement and variance.
Features

* City slicers: Filter the entire dashboard by city (Chennai, Delhi, Mumbai, Nagpur, Patna, Pune, Ranchi, Surat).
* Dashboard views (tabs): Four pre-set dashboard views for quick comparisons.
* Top performers: Ranked tables of sales executives by total sales, target hit %, and “away from target %.”
* Visuals:

Horizontal bar chart: top sales by executive.
Pie chart: contribution share by executive.
Line chart: target achievement trend (%).


* KPIs shown: Target Hit % and Away From Target % by executive.

File Structure (suggested)

* /dashboard – Excel file(s) with the interactive dashboard (e.g., Sales_Dashboard.xlsx).
* /data – Source data files (e.g., sales_data.csv).
* /images – Screenshots of the dashboard (optional).
* README.md – Project documentation (this file).

Requirements

* Microsoft Excel (365/2019 or later recommended).
* Enable macros if prompted (only if your file uses macros; remove this note otherwise).

How to Use

1. Open the Excel file in /dashboard.
2. If prompted, enable content (and macros, if applicable).
3. Use the city slicers at the top to filter the dashboard by location.
4. Use the Dashboard 1–4 buttons to switch between preset views.
5. Review:

Tables for top performers by sales, target hit %, and away-from-target %.
Bar chart for sales by executive.
Pie chart for contribution share.
Line chart for target achievement trend.



Updating the Data

1. Replace or append new records in the data table (or update the file in /data).
2. Refresh the workbook (Data → Refresh All) to update pivots/charts/slicers.
3. Verify that the slicers and views reflect the new data.

Notes on Metrics

* Total Sales: Sum of sales per executive.
* Target Hit %: Actual vs. target, shown as a percentage.
* Away From Target %: Shortfall vs. target, shown as a percentage.

Customization

* Modify slicer items to add/remove cities.
* Adjust charts or KPI logic in the pivot tables/data model as needed.
* Swap in your branding/colors in the chart formatting.

Contributing
Contributions are welcome. Please open an issue or submit a pull request with proposed changes.
License
Specify your license here (e.g., MIT).
