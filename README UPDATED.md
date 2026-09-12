# Week 6, HealthConnect Experience Lab

## Project Title
Improving Patient Appointment Attendance and Healthcare Support Using Data and AI

## My Track
Data Analytics

## Week 6 Focus
Week 6 moved the project into Integration, Advanced Development, and Validation. Rather than repeating the Week 5 exploratory analysis, I validated whether the strongest Week 5 findings, booking lead time and prior no-show history, held up under deeper segment analysis, and prepared the findings for handoff to the Data Science track.

## Files in This Folder

| File | Description |
|---|---|
| `HealthConnect_Week6_Advanced_Analytics_Report.docx` | Week 5 to 6 transition, integration readiness, advanced segment analysis, validated findings, refined KPIs, evidence-based recommendations, data limitations, Data Science findings handoff, Week 7 testing requirements, mandatory cross-track integration documentation, and updated assumptions/limitations/risks |
| `HealthConnect_Week6_Project_Summary.docx` | Concise summary covering what was planned, completed, improved, and integrated this week, plus challenges, decisions, and the proposed focus for Week 7 |
| `HealthConnect_Appointment_Data_cleaned.csv` | Cleaned dataset carried forward from Week 5 (missing values in distance_to_clinic_km and waiting_time_minutes filled using the column median) |
| `HealthConnect_Dashboard.pbix` | Updated Power BI dashboard, including a new matrix visual showing the compounding no-show risk between booking lead time and prior no-show history |

## What Changed From Week 5

Week 5 looked at booking lead time and prior no-show history as separate, single-variable KPIs. Week 6 combined them and found the effect compounds. A patient with both risk factors (31+ day lead time and a prior no-show) reaches a 73.2% no-show rate, compared to 17.1% for the safest segment (0 to 3 day lead time, no prior no-shows). This pattern was also validated as stable across every appointment type in the dataset.

## Cross-Track Integration

The relevant track for this integration is Data Science, since their no-show prediction model depends on knowing which variables are worth prioritising as features. No Data Science collaborator was assigned to this project, so rather than fabricate an exchange, this is documented honestly in the report. A dedicated findings handoff section was still produced, identifying booking_lead_days and previous_no_shows as the strongest candidate features, and recommending an engineered interaction feature between the two, ready for a collaborator to use whenever one becomes available.

## Proposed Focus for Week 7

Statistically test the significance of the validated findings, re-examine the waiting_time_minutes data inconsistency, and remain ready to connect with a Data Science collaborator if one is assigned.

## Programme
AnalystLab Africa, Data Analytics Internship Programme, Experience Lab
