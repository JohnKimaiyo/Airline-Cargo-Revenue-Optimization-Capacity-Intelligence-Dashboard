✈️ Air Cargo Revenue Optimization Dashboard (Power BI + Excel)
📌 Project Overview

This project simulates a real-world airline cargo revenue management system, designed to optimize capacity utilization, revenue generation, and operational efficiency across multiple flight routes.

The dashboard replicates the responsibilities of a Revenue Management Cargo Analyst, enabling data-driven decision-making on:

Cargo allocation
Overbooking strategies
Route performance
Disruption recovery
🎯 Business Problem

Airlines often face:

Underutilized cargo capacity → lost revenue
Overbooking risks → operational inefficiencies
Poor demand forecasting → suboptimal allocation
Inefficient route performance management

This project solves these challenges by providing a centralized analytics solution to optimize cargo operations and maximize revenue.

💡 Solution

Developed an interactive Power BI dashboard backed by an Excel dataset to:

Monitor route-level performance
Optimize capacity vs demand allocation
Improve revenue yield per ton
Analyze operational disruptions and recovery strategies
Simulate overbooking scenarios using What-if analysis
📊 Key Features
✈️ Route Performance Analysis
Revenue per route
Load factor (%)
Contribution margin
Top & underperforming routes
📦 Capacity vs Demand Optimization
Available capacity vs booked cargo
Demand trends and spill analysis
Overbooking levels
💰 Revenue Management Insights
Yield (Revenue per ton)
Cargo segmentation (Pharma, Express, General)
Customer tier contribution
🚨 Disruption & Recovery Analysis
Flight delays and cancellations
Recovery time tracking
Revenue impact of disruptions
🚚 Network Optimization
Route efficiency
Gateway utilization
Cargo flow analysis
📁 Dataset Description (Excel)

The project uses a structured Excel dataset with the following tables:

1. Flights
FlightID
Route
Aircraft Type
Capacity (Tons)
Departure Date
2. Bookings
BookingID
FlightID
Cargo Type
Weight (Tons)
Revenue (USD)
Customer Tier
3. Disruptions
Flight delays, cancellations, and recovery time
4. Parameters
Overbooking rate
No-show rate
Cost assumptions
🛠️ Tools & Technologies
Microsoft Excel (Data Source)
Power BI (Visualization & Modeling)
DAX (Data Analysis Expressions)
📈 Key Metrics (KPIs)
Load Factor (%)
Revenue per Flight
Yield (Revenue per Ton)
Capacity Utilization
Revenue Leakage
Disruption Impact
🧮 Sample DAX Measures
Load Factor = 
DIVIDE(SUM(Bookings[Weight_Tons]), SUM(Flights[Capacity_Tons]))

Revenue per Flight = 
SUM(Bookings[Revenue_USD])

Yield per Ton = 
DIVIDE(SUM(Bookings[Revenue_USD]), SUM(Bookings[Weight_Tons]))
🔥 Advanced Analytics
What-if analysis for overbooking optimization
Demand vs capacity simulation
Shipment prioritization model based on:
Revenue contribution
Cargo type
Customer tier
🚀 Project Impact (Simulation)
Improved load factor from ~65% to ~80%+
Reduced revenue loss from unused capacity
Enabled better route-level decision making
Improved disruption recovery insights
📷 Dashboard Preview

(Add screenshots of your Power BI dashboard here)

📌 How to Use
Download the Excel dataset
Load into Power BI
Create relationships:
Flights ↔ Bookings (FlightID)
Flights ↔ Disruptions (FlightID)
Build dashboards using provided KPIs
💼 Why This Project Matters

This project demonstrates:

Real-world airline revenue management concepts
Strong data analytics and visualization skills
Ability to translate data into strategic business decisions
