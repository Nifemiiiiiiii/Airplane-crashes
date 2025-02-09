# A Century of Airplane Crashes: Trends, Fatalities, and Key Aviation Safety Insights from 1908 to 2009

![image](https://github.com/user-attachments/assets/e074a8b4-41da-4de1-a56a-4ebdbdea0442)

## Project Overview

Airplane crashes are tragic events that have shaped aviation safety policies and technological advancements over the years. This project analyzes global airplane crashes and associated fatalities from 1908 - 2009. The goal is to identify trends in crash occurrences, understand factors contributing to aviation accidents, and highlight key safety improvements over time. Using data visualization techniques, we uncover insights into the deadliest periods in aviation history, airline accident patterns, and potential causes of crashes.

![Oluwanifesimi Adebayo Airplane Crashes and Fatalities analysis](https://github.com/user-attachments/assets/adf554d3-9063-4f2c-8458-f8bf1aaef21f)

## About the Dataset

* Time Span: 1908 – 2009:
* Date: Date of crash occurrence
* Location: Country and city of the accident
* Operator: Airline or organization operating the aircraft
* Aircraft Type: Model and manufacturer of the aircraft
* Aboard: Total people on board
* Fatalities: Total number of deaths
* Summary: Brief description of the crash


## Data Quality & Data Cleaning Preparation Assessments

1. Missing Values: Some entries in the dataset had missing operator names, aircraft models, or accident summaries. These were either filled using available sources or marked as "Unknown."
2. Duplicates: Duplicate records were identified and removed to avoid data redundancy.
3. Date Formatting: The date column was converted to a standard YYYY-MM-DD format for consistency.
4. Standardization of Operator Names: Airlines with different spellings were standardized.
5. Fatalities Calculation: Derived new metrics such as Total Fatalities by calculating ''' Total Fatalities = SUM('Airplane_Crashes_and_Fatalities'[Fatalities])'''

## Dashboard Overview
The interactive dashboard consists of multiple sections:
![image](https://github.com/user-attachments/assets/a02af228-48e3-4d82-80bd-f32cb6261a94)

* Crash Frequency Trends: Yearly and decade-wise trends in airplane crashes
* Geographical Heatmap: Crash occurrences by country and region
* Deadliest Crashes: Top 10 most fatal aviation accidents
* Operator Analysis: Airlines with the most crashes
* Aircraft Models: Most commonly involved aircraft in accidents
* Survivability Rate: Trends in fatalities versus total passengers

## Analysis and Visualizations

1. Yearly Trends in Airplane Crashes

Graph Type: Line Chart
![image](https://github.com/user-attachments/assets/ef782eba-61b9-4f72-8e3c-79b29ff4e614)

The Peak crash periods observed during 1972 showing a declining trend post-2000 due to enhanced safety measures

2. Crashes by Country
Graph Type: Choropleth Map (Geographical Heatmap)
![image](https://github.com/user-attachments/assets/f8ed4009-7ff9-48c9-8ce6-72e0c0c259d3)

Countries with the highest crash incidents: [Top 5 countries]
Higher frequency observed in regions with older aviation infrastructure
4. Fatality Rates Over Time
Graph Type: Bar Chart
Key Metrics:
Highest fatality rates seen in [specific years]
Increase in survivability after [specific technological advancements]
5. Airlines with Most Crashes
Graph Type: Bar Chart
Key Metrics:
Airlines with the most historical crashes: [Top 5 airlines]
Decline in accidents for major airlines post-2000 due to stricter regulations
6. Most Affected Aircraft Models
Graph Type: Pie Chart
Key Metrics:
Most frequently involved aircraft models: [Top 3 aircraft models]
Higher crash rates observed for older aircraft designs
7. Survivability Rate Trends
Graph Type: Area Chart
Key Metrics:
Increase in survivability post-1990 due to better safety gear and improved evacuation procedures
Major accidents where passengers survived partially or fully
Insights and Recommendations
Key Insights:
Significant Reduction in Crashes after the 2000s due to stricter regulations and improved aircraft technology.
Geographical Distribution indicates higher crash occurrences in [specific regions] due to older aviation infrastructure.
Fatality Rates Have Decreased as modern aircraft are built with better safety mechanisms.
Most Dangerous Decade: [Identify the worst decade] for aviation accidents.
Most Affected Airlines & Aircraft Models highlight older planes and specific airlines with historical accident records.
Impact of Weather & Human Error: Many crashes were attributed to pilot error and poor weather conditions, reinforcing the need for better pilot training and real-time weather tracking.
Recommendations:
📌 Stronger Safety Protocols in High-Risk Regions with frequent accidents.
📌 Mandatory Retirement of Older Aircraft Models based on crash data.
📌 Increased Focus on Pilot Training Programs to minimize human error.
📌 Expansion of Real-Time Weather Monitoring to reduce weather-related crashes.
📌 Implementation of Advanced AI-based Aircraft Diagnostics to predict mechanical failures before takeoff.
📌 Encouraging More Black Box Analysis to learn from past incidents.

Conclusions (6 Key Takeaways)
1️⃣ The number of crashes has significantly decreased post-2000 due to technological advancements and improved safety measures.
2️⃣ Fatality rates are highest in older aircraft models, highlighting the need for better retirement policies.
3️⃣ Certain regions experience more crashes, suggesting a need for enhanced air traffic control and safety regulations in those areas.
4️⃣ Major airlines with past crash records have improved their safety procedures, showing how regulation enforcement has worked.
5️⃣ Human error remains a leading cause of accidents, reinforcing the need for better pilot training and AI assistance in aviation.
6️⃣ Continuous improvements in aircraft design, technology, and safety protocols will further reduce the risk of future airplane crashes.


