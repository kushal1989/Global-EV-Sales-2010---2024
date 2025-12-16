🚗 Global EV Sales Analysis (2010–2024) | Power BI Dashboard
📌 Project Overview

This project analyzes global Electric Vehicle (EV) adoption trends from 2010 to 2024 using Power BI.
The goal is to provide data-driven insights into EV sales, stock growth, powertrain adoption, regional performance, charging infrastructure expansion, and energy demand to support business, policy, and strategic decision-making.

The dashboard is interactive and designed to help users explore EV trends across regions, vehicle categories, transport modes, and powertrain technologies.

🎯 Objectives

Analyze global EV adoption trends over time (2010–2024)

Identify regional differences in EV sales and stock

Compare EV growth across vehicle categories and transport modes

Analyze powertrain adoption (BEV, PHEV, FCEV)

Evaluate key EV-related parameters such as charging infrastructure and electricity demand

Perform time-series and comparative analysis

Provide actionable insights for businesses and policymakers

📂 Dataset

Source: IEA Global EV Data

Time Period: 2010–2024

Data Type: Historical data (projection scenarios filtered out)

Key Columns:

region – Country or geographic region

category – Historical or projection scenario

parameter – EV metric (stock, sales, charging points, energy demand, etc.)

mode – Vehicle type (Cars, Buses, Vans, Trucks)

powertrain – EV technology (BEV, PHEV, FCEV, charging types)

year – Calendar year

unit – Measurement unit

value – Numeric measurement of the parameter

🧹 Data Cleaning & Preparation

Removed aggregated regions like World and Rest of World to avoid double-counting

Filtered data strictly to 2010–2024

Created a transport_type column (Passenger vs Freight)

Created a development_status column (Developed vs Developing countries)

Handled multiple units and parameter-specific aggregations carefully

📊 Dashboard Pages & Insights
1️⃣ Main Dashboard

High-level KPIs: Total EV Sales, Total EV Stock, Top Region, Top Powertrain

Global EV growth trends

BEV vs PHEV comparison

Charging infrastructure growth

Energy demand trends

Future EV stock projection

2️⃣ Regional & Category Trends

EV adoption by region

EV penetration across vehicle categories

Developed vs Developing country comparison

Region-wise dominance analysis

3️⃣ Powertrain & Mode Insights

BEV, PHEV, FCEV adoption comparison

Passenger vs Freight EV analysis

Powertrain trends across transport modes

Mode-powertrain combinations by region

4️⃣ Parameter & Unit Analysis

Most reported EV parameters

Charging points and electricity demand trends

Unit distribution across EV metrics

Top contributing regions for each parameter

5️⃣ Time Series & Comparative Analysis

Year-over-year EV growth

CAGR analysis

Peak adoption years

Long-term EV stock and sales trends

🔑 Key Business Insights

China leads global EV adoption, followed by Europe and the USA

Passenger cars dominate EV adoption; freight electrification lags

BEVs are the most widely adopted and fastest-growing powertrain

Developed countries show faster and more consistent EV growth

Charging infrastructure and electricity demand are rising rapidly

EV adoption has grown exponentially after 2017

Significant regional and mode-wise disparities exist

⚠️ Challenges Faced

Limited dataset coverage for some regions and modes

Skewed data distribution across countries

Lack of monthly/quarterly data

Ambiguity in the value column due to mixed metrics

Multiple units and parameter-specific aggregation requirements

✅ Conclusion

The project highlights the rapid global transition toward electric mobility, driven primarily by passenger vehicles and BEV technology. While developed regions lead adoption, developing countries present strong future potential. Continued investment in charging infrastructure, renewable energy, and targeted EV policies is essential for sustainable growth.

🛠 Tools & Technologies

Power BI

Power Query

DAX

Microsoft Excel

GitHub

📁 Repository Contents

Global EV Sales 2010–2024.pbix – Power BI dashboard file

IEA Global EV Data 2024.csv – Dataset

README.md – Project documentation


Open using Power BI Desktop

Interact with slicers to explore insights
