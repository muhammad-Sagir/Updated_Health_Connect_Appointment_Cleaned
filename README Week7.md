# Week 7, HealthConnect Experience Lab

## Project Title
Improving Patient Appointment Attendance and Healthcare Support Using Data and AI

## My Track
Data Analytics

## Week 7 Focus
Week 7 moved the project into Testing, Refinement, and End-to-End Validation. Rather than repeating Week 6's analysis, I tested my dashboard's KPI calculations against the raw dataset, investigated a small inconsistency I found, and statistically validated whether my Week 6 compounding risk finding actually holds up rather than just looking convincing on a chart.

## Files in This Folder

| File | Description |
|---|---|
| `HealthConnect_Week7_Testing_Refinement_Report.docx` | Week 6 to 7 transition, testing readiness, KPI verification results, chart breakdown testing (including a boundary inconsistency found and resolved), statistical testing of the compounding risk finding, dashboard refinement notes, updated recommendations, HC-POD cross-track testing contribution, limitations, and Week 8 recommendations |
| `HealthConnect_Week7_Project_Summary.docx` | Concise summary covering what was tested, what was found, what changed, and the proposed focus before Week 8 |
| `HealthConnect_Appointment_Data_cleaned.csv` | Cleaned dataset carried forward from Week 5, used again this week for independent testing |
| `HealthConnect_Dashboard.pbix` | Power BI dashboard, unchanged in its calculations after testing confirmed they were accurate, documentation updated to match |

## What I Tested This Week

- Recalculated all six top-row KPI cards independently from the raw dataset. All six matched exactly
- Checked all four breakdown charts against the raw data. Three matched immediately
- Found a small inconsistency in the Distance Band chart (46.5% recalculated vs 46.4% on the dashboard), traced it to how patients at exactly 5.0km were grouped differently between my Week 5 documentation and the actual Power BI formula. Corrected the documentation to match the dashboard, which was accurate the whole time
- Ran chi-square tests on booking lead time and prior no-show history against the no-show outcome. Both came back statistically significant with p-values well under 0.001
- Rechecked the highest-risk segment (73.2% at 31+ day lead time, 1 or more prior no-shows, 15km or more away) directly against the raw data, it held

## Cross-Track Testing Contribution

The relevant track remains Data Science. No collaborator has been assigned to this project, so this is documented honestly rather than fabricated. I still produced genuine testing evidence, statistically validating the two features I recommended in Week 6, so the handoff document is stronger and ready whenever a collaborator becomes available.

## What Must Be Completed Before Week 8

Following up on the missing Data Science collaboration with the programme coordinators, and deciding how to finally address the waiting_time_minutes inconsistency flagged since Week 5.

## Programme
AnalystLab Africa, Data Analytics Internship Programme, Experience Lab
