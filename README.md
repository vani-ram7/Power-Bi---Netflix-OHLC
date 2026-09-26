Netflix Stock Market Data Visualization Dashboard

📊 Project Overview

This project is an interactive Netflix (NFLX) Stock Market Data
Visualization Dashboard developed using Microsoft Power BI.

The dashboard transforms stock-market data into an interactive
analytical experience, allowing users to explore price trends, moving
averages, trading-volume activity, and time-based patterns.

The project focuses on presenting financial data in a clear and
user-friendly way using Power BI visualizations, calculated measures,
slicers, and time hierarchies.

🎯 Objectives

Analyze Netflix (NFLX) stock-market data over time.

Visualize stock-price trends using interactive line charts.

Compare short-term and medium-term moving averages.

Analyze trading-volume activity.

Enable date-based filtering and drill-down.

Provide an interactive dashboard for financial-data exploration.

Demonstrate practical Power BI data-analytics and visualization
skills.

🛠️ Tools & Technologies

Microsoft Power BI

Power BI Desktop

DAX / Power BI Measures

Data Modeling

Time Intelligence

Interactive Data Visualization

📁 Project Structure

Netflix-Stock-Market-Visualization/
│
├── skill_DV.pbix
├── README.md
├── Netflix_Stock_Data_Visualization_Project_Report.pdf
└── screenshots/
    └── dashboard-preview.png

File names may vary depending on how the project is organized in the
repository.

📈 Dashboard Features

1. Stock Price Trend

A line chart is used to visualize the NFLX Close value over time.

It helps users examine:

Overall price movement

Period-to-period changes

Long-term and short-term trends

Changes across different time periods

2. Moving Average Analysis

The dashboard includes:

20-day moving average

50-day moving average

Moving averages smooth daily fluctuations and make broader trends easier
to identify.

Conceptually:

Moving Average = Average of values within a rolling time window

The 20-day measure provides a shorter-term view, while the 50-day
measure represents a longer smoothing period.

3. Volume Analysis

A column chart is used to visualize the NFLX Volume field across the
selected time hierarchy.

This allows users to explore changes in trading activity across
different periods.

4. Date Filtering

The dashboard includes a date slicer that allows users to select a
specific time range.

This makes it possible to focus the analysis on:

A particular year

A quarter

A month

A smaller custom date range

5. Interactive Metric Selection

The project includes an AVG_METRIC field parameter that supports
interactive selection of analytical measures used in the dashboard.

🗂️ Data Model

The report contains the following major components:

Component        Purpose

NFLX         Primary stock-market data
DateTable    Time-based analysis and filtering
Measuress    Calculated analytical measures
AVG_METRIC   Interactive metric/field parameter

Important Fields

The project definition references:

Close

Volume

Date

Year

Quarter

Month

Day

20_day_moving

50_day_moving

🕒 Time Intelligence

The dashboard uses a dedicated date hierarchy:

Year
  ↓
Quarter
  ↓
Month
  ↓
Day

This allows users to drill from high-level yearly trends into more
detailed time periods.

📊 Dashboard Visuals

The supplied Power BI report contains:

2 Line Charts

1 Column Chart

1 Metric Slicer

1 Date Slicer

The report is also configured with a Year-based drillthrough
workflow.

🔍 Key Analytical Questions

The dashboard can be used to investigate questions such as:

How does Netflix stock activity change over time?

How does the 20-day moving average compare with the 50-day moving
average?

When does trading activity increase or decrease?

How do trends change between years, quarters, and months?

How does changing the selected date range affect the observed trend?

🚀 How to Use the Project

Step 1 --- Install Power BI Desktop

Install Microsoft Power BI Desktop on your Windows computer.

Step 2 --- Open the PBIX File

Open:

skill_DV.pbix

in Power BI Desktop.

Step 3 --- Explore the Dashboard

Use the:

Date slicer

Metric selector

Chart interactions

Date hierarchy drill-down

Year-based drillthrough

to explore the dashboard.

Step 4 --- Refresh Data

If the underlying dataset is connected to a refreshable source, use
Power BI's Refresh option to update the report.

💡 Future Enhancements

The dashboard can be extended with:

KPI cards for current/latest price

Percentage change indicators

Daily/weekly/monthly returns

Volatility analysis

Additional technical indicators

High/Low price analysis

Trading-volume summaries

More advanced drillthrough pages

Automated data refresh

Data-quality validation

Additional financial visualizations

📌 Project Outcome

This project demonstrates practical skills in:

Data visualization

Power BI dashboard development

Data modeling

Time-series analysis

DAX measures

Interactive reporting

Financial-data visualization

Dashboard design

It provides a foundation that can be further developed into a more
comprehensive financial analytics solution.

👩‍💻 Author

Vani

Data Science & Analytics Enthusiast

GitHub: https://github.com/vani-ram7

📄 Project Report

A detailed project report is included with this project:

Netflix Stock Data Visualization Project Report

The report covers the project architecture, data model, dashboard
visuals, analytical methodology, technical implementation, and future
enhancements.

⚠️ Disclaimer

This project is created for educational and data-visualization
purposes.

The dashboard should not be considered financial advice or a
recommendation to buy or sell any security.
