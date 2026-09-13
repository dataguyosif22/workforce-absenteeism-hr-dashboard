# Methodology

## 1. Business question

Which roles, age groups, and business units carry the most absenteeism risk within Arima Pastry's workforce, and does that risk vary by gender?

## 2. Data source

Not independently verifiable. The dashboard is a view-only Power BI report referencing an Arima Pastry-branded HR dataset; the underlying dataset's real-world origin (actual company data vs. a public/case-study dataset) is not exposed through the public link and is not claimed here as a verified client engagement.

## 3. Data preparation

Not accessible from the public report.

## 4. Data modelling

Not accessible. The report appears to model employees with attributes for gender, age band, job role, and business unit (Stores/Head Office), joined to absence records with duration in days/hours, but the underlying table structure cannot be confirmed without the .pbix file.

## 5. KPI definitions

- **Total headcount**: count of distinct employees (8,336).
- **Gender split**: headcount grouped by gender, expressed as a percentage of total.
- **Age band distribution**: headcount grouped into age brackets (e.g. 40–49).
- **Business unit split**: headcount grouped by business unit (Stores, Head Office), expressed as a percentage.
- **Total absent days by role**: sum of absence days grouped by job role.
- **Employee count by absence-hour band**: count of employees grouped into absence-hour ranges (e.g. 0–39 hours).
- **Absence entries by gender within a day-band**: count of absence entries grouped by gender, filtered to a specific absence-day range (e.g. 80–119 days).

## 6. Analysis

Analysis segments the workforce by demographic and organizational attributes, then cross-references those segments against absence volume (days and hours) to identify where absenteeism is concentrated, both by role and by employee-level absence intensity.

## 7. Dashboard design

The published report presents summary KPI cards (headcount, gender split) alongside business unit, role, age, and absence-band breakdowns.

## 8. Validation

No independent validation was possible; figures in this repository are taken directly from the published dashboard as viewed.

## 9. Limitations

- Data provenance is not confirmed; treated as portfolio/practice data.
- The .pbix file and its DAX/Power Query logic are not available for review.
- No stated reporting period was identified in the material reviewed.
- Findings are based on a single review of the published report, not a refreshed or monitored data feed.
