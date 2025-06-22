# Deloitte_data_analytics_virtual_internship
📊 Deloitte Data Analytics Virtual Internship (Forage)
🧑‍💼 Completed by: Dharshini

📝 Overview
This repository contains my submissions for the Deloitte Data Analytics Virtual Internship, hosted by Forage. The internship simulated real-world data analytics projects handled by consultants at Deloitte.

I worked on two key tasks:

Telemetry Data Analysis using Tableau

Employee Compensation Fairness Analysis using Excel

📁 Project 1: Telemetry Data Dashboard (Tableau)
🔍 Objective
Analyze machine telemetry data collected from 4 global factories of Daikibo Corp to determine:

Which factory had the most machine breakdowns (downtime)?

Which device types broke most often in that factory?

🛠️ Tools Used
Tableau Public

JSON (data source)

📌 Steps Followed
Imported daikibo-telemetry-data.json into Tableau

Created a calculated field:
Unhealthy = 10 (10 mins of downtime per unhealthy status)

Built two charts:

Down Time per Factory (bar chart)

Down Time per Device Type (bar chart)

Created a dashboard combining both sheets

Set factory bar chart as a filter for device types



📁 Project 2: Equality Score Classification (Excel)
🔍 Objective
Classify job roles across factories based on Equality Score (ranging -100 to +100) into:

Fair (±10)

Unfair (±11 to ±20)

Highly Discriminative (>±20)

🛠️ Tools Used
Microsoft Excel (formulas, formatting, charts)

📌 Steps Followed
Cleaned and analyzed the dataset Equality Table.xlsx

Added a new column Equality Class using formula:

excel
Copy
Edit
=IF(ABS(C2)<=10, "Fair", IF(ABS(C2)<=20, "Unfair", "Highly Discriminative"))
Used PivotTables and Charts to summarize and visualize the classification

📊 Sample Output
Factory	Job Role	Equality Score	Equality Class
Tokyo	Engineer	-8	Fair
Berlin	Manager	15	Unfair
Shenzhen	Operator	27	Highly Discriminative

✅ Key Takeaways
Built Tableau dashboards with interactive filters and calculated measures

Applied Excel techniques for data classification and visualization

Simulated real client-facing analytics scenarios

Strengthened data storytelling and insight generation skills
About the Internship
Provider: Deloitte (via Forage)

Type: Self-paced Virtual Internship

Modules: Data cleaning, dashboarding, data storytelling


