🚦 Australian Fatal Road Crash Analysis (2018–2023)

📌 Project Overview
This project analyzes fatal road crashes in Australia (2018–2023) using the Australian Road Deaths Database (ARDD). The goal was to build professional visualizations in Power BI to identify patterns, high-risk demographics, and peak times for crashes.

The project demonstrates end-to-end data cleaning, modeling, visualization, and storytelling, following real-world data analyst practices.

📊 Dataset
Source: Australian Road Deaths Database (public dataset).
Time Period: 2018–2023.

Key Features:
Crash ID (unique identifier)
State, SA4, LGA
Year, Month, Day of Week, Time of Day, Crash Hour
Crash Type, Road Type, Speed Limit
Holiday Flags (Christmas, Easter)
Age Group, Gender

🛠️ Data Preparation

Replaced placeholder values (-9) with “Unknown”.
Standardized state names (e.g., WA → Western Australia).
Created calculated columns:
YearMonth → trend analysis
Crash Hour → peak crash time
Holiday Period → Christmas, Easter, or Other
Defined measures:
Crash Count = DISTINCTCOUNT('Crash'[Crash ID])
Filtered data to 2018–2023 for recency.

📈 Dashboard Visuals

Crash Trends Over Time
Fatal crashes fluctuate monthly (70–114 crashes). Alt Text
Peaks observed in late 2023.

Heatmap – Day of Week × Time of Day Alt Text
Weekend afternoons/evenings (Fri–Sun, 3–6 PM) show the highest crash density.
Map – Geographic Distribution Alt Text
New South Wales, Victoria, and Queensland account for the majority of crashes.

Western Australia and Northern Territory show higher rates relative to population.
Crash Type & Vehicle Involvement
Single-vehicle crashes dominate.

Heavy vehicle (truck/bus) involvement is significant in multi-vehicle crashes.
Road Type & Speed Limit Alt Text
Highways and arterial roads are most dangerous.
100 km/h speed zones have the most crashes.

Holiday Effect
Only 3.5% of crashes occur during Christmas/Easter.
Majority (96%) occur outside major holidays.

Demographics – Age & Gender
Males dominate Crash across all age groups.
17–25 years is the riskiest group, followed by 40–64 and 26–39.

Peak Crash Hour (KPI)
Peak crash hour: 15:00 (3 PM) with 3,295 crashes.
Next highest: 16:00 and 17:00 → confirms afternoon/evening rush hour risk.

🔎 Key Insights

Time: Weekend afternoons/evenings (Fri–Sun, 3–6 PM) are the deadliest.
Location: NSW, VIC, QLD have the most crashes; NT/WA are high relative to population.
Crash Type: Single-vehicle and highway crashes dominate.
Demographics: Young males (17–25) are most at risk.
Holiday Effect: Holiday crashes get attention but account for only a small fraction.

📝 Conclusion

Dashboard Alt Text
This project highlights the importance of time, location, and demographics in fatal crashes. Insights support targeted:
Road safety campaigns for young drivers.
Weekend afternoon enforcement.

Highway safety improvements.
<img width="1376" height="769" alt="Screenshot 2025-09-29 195531" src="https://github.com/user-attachments/assets/df84f5ec-7d81-4a44-89a0-40fa8f7ba2ce" />


📂 Repository Structure /images # Dashboard screenshots Australia_Crash.pbix # Power BI project file README.md # Project documentation
🚀 Next Steps (Professional Expansion)
Add rolling averages and YOY comparisons.
Integrate population data to show crash rates per 100k residents.
Enable scheduled refresh with live datasets.
Build a Tableau version for cross-tool comparison.

<img width="1374" height="766" alt="Screenshot 2025-09-29 200401" src="https://github.com/user-attachments/assets/4c32325c-e532-47a6-a7f6-0b6602ded789" />


✅ With this project, I practiced real-world analyst skills: data cleaning, modeling, dashboard design, and storytelling — making it a strong addition to my data analytics portfolio.
