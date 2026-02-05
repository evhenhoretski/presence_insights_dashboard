# Presence Insights Dashboard (Power BI)

This Power BI dashboard analyzes employee attendance and presence patterns, including on-site work, work-from-home, and different leave types.  
The report provides a clear overview for basic workforce monitoring and trend analysis.

---

## Dashboard Overview

The dashboard highlights:

- **Presence %** – on-site attendance
- **WFH %** – work-from-home rate
- **SL %** – sick leave rate

KPIs are shown at the top, with trend analysis and breakdowns by employee and day of week.

---

## Key Insights Covered

- Presence, WFH, and SL trends over time
- Weekly attendance patterns
- Comparison by employee
- Distribution by day of week

---

## Interactivity

Interactive filters include:

- Date (month / period)
- Employee
- Day of week

All visuals update dynamically based on selections.

---

## Attendance Key

| Code | Meaning |
|-----|--------|
| P | Present |
| PL | Paid Leave |
| SL | Sick Leave |
| HPL | Half Day Paid Leave |
| HSL | Half Day Sick Leave |
| WFH | Work From Home |
| HWFH | Half Work From Home |
| FFL | Floating Festival Leave |
| HFFL | Half Day Floating Festival Leave |
| BL | Birthday Leave |
| LWP | Leave Without Pay |
| HLWP | Half Day Leave Without Pay |
| BRL | Bereavement Leave |
| HBRL | Half Day Bereavement Leave |
| WO | Weekly Off |
| HO | Holiday Off |
| ML | Menstrual Leave |
| HML | Half Day Menstrual Leave |

---

## Data Model

- **Fact table**: daily attendance records  
- **Dimensions**: employee, date  

Star schema is used to support filtering and time-based analysis.

---

## Calculations

All metrics are implemented as **DAX measures**, including Presence %, WFH %, and SL %.

---

## Dashboard Preview

![Presence Insights Dashboard](/screenshot.png)

---

## Tools Used

- Power BI Desktop
- DAX
- Power Query
