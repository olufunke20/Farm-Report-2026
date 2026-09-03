Farm-Report-2026
This project is an interactive Power BI Business Intelligence Dashboard designed to analyze resource consumption, input efficiency, and operational metrics across agricultural production units.   The report enables farm managers and agricultural analysts to track aggregate resource inputs (water, fertilizer, and pesticides) and evaluate variance across **crop types, soil classifications, and seasonal cycles** to optimize yield and resource allocation.
Key Metrics & KPIs Tracked
Total Farm Area: 12.75K acres monitored
Total Water Volume Utilized: 2.84M cubic meters across growing cycles
Input Distribution: High-level tracking of total fertilizer and pesticide applications
Yield Performance: Baseline yield tracking per production block

Core Analytical Dimensions
1. Water Usage by Crop Type
Breaks down water demand across individual crops (e.g., Maize, Wheat, Barley, Sugarcane) to identify high-consumption varieties.
Highlights resource-intensive crops requiring targeted irrigation scheduling.

2. Water Consumption by Seasonality
Evaluates volume swings across seasonal cycles (Kharif, Rabi, Summer/Zaid).
Uncovers peak seasonal strain on irrigation reserves.

3. Soil Type Efficiency
Compares water retention and absorption variance across Clay, Sandy, Loam, and Silt soil profiles.
Identifies which soil-crop pairings result in disproportionate resource overhead.

Technical Stack & Features
BI Platform: Microsoft Power BI
Data Modeling: Star-schema structure connecting dimension tables (Crop, Soil, Season) with operational fact logs.
DAX Measures: Custom calculated metrics for resource usage aggregation, average water volume per acre, and seasonal variance.
Interactivity: Dynamic multi-select slicers for **Soil Type**, **Crop Type**, and **Season** enabling instant drill-down without recalculation lag.
