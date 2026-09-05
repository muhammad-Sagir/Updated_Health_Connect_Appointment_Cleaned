# Week 5, HealthConnect Experience Lab

## Project Title
Improving Patient Appointment Attendance and Healthcare Support Using Data and AI

## My Track
Data Analytics

## Week 5 Focus
Week 5 moved the project from planning into practical analysis. Building on the Week 4 foundation, I cleaned the dataset, ran exploratory analysis, calculated 5 KPIs, built a Power BI dashboard, and produced business insights and recommendations for HealthConnect.

## Files in This Folder

| File | Description |
|---|---|
| `HealthConnect_Week5_Analytics_Report.docx` | Data preparation summary, exploratory data analysis, KPI calculations, dashboard, key findings, business recommendations, limitations, and cross-track collaboration notes |
| `HealthConnect_Week5_Project_Summary.docx` | Concise summary of what I planned, what I completed, key outcomes, challenges, decisions, and my proposed focus for Week 6 |
| `HealthConnect_Week5_Business_Insights.pptx` | Slide deck presenting the 5 key business insights and recommendations |
| `HealthConnect_Appointment_Data_cleaned.csv` | Cleaned version of the appointment dataset, with missing values in distance_to_clinic_km and waiting_time_minutes filled using the column median. The original dataset was not modified |
| `HealthConnect_Dashboard.pbix` | Power BI dashboard file |

## Data Preparation Summary

- `distance_to_clinic_km`: 90 missing values (1.8%), filled with the median (8.7 km)
- `waiting_time_minutes`: 60 missing values (1.2%), filled with the median (24 minutes)
- No duplicates or inconsistent values found
- Cleaned file saved separately from the original

## Key Findings

1. Booking lead time is the strongest driver of no-shows. Patients booking 31 or more days ahead no-show at 60.5%, more than double same-week bookings
2. Prior no-show history strongly predicts future no-shows (55.4% vs 43.5%)
3. Distance to the clinic has a moderate effect (46.4% under 5km vs 54.1% at 15km or more)
4. Reminders help modestly, and SMS is the most effective channel
5. Demographic factors like gender show little to no effect on attendance

## Cross-Track Collaboration

Shared KPI findings and business insights with the Data Science track, particularly flagging booking lead time and prior no-show history as strong candidate features for their no-show prediction model.

## Proposed Focus for Week 6

Explore how these factors interact with each other, and continue supporting the Data Science track as their model development progresses.

## Programme
AnalystLab Africa, Data Analytics Internship Programme, Experience Lab
