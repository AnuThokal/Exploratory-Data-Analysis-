#  Messy Clinic Appointment Dataset(Excel) :
An interactive Excel dashboard that tracks patient visits and billing amounts across hospital departments, built with pivot tables, dynamic formulas, and slicers for real-time filtering.
📊 # **Dashboard Preview** #
<img width="1897" height="969" alt="Screenshot (74)" src="https://github.com/user-attachments/assets/f540a66b-37eb-4ddb-808a-34975c0bd50b" />
🧾 # **Overview** 
This project analyzes hospital data across four departments — Cardiology, General, Neurology, and Orthopedics — covering patient counts, billing amounts, and demographic breakdowns. The dashboard is fully interactive: selecting a department or month updates every connected chart instantly.
✨# **Key Features**
-Department & Month Slicers :<img width="632" height="70" alt="74" src="https://github.com/user-attachments/assets/64528810-ba7b-4051-8d3e-2f699042fd62" />
 filter the entire dashboard by department or by month, with all charts updating together
 -Waterfall Chart :
 <img width="368" height="164" alt="75" src="https://github.com/user-attachments/assets/a8595857-15a1-4888-8463-6f1f820cb6a1" />
shows each department's contribution to the total billing amount, building up to the Grand Total
-Treemap Chart :<img width="304" height="143" alt="76" src="https://github.com/user-attachments/assets/ed4d3723-2677-4daa-a6d5-31dd395f1a12" />
visualizes department-wise patient volume at a glance
-Quarterly Trend Chart :
<img width="320" height="125" alt="77" src="https://github.com/user-attachments/assets/ba289b94-f9e3-4993-be01-6e526060b06c" />
tracks total amount across Qtr1–Qtr4
-Male vs Female Patient Breakdown :
<img width="288" height="167" alt="78" src="https://github.com/user-attachments/assets/46fcc231-be09-44a0-87ea-1b3621e72068" />
compares patient demographics by age group (Adult, Senior, Teenager).
-Dynamic Chart Titles — titles update automatically based on filtered data (e.g. peak quarter, top-contributing department
🛠️ # **Tools & Techniques Used**
-Pivot Tables & Pivot Charts
-GETPIVOTDATA (dynamic, error-safe cell references)
-Slicers (single and multi-chart connections via Report Connections)
-Waterfall and Treemap chart types
-Dynamic chart titles linked to formula cells
-Conditional formatting & custom slicer styling
💡 # **Insights Highlighted**
-Which department contributes the most to total billing amount
-Seasonal/quarterly trends in billing
-Patient demographic split by department and age group
-Department-wise patient load comparison
