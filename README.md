# Power-BI
POWER BI REPORT: PATIENT WAIT LIST ANALYSIS
Requirement Gathering:
- Identify Stakeholders
- Understand Business Objectives
- High Level Data Study
- Define Scope
Overall Objectives:
• Project Goals:
1- Track current status of patient waiting list.
2- Analyse historical monthly trend of waiting list in Inpatient &
Outpatient categories.
3- Detailed specialty level & age profile analysis.
• Data Scope:
2018 – 2021
• Metrics Required:
1- Average & Median Waiting List
2- Current Total Wait List
• Views Required:
1- Summary Page.
2- Detailed page for Granular Analysis.
INTRODUCTION:
This document provides a detailed explanation of the data visualization components in the Power BI report for Patient Wait List Analysis. The report aims to offer insights into patient
wait times across different specialties, case types, and age profiles to optimize resource allocation and improve patient care.
DASHBOARD OVERVIEW: The dashboard comprises various visualizations tailored to analyze patient wait list data effectively:
Page 1: Summary
LATEST MONTH WAIT LIST AND PY LATEST MONTH WAIT LIST:
These cards display the number of patients on the wait list for the latest month and the
corresponding month of the previous year, respectively.
AVG/MED WAIT LIST BY CASE TYPE:
A pie chart illustrating the distribution of average or median wait list numbers across
different case types (Day Case, Inpatient, Outpatient).
AVG/MED WAIT LIST BY TIME BANDS AND AGE PROFILE:
A stacked column chart presenting the average or median wait list numbers categorized by
time bands and age profiles.
SLICERS:
• Archive Date Slider: Allows users to filter data based on the archive date using a
slider.
• Calculation Method Slicer: Enables users to switch between displaying average and
median wait list numbers.
• Specialty Name Slicer: Facilitates filtering of data by specialty name.
• Case Type Slicer: Allows users to filter data by case type (Day Case, Inpatient,
Outpatient).
TOP 5 SPECIALTIES BY AVG/MED WAIT LIST:
A multi-row card showcasing the top 5 specialties with the highest average or median wait
list numbers.
WAIT LIST TRENDS OVER TIME:
Two line charts displaying the trend of total wait list numbers over time, segmented by case
type (Day Case, Inpatient, Outpatient).
KEY MEASURES:
AVERAGE WAIT LIST: Calculates the average wait list across all patient data.
MEDIAN WAIT LIST: Determines the median wait list across all patient data.
DYNAMIC TITLE: Switches between displaying "Key Indicators - Patient Wait List (Average)"
or "Key Indicators - Patient Wait List (Median)" based on user selection.
AVG/MED WAIT LIST: Displays either the average or median wait list based on user
selection.
LATEST MONTH WAIT LIST: Computes the total number of patients on the wait list for the
latest month.
PY LATEST MONTH WAIT LIST: Calculates the total number of patients on the wait list for the
corresponding month of the previous year.

Page 2: Detailed View
Matrix (Table):
Rows: Archive_Date, Specialty_Name, Age_Profile, Time_Bands
Columns: Case_Type
Values: Sum of Total
Slicers: Archive_Date, Case_Type, Specialty_Name, Age_Profile, Time_Bands
This detailed view provides a comprehensive breakdown of patient wait list data across
various dimensions, including archive date, specialty name, age profile, time bands, and case
type. The matrix allows users to analyze wait list numbers dynamically based on their
specific filtering criteria.
Page 3: DrillDown (Hidden Tooltip Page)
Tooltip:
Total Wait List: Sum of Total (Displayed as title)
Stacked Bar Chart: Specialty Group by Sum of Total
Specialty Group: Categorized groups of specialties derived from the Mapping_Specialty
table.
Sum of Total: Represents the total number of patients on the wait list for each specialty
group.
This hidden tooltip page serves as an interactive feature that appears when hovering over
the line chart on the first page. It provides additional insights into the total wait list numbers
and allows users to compare wait list numbers across different specialty groups.
Conclusion:
The Power BI report for Patient Wait List Analysis provides healthcare administrators and
professionals with a powerful tool to gain insights into patient wait times and optimize
resource allocation effectively. Through a series of carefully crafted visualizations and
interactive features, the report enables users to:
Monitor Key Metrics: The dashboard presents essential metrics such as total patients on the
wait list, average and median wait times, and trends over time. This allows stakeholders to
track performance against targets and identify areas for improvement.
Segmented Analysis: Users can drill down into the data by specialty, case type, age profile,
and time bands using slicers and matrix tables. This segmented view offers a granular
understanding of wait list dynamics across different dimensions, facilitating targeted
interventions and resource allocation.
Comparative Analysis: The report allows for easy comparison between different time
periods, specialties, and patient demographics. This comparative analysis helps identify
trends, disparities, and opportunities for process optimization.
Top Specialty Insights: The multi-row card highlighting the top 5 specialties by average or
median wait list numbers provides actionable insights for priority setting and resource
allocation.
Interactive Tooltip: The hidden tooltip page offers an interactive feature that appears when
hovering over the line chart, providing additional insights into total wait list numbers across
specialty groups.
Overall, the Power BI report empowers healthcare organizations to make data-driven
decisions, optimize patient flow, improve resource utilization, and ultimately enhance the
quality of care provided to patients. By leveraging the insights gained from this report,
stakeholders can drive continuous improvement in patient wait times and overall healthcare
delivery.
The background image is designed with Adobe XD.
