# Project Title:
Optimizing Order Fulfillment: A Data-Driven Approach to Eliminate Backlogs with an Excel Interactive Dashboard

# Company Overview
Streamline Logistics Solutions is a fast-growing logistics and delivery company specializing in order fulfillment across multiple zones. The company coordinates a fleet of vans, bikes, and trucks to ensure efficient last-mile delivery. As a service-driven organization, Streamline Logistics prioritizes customer satisfaction, operational excellence, and real-time visibility into logistics performance.

## Problem Statement
Despite a functional delivery operation, the company faced significant challenges in its supply chain processes, including rising backlogs, delivery delays, inefficient resource allocation, and lack of visibility into order progress. These inefficiencies threatened customer satisfaction, increased operational costs, and risked damaging the company’s industry reputation.

## Aim and Purpose of the Project
The goal of this project was to develop a robust, Excel-based interactive dashboard to streamline order fulfillment and improve decision-making. The dashboard would serve as a central tool for tracking key metrics, optimizing resource deployment, identifying performance bottlenecks, and enhancing communication. Ultimately, the project aimed to eliminate backlogs, reduce delivery delays, and support strategic planning with actionable insights.

# Data Cleaning and Automation Process
To ensure accuracy and reliability in the analysis, raw logistics data was first cleaned and structured using Excel Power Query. 

This involved:
- Removing duplicates and filtering incomplete or irrelevant records.
- Standardizing date and time formats to calculate delivery durations accurately.
- Normalizing location and driver data for consistency across entries.
- Handling missing values through logical imputation and validation.
- After cleaning, key performance indicators (KPIs) such as order completion rate, average delivery time, and delay frequency were automated using advanced Excel formulas and named ranges.
- Additionally, Office Scripts were used to auto-generate weekly KPI summary reports with visualizations, streamlining repetitive reporting tasks and saving manual effort.

  A Figure Below shows a screenshot of the Raw Data.

  ![Image](https://github.com/user-attachments/assets/d84a1483-d576-4b6f-ab10-d10fa87ebc9a)

# Interactive Excel-based Bashboard
An interactive Excel-based dashboard was developed to present real-time insights into order fulfillment performance. 

The dashboard featured:

- Dynamic charts and pivot tables for visualizing trends in delivery times, order volumes, and zone-based performance.

- Slicers and dropdown filters to allow users to drill down by date, driver, delivery zone, and transport method.

- Conditional formatting to highlight performance issues such as delays, backlogs, and underperforming drivers.

- Automated refresh features for up-to-date data visualization with every data import.

These visualizations enhanced decision-making by transforming raw data into intuitive, actionable insights tailored to operations and logistics management.

![Image](https://github.com/user-attachments/assets/9697f249-cc13-416f-beb6-34b54429e3ba)

# Delivery Performance Insights & Strategic Recommendations
## Key Insights
- Driver Delays: Drivers D86, D44, and D29 have the highest rates of late deliveries. Possible causes include poor route knowledge, vehicle issues, or lack of motivation.

- Zone 2 Bottlenecks: Zone 2 is the most delayed area, especially on Wednesdays and Thursdays. Route 3 is a congestion hotspot.

- Order Backlog: 767 current orders are overdue, showing the need for better planning and resource allocation.

- Customer Feedback: Surprisingly, late deliveries received more positive feedback than on-time ones—pointing to issues like driver behavior or poor delivery handling.

- Transport Issues: Vans outperform motorbikes. Bikes show the highest delays, often due to poor maintenance and inefficient routing.

- Policy Flaws: The “Expedited Rule Clears” policy meant to speed up orders is causing more delays and needs a redesign.

## Recommendations at a Glance
Improve Driver Performance:
- Provide one-on-one reviews and targeted route training.
- Introduce performance incentives and mentorship programs.
- Launch a feedback system to track driver behavior.

Optimize Routes:
- Avoid congested Route 3; use route-mapping tools like Route XL or OpenRouteService.
- Reschedule some Zone 2/3 deliveries to off-peak hours or alternate days.

Balance Weekly Loads:
- Spread deliveries more evenly across the week to ease midweek pressure.

Clear the Backlog:
- Prioritize high-delay zones and use efficient vehicles like Van A.
- Use forecasting to better plan capacity and deliveries.

Upgrade the Fleet:
- Replace or maintain underperforming bikes and trucks.
- Assign skilled drivers to problem vehicles for better results.

Improve Customer Service:
- Engage customers directly post-delivery for feedback.
- Address complaints tied to driver conduct or product condition.

Fix Policy Gaps:
- Review and revise the expedited delivery policy based on performance data.

## Conclusion
Streamline Logistics has strong potential but needs strategic improvements to boost delivery speed, reliability, and customer satisfaction. 
These insights and actions aim to enhance operations and preserve the company’s reputation for excellence in logistics.
