🚚 Logistics Analytics Dashboard – OTIF Performance
📌 Project Overview

This project presents a Logistics Performance Dashboard focused on OTIF (On-Time In-Full) analysis.

The dashboard provides end-to-end visibility into delivery performance, operational efficiency, and team-level execution metrics. It is designed to simulate a real-world enterprise logistics environment where operational KPIs directly impact service level agreements and customer satisfaction.

🎯 Business Objective

In logistics operations, OTIF is one of the most critical KPIs. Poor OTIF performance leads to:

  🟩 Customer dissatisfaction
  
  🟩 Increased operational costs
  
  🟩 Penalty charges
  
  🟩 Supply chain disruption

This dashboard helps stakeholders:

  🟩 Monitor monthly OTIF trends
  
  🟩 Analyze delivery performance (On-Time vs Late)
  
  🟩 Track order volumes and fulfillment rates
  
  🟩 Identify high and low performing teams
  
  🟩 Measure cycle time and operational efficiency

📊 Dashboard Features
1️⃣ OTIF KPI Summary

  🟩 OTIF %
  
  🟩 On-Time %
  
  🟩 In-Full %
  
  🟩 Visual gauge indicators for quick executive view

2️⃣ OTIF Performance Over Time

  🟩 Monthly trend comparison (Current Year vs Previous Year)
  
  🟩 Time intelligence analysis
  
  🟩 Performance fluctuation visibility

3️⃣ Orders Delivery Status

  🟩 On-Time vs Late distribution
  
  🟩 Monthly breakdown
  
  🟩 Volume-based performance insights

4️⃣ Operational KPIs

  🟩 Total Orders
  
  🟩 Delivered Orders
  
  🟩 Outstanding Orders
  
  🟩 Orders Fill Rate
  
  🟩 Orders Cycle Time

5️⃣ Top 5 Teams Performance

  🟩 Ranked OTIF performance by region/team
  
  🟩 Highlights operational variance across zones

🧠 Analytical Approach

The model simulates a structured logistics dataset including:

  🟩 Orders fact table
  
  🟩 Date dimension (Time intelligence enabled)
  
  🟩 Team hierarchy
  
  🟩 Performance metrics

Key analytical techniques used:

  🟩 DAX-based KPI calculations
  
  🟩 Time intelligence (YoY comparison)
  
  🟩 Dynamic measures
  
  🟩 Performance ranking
  
  🟩 KPI indicator visuals

🛠️ Technical Stack

  🟩 Power BI Desktop
  
  🟩 DAX
  
  🟩 Power Query (M)
  
  🟩 Star Schema Data Modeling
  
  🟩 Time Intelligence Functions

📈 Key KPIs Defined

OTIF % = On-Time % * In-Full %

On-Time % = Orders Delivered On-Time / Total Delivered

In-Full % = Orders Delivered In-Full / Total Delivered

Fill Rate = Average time in days between Order date and Electronic Bill of Lading

Order Cycle Time = Average time in days between Order date and delivery date

🏗️ Data Model

The solution follows a Star Schema design:

  🟩 Fact Table: Orders

Dimensions:

  🟩 Date
  
  🟩 Region / Team
  
  🟩 Customers

This structure ensures:

  🟩 High performance
  
  🟩 Scalability
  
  🟩 Clean relationship management
  
  🟩 Accurate aggregation behavior

🎨 Design Philosophy

The dashboard uses:

  🟩 Executive-friendly KPI cards
  
  🟩 Clear trend visualizations
  
  🟩 Regional comparison layout

  🟩 Dark theme for enterprise reporting feel
  
  🟩 Visual hierarchy for quick decision making

🤖 AI-Powered Insights (Power BI Native AI Visuals)

This dashboard leverages Microsoft Power BI’s built-in AI visuals to move beyond traditional reporting and enable intelligent data exploration.

🧩 Decomposition Tree

  🟩 The Decomposition Tree visual enables dynamic root cause analysis by allowing users to:
  
  🟩 Drill down into KPIs across multiple dimensions
  
  🟩 Automatically identify the highest or lowest contributing factors
  
  🟩 Perform AI-driven splits to uncover hidden patterns
  
  🟩 Interactively analyze logistics performance drivers

🔍 Key Influencers

The Key Influencers visual uses machine learning to determine which factors most significantly influence a selected metric.

In this dashboard, it helps:

  🟩 Identify drivers behind late deliveries or fulfillment performance
  
  🟩 Highlight variables that increase or decrease operational efficiency
  
  🟩 Provide statistically backed explanations instead of assumptions
  
  🟩 Quantify impact strength of different attributes
