# Week 8, HealthConnect Experience Lab, Final Integration & Presentation

## Project Title
Improving Patient Appointment Attendance and Healthcare Support Using Data and AI

## My Track
Data Analytics

## Week 8 Focus
Week 8 is the final stage of the HealthConnect Experience Lab. This week pulled together everything from Weeks 4 through 7 into one final, validated analytics package, and included recording an individual video presentation explaining my contribution to the overall project.

## Files in This Folder

| File | Description |
|---|---|
| `HealthConnect_Week8_Final_Analytics_Package.docx` | Final deliverable, executive summary, Week 7 to 8 transition, final integration readiness table, final KPIs, validated findings, dashboard, business insights, recommendations, analytical limitations, and HC-POD final integration documentation |
| `HealthConnect_Dashboard.pbix` | Final Power BI dashboard, all KPIs verified against the raw dataset during Week 7 testing |
| `HealthConnect_Appointment_Data_cleaned.csv` | Cleaned dataset used throughout the project, missing values in distance_to_clinic_km and waiting_time_minutes filled using the column median |
| Individual video presentation | 5 to 10 minute recorded presentation covering my track contribution, cross-track collaboration, testing journey, and the overall HealthConnect solution |

## Final Summary of My Contribution

Across this project I moved from an initial exploratory look at HealthConnect's appointment data to a fully validated, statistically tested set of findings. The two strongest, most reliable predictors of missed appointments turned out to be booking lead time and prior no-show history, and these two factors compound when combined. Patients booking more than a month ahead with a history of missed appointments reach a 73.2% no-show rate, compared to just 17.1% for the safest group. Both findings are backed by chi-square testing (p < 0.001), not just visual patterns.

## Cross-Track Integration

The relevant track throughout this project was Data Science, since my validated findings identify which variables are worth prioritising as prediction model features. No Data Science collaborator was ever assigned to this project across all eight weeks, so this has been documented honestly at every stage rather than fabricated. I still produced a complete, statistically validated findings handoff, ready for a collaborator to use whenever one becomes available.

## Key Limitations

Small gaps in distance_to_clinic_km and waiting_time_minutes were filled using median imputation. The waiting_time_minutes field also shows an unresolved inconsistency, values recorded even for appointments that were never attended. These findings show strong statistical association, not proof of direct cause, and the dataset itself is synthetic.

## Programme
AnalystLab Africa, Data Analytics Internship Programme, Experience Lab
