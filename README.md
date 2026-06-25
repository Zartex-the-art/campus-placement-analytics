# Campus Placement Analytics Dashboard

Power BI dashboard to analyze campus placement performance, hiring trends, salary distribution, and placement drive outcomes.

## Files Included

* `Campus_Placement_Analytics.pbix`
* 4 Excel source files
* PDF report
* Dashboard screenshots

## Dataset

* **students_2026.xlsx** → Student details, CGPA, eligibility
* **offers.xlsx** → Offers, packages, roles
* **companies.xlsx** → Recruiter details
* **placement_drives.xlsx** → Drive performance

## Dashboard Pages

1. Executive Summary
2. Student Analytics
3. Company Analytics
4. Salary Analytics
5. Placement Drive Analytics

## KPIs

* Total Students
* Placed Students
* Placement Rate
* Total Offers
* Highest Package
* Average Package

## DAX Measures

```DAX
Placement Rate =
DIVIDE([Placed Students], [Total Students], 0) * 100

Highest Package =
MAX(Offers[Package])

Average Package =
AVERAGE(Offers[Package])
```

## Key Insights

* Higher CGPA improves placement chances
* Few companies contribute most offers
* Salary distribution is uneven
* Conversion drops in later drive stages

## Screenshots

Dashboard previews are available in the `/Images` folder.

## Note

Recruiters usually check **README, screenshots, and PDF first** before downloading the `.pbix` file.
