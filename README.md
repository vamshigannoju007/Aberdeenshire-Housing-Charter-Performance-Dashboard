# Aberdeenshire Housing Performance Benchmark Dashboard

## Project Overview

This project analyses Scottish Social Housing Charter performance data for Aberdeenshire Council and compares it against the Scottish average from 2019/20 to 2024/25.

The dashboard was built in Power BI to demonstrate how housing performance indicators can be transformed into clear, self-service reporting for service teams and decision-makers. The project focuses on tenant satisfaction, housing quality, repairs, arrears, rent collection, and re-let performance.

## Business Context

Aberdeenshire Council’s Housing Information Team supports housing services by extracting, analysing, and presenting data for internal teams, managers, external agencies, and public reporting.

This project reflects that type of work by using public Scottish Housing Charter data to identify service performance gaps, benchmark against national averages, and present key findings through interactive Power BI visuals.

## Dataset

**Source:** Scottish Housing Regulator  
**Dataset:** Scottish Social Housing Charter Data  
**Period Covered:** 2019/20 to 2024/25  
**Focus:** Aberdeenshire Council vs Scottish Average

The dataset was filtered to compare Aberdeenshire Council against the Scottish average across selected Charter performance indicators.

## KPIs Analysed

The dashboard focuses on 8 key performance indicators:

- Overall tenant satisfaction %
- Communication satisfaction %
- SHQS compliance %
- Emergency repair completion hours
- Non-emergency repair completion days
- Rent collected %
- Gross rent arrears %
- Average calendar days to re-let properties

## Tools Used

- Power BI
- Power Query
- DAX
- Excel

## Data Cleaning and Transformation

Power Query was used to prepare the dataset for analysis.

Key steps included:

- Imported the Scottish Housing Charter dataset into Power BI.
- Filtered the data to retain Aberdeenshire Council and Scottish Average records.
- Selected only relevant KPI columns for focused analysis.
- Renamed long indicator fields into clear business-friendly KPI names.
- Changed data types for percentage, numeric, and year fields.
- Removed unnecessary columns to simplify the model.
- Created a year sort column to display financial years in the correct order.
- Prepared the final table for dashboard visuals and DAX calculations.

## DAX Measures Created

DAX was used to calculate KPI values and benchmark differences.

Measures included:

- Overall Satisfaction %
- SHQS Compliance %
- Rent Collected %
- Gross Rent Arrears %
- Average Re-let Days
- Aberdeenshire KPI values
- Scottish Average KPI values
- Variance against Scottish Average

## Dashboard Pages

### Page 1: Performance Overview

This page provides a 2024/25 snapshot of Aberdeenshire Council’s housing performance.

It includes:

- KPI cards
- Trend charts from 2019/20 to 2024/25
- Comparison visuals against the Scottish average
- Year filter for interactive analysis

### Page 2: Benchmark Comparison

This page compares Aberdeenshire Council against the Scottish average across key housing indicators.

It includes:

- KPI comparison matrix
- Variance cards
- Satisfaction and compliance gaps
- Operational performance differences

## Key Insights

For 2024/25:

- Aberdeenshire’s overall satisfaction was 5.1 percentage points below the Scottish average.
- SHQS compliance was 4.6 percentage points below the Scottish average.
- Average re-let days were 6.4 days faster than the Scottish average.
- Rent collection was 0.5 percentage points higher than the Scottish average.
- Gross rent arrears were 2.0 percentage points lower than the Scottish average.

## Project Outcome

The dashboard shows how housing performance data can be turned into a clear benchmark report for decision-making.

It highlights areas where Aberdeenshire underperformed, such as tenant satisfaction and SHQS compliance, while also showing stronger operational performance in rent collection, arrears control, and re-let times.

## Skills Demonstrated

- Public-sector performance reporting
- Power BI dashboard development
- Power Query data cleaning
- DAX measure creation
- KPI benchmarking
- Variance analysis
- Housing performance data interpretation
- Self-service reporting design
