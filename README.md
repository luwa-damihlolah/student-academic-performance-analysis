# Student Academic Performance Analysis

**Tools:** Microsoft Excel | Power BI  
**Project area:** Education Analytics

## Project overview
This project explores a dataset of 100 student records to summarize academic outcomes and examine patterns across departments, subjects, attendance, study hours and gender. The Power BI dashboard presents key indicators and visual comparisons to support academic monitoring.

## Business problem
Educational institutions need practical ways to interpret student records, identify performance gaps and monitor indicators associated with academic outcomes. This analysis organizes student data into measurable indicators and dashboard visuals.

## Objectives
- Compare average academic scores across departments.
- Review performance across Mathematics, English, Physics and Chemistry.
- Examine attendance and study-hours relationships with average scores.
- Compare average scores by gender.
- Summarize grade distribution and pass rate.
- Communicate findings through a Power BI dashboard.

## Dataset
The supplied Excel workbook contains **100 student records** and **13 fields**: Student ID, Department, Gender, Attendance (%), Study Hours, four subject scores, Total Score, Average Score, Grade and Pass Indicator.

## Key findings
| Metric | Result |
|---|---:|
| Total students | 100 |
| Average attendance | 77.53% |
| Overall average score | 54.36 |
| Pass rate | 57% |
| Highest department average | Arts — 56.94 |
| Lowest department average | Business — 49.76 |
| Highest subject average | Math — 54.93 |
| Students with Grade F | 43 |

Female students averaged 54.41; male students averaged 54.31. The correlation between study hours and average score is 0.87; for attendance and average score it is 0.32. These are associations, not evidence of causation.

## Tools and workflow
- **Microsoft Excel:** spreadsheet-based data review and preparation, as described in the supplied project notes.
- **Power BI:** KPI cards, comparisons and dashboard visualization.

The separate Excel analysis workbook was not included in the supplied project files. Therefore, individual Excel formulas, PivotTables and cleaning steps cannot be independently verified from this repository.

## Recommendations
1. Review support needs in departments with lower average scores.
2. Investigate the reasons for the number of F grades and identify students who may benefit from additional support.
3. Monitor attendance and study habits alongside academic results.
4. Review subject-level patterns to identify opportunities for additional learning support.
5. Use the dashboard to track indicators over time and evaluate interventions.

## Limitations
The analysis covers 100 records from the supplied dataset. It is descriptive and does not establish causal relationships. Results should be interpreted within the scope of this dataset.

## Repository structure
```text
01_Dataset/                  Raw student dataset
02_PowerBI/                  Power BI report (.pbix)
03_Dashboard_Screenshots/    Dashboard image
04_Documentation/            Project report and original notes
```

## Files
- `01_Dataset/Student_Academic_Performance_Raw_Dataset.xlsx`
- `02_PowerBI/Student_Performance_Analysis.pbix`
- `03_Dashboard_Screenshots/Student_Performance_Dashboard.png`
- `04_Documentation/Student_Academic_Performance_Project_Report.docx`

