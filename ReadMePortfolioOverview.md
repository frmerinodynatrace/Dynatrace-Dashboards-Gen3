# Portfolio Overview Dashboard
This dashboard provides an executive level for all your Applications.

![Portfolio Overview Dashboard](PortfolioOverview.png)

# Prerequisites

None.

# Target Audience

- Application Owner
- Line of Business
- Executive

# Use Cases

- What is my overall APDEX score?
- Is my user traffic increasing?
- Do I have application efficiency issues?
- Do I have any poor performance trend issues?
- Do I have any error trend issues?
- Is any application experiencing high error rates?
- Is any application suffering from poor performance?
- What days/times do I have good user experiences?

# Install Instructions

- Download https://github.com/TechShady/Dynatrace-Dashboards-Gen3/blob/main/Portfolio%20Overview.json
- Launch the new Gen3 UI
- Select the Dashboard app
- In the upper righthand corner, select Upload and select your json file
- Refresh your dashboard list and launch your Dashboard

# User Guide

The Portfolio Overview Dashboard is broken down into three sections.

![Portfolio Overview Dashboard](PortfolioOverview-1.png)

The top section is called the KPI banner. This section has the following KPIs:
- Avg Duration: Time between the initial user input and complete page load.
- Avg Errors: Average number of Request and JavaScript Errors.
- Efficiency Rate: Rate of sessions with good user experience. A perfect efficiency rate is 100.
- Deficiency Rate: Rate of sessions with poor user experience. A perfect deficiency rate is 0.
- Sessions: The total number of user sessions for all applications.
- Apdex: Application Performance Index is a standard developed by an alliance of companies for measuring the performance of applications. A perfect Apdex score is 1.

Each KPI cell displays the current value for the last 24 hours. Each KPI is compared to a seven-day time shift over the past 24 hours and will display, in parentheses, the KPI difference and trend direction.

![Portfolio Overview Dashboard](PortfolioOverview-2.png)

The middle section displays the following tables: 
- Sessions - The number of User Sessions for each application.
- Duration - The average user action Duration for each application.
- JavaScript Errors - The number of JavaScript Errors for each application.
- Request Errors - The number of Request Errors for each application.

 Each table displays the metric for the last 24 hours, 7 day timeshift, 14 day timeshift and 21 day timeshift. This enables trend analysis for each metric.
  
![Portfolio Overview Dashboard](PortfolioOverview-3.png)

The bottom section charts customer satisfaction (Satisfied, Tolerated, Frustrated) over the last seven days.
