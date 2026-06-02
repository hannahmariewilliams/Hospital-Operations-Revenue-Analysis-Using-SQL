# Healthcare Data Analysis Project

## Executive Summary:
Using SQL, I pulled patients, doctors, and financial data from the hospital database and explored the data. Data was then transformed into an interactive Power Bi dashboard to visualize key metrics. As a result, I identifyied that the hospital has a high no show rate, that most scheduled appointments are check-ups and the highest grossing treatment type is X-Ray. I recommend that the hospital improves on the following:

1. Automated reminders and/or flexible re-scheduling
2. Dedicated time blocks for scheduling check-ups
3. Ensure staff, equipment, and scheduling are adequately supported for X-Ray services

### Business Problem:
The hospital is experiencing operational inefficiencies that impact both revenue and patient care quality. A high patient no-show rate leads to underutilized appointment slots. Additionally, the high volume of routine check-ups and the significant revenue contribution from X-ray services highlight a misalignment between scheduling practices and demand patterns. Without more strategic scheduling and resource allocation, the hospital risks continued revenue loss, and reduced patient access to timely care.

### Methodology:
1. SQL query to perform exploratory data analysis
   
2. Dashboard in Power BI that visualizes key metrics.

### Skills:
SQL: Joins, aggregate functions, CTEs

Power BI: calculated columns, ETL, data visualization, writing functions, Dax, data modeling

### Results & Business Recommendation:
The hospital is experiencing operational inefficiencies that negatively impact revenue and patient access to care. A high patient no-show rate of 26% results in underutilized appointment capacity and lost revenue opportunities. Additionally, a large share of appointments consists of routine check-ups, while X-ray services account for 28% of total revenue, indicating a misalignment between scheduling practices and revenue-driving services. Without more strategic scheduling and resource allocation, the hospital risks continued inefficiencies, reduced capacity utilization, and missed opportunities to optimize high-value services.
<p></p>
<p></p>
<img width="3236" height="1742" alt="Screenshot 2026-06-01 201945" src="https://github.com/user-attachments/assets/99eee1da-03a9-4d1b-bfa8-51e7c6a21b39" /> 
<p></p>
<p></p>
Because the hospital is experiencing a 26% patient no-show rate and a significant portion of revenue is concentrated in high-demand services like X-ray (28% of total revenue), I recommend several targeted operational adjustments:

1. Implement automated appointment reminders and confirmation workflows via text and email to reduce missed appointments and improve patient attendance consistency.
2. Introduce flexible self-scheduling and rescheduling options to reduce friction for patients and allow more efficient filling of canceled or unused time slots.
3. Allocate dedicated scheduling blocks for high-frequency visit types such as routine check-ups to improve patient flow and reduce scheduling congestion.
4. Ensure sufficient staffing, equipment availability, and optimized scheduling capacity for X-ray services to support consistent demand and protect high-revenue operations.

These adjustments directly target the highest-impact inefficiencies in the scheduling system, improving appointment utilization, strengthening revenue capture, and increasing overall operational efficiency.

### Next Steps
1. A/B test different patient reminder strategies (timing, frequency, and messaging tone) to determine which most effectively reduces appointment no-show rates.
2. Pilot automated confirmation and self-scheduling features to evaluate impact on appointment utilization and cancellation recovery.
3. Collaborate with operational staff to refine scheduling rules and validate feasibility of dedicated check-up time blocks.
4. Track changes in no-show rate and X-ray utilization over time to assess whether scheduling and engagement improvements translate into operational and revenue gains.

### Project Structure:
This project is organized into sections:

Chapter 1: Core KPIs
Chapter 2: Doctors Analysis
Chapter 3: Patient Analysis
Chapter 4: Financial Analysis
Chapter 5: Final Insights & Recommendations
Hospital Dashboard - Power BI

Each chapter includes SQL queries and explanations, followed by insights derived from the analysis. The dashboard is also included.

Data source: [Hospital Management Dataset](https://www.kaggle.com/datasets/kanakbaghel/hospital-management-dataset)
