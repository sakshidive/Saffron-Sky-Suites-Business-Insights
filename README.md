# Saffron-Sky-Suites-Business-Insights

## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Tools Used](#tools-used)
- [Data Source](#data-source)
- [Key Metrics](#key-metrics)
- [Key Visuals](#key-visuals)
- [Dashboard](#dashboard)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Outcomes](#outcomes)
- [Skills Learned](#skills-learned)
- [Conclusion](#conclusion)

## Project Overview 
**Saffron Sky Suites**, a luxury hotel chain, is leveraging a data-driven approach to regain market share and revenue in the competitive hospitality industry. This project features an interactive Power BI dashboard designed to analyze KPI's (key performance indicators) to deliver actionable business insights, enabling stakeholders to make data-driven decisions and improve operational performance.

## Problem Statement 
**Saffron Sky Suites**, a leader in the hospitality industry for over 20 years, owns multiple five-star hotels across India. Recently, the company has experienced a decline in market share and revenue due to strategic advancements by competitors and ineffective management decisions. Recognizing the need for **Business and Data Intelligence**, the management has adopted a data-driven approach to identify performance gaps, gain actionable insights, and drive strategic decision-making to regain their competitive position and foster business growth.

## Tools Used 
- **Power Query** : For data cleaning and transformation
- **DAX (Data Analysis Expression)** : For creating Calculated Columns and Measures
- **Power BI** : For designing interactive dashboard and visualizations.

## Data Source 
The dataset comprises of following CSV files: 
- dim_date.csv: Contains information about dates and their corresponding day types (e.g., weekday, weekend).
 #### **Note**: In the hospitality industry, **Friday and Saturday** are considered **weekends**, while **Sunday to Thursday** are **weekdays**.
- dim_hotels.csv: Provides details about the properties, including their category and location (city).
- dim_rooms.csv: Includes information about room types and categories for each property.
- fact_aggregated_bookings.csv: Aggregated data detailing check-in dates, room categories, successful bookings, and property IDs.
- fact_bookings.csv: Comprehensive booking details, including booking platform, booking status, check-in and check-out dates, and revenue (realized and generated). 
- metrics_list.csv and Mock-Up Dashboard: Documents provided by stakeholders outlining required metrics and a reference dashboard design to guide the analysis.

## Key Metrics 
- **Revenue:** ₹1.69 billion  
- **RevPAR (Revenue Per Available Room):** ₹7,337  
- **ADR (Average Daily Rate):** ₹12,696  
- **Occupancy Percentage:** 57.8%  
- **Realisation Percentage:** 70.1%  
- **Cancellation Percentage:** 24.8%  
- **Total Bookings:** 133K  
- **Average Customer Rating:** 3.62/5
- **DSRN (Daily Sellable Room Nights):** 2,528

## Key Visuals 
### 1. **Executive Summary:**
- A high-level summary of the hotels KPI's(key performance indicators) for quick decision-making.
- Spot trends and identify focus areas without diving into granular details. 
- Enable leadership to align strategies with overall performance indicators.
- Empowers executives to monitor performance at a glance and make data-driven strategic decisions.

![Screenshot 2024-12-12 015928](https://github.com/user-attachments/assets/e1e8c367-e8f8-4838-9721-e767bc9a6f5d)

### 2. **Overall Performance:**
- Offers a revenue-centric analysis of hotel operations and performance.
- Highlights high-performing areas and revenue gaps to guide strategic improvements.
- Enables stakeholders to optimize pricing, marketing strategies, and operational decisions for maximum profitability.

![Screenshot 2024-12-12 020016](https://github.com/user-attachments/assets/44a41cde-38bc-4db8-a4b3-78f4888b710a)

### 3. **Bookings Insights:**
- Detailed analysis of booking patterns, platform contributions, and cancellations.
- Reduce revenue leakage, optimize platform performance, and understand guest preferences.
- Helps maximize bookings, prioritize resources, and improve guest experiences.

![Screenshot 2024-12-12 020046](https://github.com/user-attachments/assets/4951c705-6bd7-45a3-a617-8e15b0ba43ac)

## Dashboard 
### [Saffron Sky Suites Business Insights](https://app.powerbi.com/view?r=eyJrIjoiODJmNTUwNTItY2VmNy00MjE2LWEzMGEtZDQ1NzI1MDJhMWE4IiwidCI6Ijk0YjBjYWUyLTcyMzgtNDQ4OC05NTRmLWZjOTAyNWFmYzYxYSJ9) - Live Dashboard Link


## Insights 
- **Saffron Exotica** generated the highest revenue (₹316M), followed by **Saffron Palace** (₹300M).  
- **Saffron Seasons** is the lowest performing property, with the least revenue, lowest customer ratings, and a 44.6% occupancy rate 
- Elite rooms are the top revenue contributors, while Standard rooms underperforms.
- Luxury hotels drive 61.6 % of total revenue, while business hotels contribute for 38.4% .
- **Makeyourtrip** and **Others** platforms account for over 20K cancellations combined, the highest among booking channels.  
- Weekend occupancy outperforms weekdays, but weekdays contribute significantly to overall bookings requiring strategies targeting both time periods.

## Recommendations
- **Dynamic Pricing**: Adjust pricing based on seasonal trends, charging premium rates on weekends and offering discounts during low-demand periods.
- **Marketing Focus**: Target underperforming locations, platforms, and room types like Standard rooms to boost revenue.
- **Weekday Strategies**: Launch corporate discounts and loyalty programs to attract business travelers during weekdays.
- **Cancellation Policies**: Implement stricter policies for peak periods and offer incentives to reschedule rather than cancel.
- **Direct Bookings**: Provide exclusive discounts and better deals to increase direct bookings and enhance customer loyalty.

## Outcomes
- Proposed dynamic pricing strategies, leading to a potential 15% revenue increase.  
- Provided actionable insights into underperforming hotel locations, enabling better resource allocation and marketing.
- Enhanced decision-making through real-time dashboards and trend analysis of booking patterns.

## Skills Learned 
- Advanced data visualization and dashboard creation using Power BI.
- Data transformation with Power Query 
- Calculating key hospitality metrics like RevPAR and ADR using DAX.
- Deriving actionable business insights from data analysis.
- Data Modeling

## Conclusion 
This project demonstrates how data analysis and Power BI can identify revenue gaps, optimize pricing strategies, improve resource allocation, and enhance customer satisfaction. By analyzing key metrics and trends, the findings highlight growth opportunities and showcase my ability to leverage data visualization to deliver impactful, data-driven strategies for business success."















