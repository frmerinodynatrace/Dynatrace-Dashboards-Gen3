# Performance Conversion Analysis Dashboard
This dashboard provides a performance conversion analysis for your applications and tells you if the performance for a certain User Action impacts your conversion rate.

![Performance Conversion Analysis Dashboard](PerformanceConversionAnalysis.png)

# Prerequisites

Required: [Create a session property](https://www.dynatrace.com/support/help/platform-modules/digital-experience/web-applications/additional-configuration/define-user-action-and-session-properties) for a user action that indicates a completed business transaction (i.e. Order Confirmation Page).

Required: [Configure Key User Action](https://www.dynatrace.com/support/help/platform-modules/digital-experience/web-applications/additional-configuration/configure-key-user-actions-web) for the User Action that is to be analyzed.

# Target Audience

- Application Owner
- Line of Business
- Executive
- Web Developer

# Use Cases

- What is the APDEX for my Key User Action?
- Is my user traffic increasing?
- Does the performance of my Key User Action impacting my Conversion Rate?
- Are users that interract with my Key User Action converting efficiently?
- What is the optimal performance for my Key User Action with respect to conversions?

# Install Instructions

- Download https://github.com/TechShady/Dynatrace-Dashboards-Gen3/blob/main/Performance%20Conversion%20Analysis.json
- Launch the new Gen3 UI
- Select the Dashboard app
- In the upper righthand corner, select Upload and select your json file
- Refresh your dashboard list and launch your Dashboard
- Modify the ConversionGoal variable filter and replace with your conversion session property

# User Guide

The Performance Conversion Analysis Dashboard is broken down into four sections.

![Performance Conversion Analysis Dashboard](PerformanceConversionAnalysis-0.png)

The dashboard header section has five filters that you can apply to your Performance Conversion Analysis Dashboard:
- AppName - List of applications currently monitored by Dynatrace. Select the application to filter the dashboard for any application.
- ConversionGoal - The session property for you application that indicates a converted session.
- KPI - List of KPIs used in analysis (i.e. Duration, Visually Complete Time).
- Aggregate - List of aggregations used in analysis (i.e. Avg, Median).
- KeyUserAction - A list of key user actions that you can analyze.

![Performance Conversion Analysis Dashboard](PerformanceConversionAnalysis-1.png)

The top section is called the KPI banner. This section has the following KPIs:
- Performance Metric: Configured based on the KPI and Aggregate selected (i.e. Avg Duration).
- Sessions: Total number of user sessions that executed the Key User Action.
- Efficiency Rate: Rate of sessions that converted with good user experience. A perfect efficiency rate is 100.
- Deficiency Rate: Rate of sessions that abandoned with poor user experience. A perfect deficiency rate is 0.
- Conversion Rate: Rate of sessions that converted.
- Apdex: Application Performance Index is a standard developed by an alliance of companies for measuring the performance of applications. A perfect Apdex score is 1.

Each KPI cell displays the current value for the last 24 hours. Each KPI is compared to a seven-day time shift over the past 24 hours and will display, in parentheses, the KPI difference and trend direction.

![Performance Conversion Analysis Dashboard](PerformanceConversionAnalysis-2.png)

The middle section displays the conversion analysis for your Key User Action. Each column filters the data based on the performance range of the Key User Action (i.e. <2s, 2s - 3s). The rows show the conversion count, abandon count and the conversion rate for your Key User Action. 

![Performance Conversion Analysis Dashboard](PerformanceConversionAnalysis-3.png)

The bottom section charts the conversion rate over the performance ranges.
