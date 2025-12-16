# 🚗 Global EV Sales Analysis (2010–2024) | Power BI Dashboard

## 📌 Project Overview
This project analyzes **global Electric Vehicle (EV) adoption trends from 2010 to 2024** using Power BI.  
The objective is to provide **data-driven insights** into EV sales, stock growth, powertrain adoption, regional performance, charging infrastructure expansion, and energy demand to support **business, policy, and strategic decision-making**.

---

## 🎯 Objectives
- Analyze global EV adoption trends over time (2010–2024)
- Identify regional differences in EV sales and stock
- Analyze EV growth across vehicle categories and transport modes
- Compare powertrain adoption trends (BEV, PHEV, FCEV)
- Evaluate key EV-related parameters such as charging infrastructure and electricity demand
- Perform time-series and comparative analysis
- Provide actionable insights for strategic planning

---

## 📂 Dataset
- **Source:** IEA Global EV Data  
- **Time Period:** 2010–2024  
- **Data Type:** Historical data (projection scenarios filtered out)

### Key Columns
- `region` – Country or geographic region  
- `category` – Historical or projection scenario  
- `parameter` – EV metric (stock, sales, charging points, energy demand, etc.)  
- `mode` – Vehicle type (Cars, Buses, Vans, Trucks)  
- `powertrain` – EV technology (BEV, PHEV, FCEV, charging types)  
- `year` – Calendar year  
- `unit` – Measurement unit  
- `value` – Numeric measurement of the parameter  

---

## 🧹 Data Cleaning & Preparation
- Removed aggregated regions such as **World** and **Rest of World** to avoid double-counting
- Filtered dataset strictly to **2010–2024**
- Created a `transport_type` column (Passenger vs Freight)
- Created a `development_status` column (Developed vs Developing countries)
- Handled multiple units and parameter-specific aggregations carefully

---

## 📊 Dashboard Pages

### 1️⃣ Main Dashboard
- Key KPIs: Total EV Sales, Total EV Stock, Top Region, Top Powertrain
- Global EV stock growth trends
- BEV vs PHEV comparison
- Charging infrastructure growth
- EV energy demand trends
- Future EV stock projection

### 2️⃣ Regional & Category Trends
- Region-wise EV adoption
- EV penetration across vehicle categories
- Developed vs Developing region comparison
- Category dominance by region

### 3️⃣ Powertrain & Mode Insights
- Powertrain adoption across transport modes
- Passenger vs Freight EV comparison
- Powertrain growth trends
- Mode–powertrain combinations by region

### 4️⃣ Parameter & Unit Analysis
- Frequency of EV parameters
- Charging infrastructure distribution
- Electricity demand trends
- Unit-wise metric analysis

### 5️⃣ Time Series & Comparative Analysis
- Year-over-year EV growth
- CAGR analysis
- Peak adoption years
- Long-term EV trends

---

## 🔑 Key Business Insights
- China leads global EV adoption, followed by Europe and the USA
- Passenger vehicles dominate EV growth; freight electrification lags
- BEVs are the most widely adopted powertrain
- Developed countries show faster and more consistent EV growth
- Charging infrastructure and electricity demand are increasing rapidly
- EV adoption shows exponential growth post-2017
- Significant regional and mode-wise disparities exist

---

## ⚠️ Challenges Faced
- Limited dataset coverage for some regions and vehicle modes
- Skewed data distribution across regions
- Lack of monthly or quarterly granularity
- Ambiguity in the `value` column due to mixed metrics
- Multiple units and parameter-specific aggregation challenges

---

## ✅ Conclusion
The project highlights the rapid global transition toward electric mobility, driven primarily by passenger vehicles and BEV technology. While developed regions lead adoption, developing countries present strong future potential. Continued investment in infrastructure, renewable energy, and targeted EV policies is essential for sustainable growth.

---

## 🛠 Tools & Technologies
- Power BI
- Power Query
- DAX
- Microsoft Excel
- GitHub

---

## 📁 Repository Contents
- `Global EV Sales 2010–2024.pbix` – Power BI dashboard file  
- `IEA Global EV Data 2024.csv` – Dataset  
- `README.md` – Project documentation  
- Dashboard screenshots  

2. Open it using **Power BI Desktop**  
3. Use filters and slicers to explore insights  
