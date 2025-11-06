# 🚗 Car Sales Dashboard in Tableau
This Tableau project analyzes car sales data across multiple manufacturers and models to uncover insights into revenue generation, market share, pricing, and fuel efficiency trends. The interactive dashboard enables dynamic exploration using filters and parameters, making it a versatile tool for business intelligence and decision-making.

**🔍 Project Overview**
The purpose of this dashboard is to provide a clear and actionable visual analysis of car sales and performance metrics.
Key questions addressed:
Which car models and manufacturers generate the most revenue?
What are the market shares of different manufacturers?
How does pricing correlate with fuel efficiency and sales volume?
What are the top-performing vehicle models at different scales (Top 5, Top 10, Top 20, etc.)

**🛠️ Tools & Technologies**
Tool	Purpose
Tableau Desktop	Dashboard creation and visualization
CSV Dataset	Car sales data source
GitHub	Version control and portfolio documentation

**📊 Dashboard Features**
1. **Top N Models by Revenue**
Dynamic bar chart showing the top-performing car models.
Uses a user-driven parameter (Top N Models) to switch between the best 5, 10, or 20.
Includes a calculated ranking field and filter logic.
**2. Market Share by Manufacturer**
Pie chart showing how much revenue each manufacturer contributes.
Enhanced with percentage labels inside each slice.
**3. Performance  vs Weight**
Visual comparison of horse power  across weight (horsepower per 1000Ib).
Highlights brand differences with color-coded points.
**4. Interactive Filtering & Controls**
Global Top N parameter.
Filters for model, brand, and vehicle type where applicable.

**📂 Dataset**
Source: Car_sales.csv
Contains fields like:
Model, Manufacturer, Sales, Revenue_millions, Price_in_thousands, Fuel_efficiency, etc.

**🧠 Key Insights Derived**
1. Top Sales by Revenue (Bar Chart, Top Left)
Highest-grossing model: F-Series with revenue around $15K million.
Other top models: Explorer, Expedition, Ram Pickup, Taurus, Camry, Grand Cherokee, Caravan, Accord, Windstar—all below $10K million.
**Observation: Ford F-Series dominates revenue significantly compared to other models**.

2. Top Revenue by Manufacturer (Bar Chart, Bottom Left)
Top manufacturer: Ford leads with 2,023 thousand units sold.
Other high performers: Dodge (910k), Toyota (740k), Honda (593k), Chevrolet (554k), Nissan (400k).
Lower revenue brands: Acura, Volvo, Plymouth, BMW (under 100k units).
**Observation: Ford not only has a top-selling model but also leads overall sales by manufacturer.**

3. Market Share by Brand (Pie Chart, Top Right)
Largest market share: A single brand (likely Ford based on revenue) holds 25.43%.
Other notable shares: Dodge (10%), Toyota (7.38%), Chevrolet (5.34%), Honda (5.52%).
**Observation: Market share is concentrated, with a few brands dominating the auto market.**

4. Performance vs Weight (Scatter Plot, Bottom Right)
Trend: Higher horsepower per weight (HP_per_1000lb) generally corresponds to higher total horsepower.
Notable outliers:
Mercedes-B and Chevrolet are high in both HP and HP per 1000 lbs.
Lincoln shows lower horsepower relative to weight.
**Observation: Sports/performance-oriented models cluster in the top-right; economy/lighter vehicles cluster lower-left.**

5. **General Insights**
Ford is the clear market leader in both revenue and volume.
American brands like Dodge, Chevrolet, and Chrysler dominate in volume but performance varies widely.
The F-Series is an outlier in terms of revenue, suggesting high unit price or high sales volume.
Performance (HP) scales with weight, but exceptions like Mercedes-B indicate high-performance, heavier vehicles.
