# Feeder Wise Load Analysis Dashboard
### Tool: Power BI 

Analyzed electricity feeder data to monitor load patterns, power quality, and KWH consumption across different day types and months.


## Dashboard Pages

### Page 1 — Feeder Load Analysis
**KPIs:**
- Avg Power Load: 1.66K
- Min Load: 486.97
- Max Load: 3.34K  
- Total KWH: 605.15K
- Load Category: Low Load

**Key Insights:**
- March = Highest Load Month
- September = Lowest Power Factor Month
- May = Highest Voltage Month
- Weekend = Peak Load Day Type

**Charts:**
- Line chart: Avg Power Load by Month
- Donut chart: Weekday (48.78%) vs Weekend (51.22%)

---------------------------------------------------------------------------------------
### Page 2 — Power Quality Analysis
**KPIs:**
- Avg Voltage: 11.60
- Avg Power Factor: 0.93
- PF Status: Average

**Charts:**
- Line chart: Average Voltage by Month
- Line chart: Total Current by Month
- Line chart: Average Power Factor by Month

**Finding:**
Power factor drops significantly in August-September (below 0.85) indicatingpoor power quality during these months.
Recommendation: Install capacitor banks to improve power factor.

-----------------------------------------------------------------------------------------------------------------------------------------------------
### Page 3 — KWH Consumption Analysis

**KPIs:**
- Total KWH: 605.15K
- Avg Power Load: 1.66K

**Charts:**
- Area chart: KWH Consumption Over Time
- Bar chart: Monthly KWH Consumption
- Bar chart: KWH by Day Type
- Table: Daily KWH Details

**Finding:**
- KWH consumption shows steady increase from May to December — suggesting growing electricity demand.
- Weekday KWH significantly higher than Weekend — indicating industrial/commercial load.
