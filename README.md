# HR Employee Presence Report

## Overview

This project analyzes employee attendance, work from home (WFH), half WFH, sick leave (SL), and holidays data over a period of three years to provide insights into employee presence trends. The dashboard helps in identifying the best employees, understanding WFH preferences, sick leave trends, and overall attendance percentages.

![HR Employee Presence Report](./PowerBI_Dashboard.png)

## Dataset

The dataset used in this project includes the following columns:
- **Date**: The date of the attendance record.
- **Day of the week**: The day corresponding to the date.
- **Employee ID**: Unique identifier for each employee.
- **Month**: Month of the attendance record.
- **Name**: Employee's name.
- **Sheet Name**: Name of the data sheet.
- **SL Count**: Sick leave count.
- **Value**: Presence status (e.g., P for Present, WFH for Work From Home, SL for Sick Leave).
- **WFH Count**: Work from home count.
- **Percentage %**: Percentage of presence status.
- **Present Days**: Count of present days.
- **SL %**: Percentage of sick leave.
- **Total Working Days**: Total count of working days.

## Analysis

The following analyses were performed using the dataset:
1. **Overall Attendance Analysis**:
   - **WFH %**: Percentage of days employees worked from home.
   - **Percentage %**: Overall attendance percentage.
   - **SL %**: Percentage of sick leaves taken.

2. **Employee-wise Analysis**:
   - Identifying the best employees based on attendance percentage.
   - Analyzing individual WFH preferences and sick leave trends.

3. **Date-wise Analysis**:
   - Percentage of attendance by date.
   - WFH percentage by date.
   - Sick leave percentage by date.

4. **Day of the Week Analysis**:
   - Attendance trends based on the day of the week.
   - WFH trends based on the day of the week.
   - Sick leave trends based on the day of the week.

## Key Insights

- **Best Employees**: Employees with the highest attendance percentages and lowest sick leave counts.
- **WFH Preferences**: Analysis of how often employees prefer to work from home.
- **Sick Leave Trends**: Understanding the frequency and patterns of sick leaves.
- **Date Trends**: Trends in attendance, WFH, and sick leave over specific dates.
- **Weekly Trends**: Insights into how attendance, WFH, and sick leave vary by day of the week.

## Steps to Reproduce

1. **Load Data**: Import the dataset into Power BI.
2. **Transform Data**: Clean and transform the data using Power Query. Unpivot date columns to create a single 'Date' column if necessary.
3. **Create Visualizations**: Build the visualizations as shown in the dashboard:
   - Overall attendance metrics.
   - Line charts for attendance, WFH, and sick leave trends by date.
   - Bar charts for weekly attendance, WFH, and sick leave trends.
4. **Generate Insights**: Analyze the visualizations to generate key insights.

## Conclusion

The HR Employee Presence Report provides valuable insights into employee attendance patterns, WFH preferences, and sick leave trends. This analysis can help HR departments to understand employee behavior better and make informed decisions.

## Further Steps

- Record the process: Document the data loading, transformation, and visualization creation process for reproducibility.
- Explore additional analyses: Further analyze holiday impacts, festival attendance, and compare different time periods.

## Contact

For any questions or further information, please contact [Your Name] at [Your Email].

---

*This project was developed using Power BI Desktop.*
