# Conversion Overview Dashboard
This dashboard provides an executive level overview and risk assessment on application conversions.

![Conversion Overview Dashboard](ConversionOverview.png)

# Prerequisites

1. Required: [Create a conversion goal](https://www.dynatrace.com/support/help/platform-modules/digital-experience/web-applications/analyze-and-use/define-conversion-goals) for a user action that indicates a converted user session (i.e. Order Confirmation Page).
2. Optional: [Create a session property](https://www.dynatrace.com/support/help/platform-modules/digital-experience/web-applications/additional-configuration/define-user-action-and-session-properties) for a page that indicates the start of a potential converted session (i.e. Add to Cart Page Name).

# Target Audience

- Application Owner
- Line of Business
- Executive

# User Guide

The Conversion Overview Dashboard is broken down into three sections.

![Executive Overview Dashboard](EO2-1.png)

The top section is called the KPI banned. This section has the following KPIs:
- Avg Duration: Time between the initial user input and complete page load.
- Error Rate: Rate of Request, JavaScript and Custom Errors.
- Efficiency Rate: Rate of sessions that converted with good user experience. A perfect efficiency rate is 100.
- Deficiency Rate: Rate of sessions that abandoned with poor user experience. A perfect deficiency rate is 0.
- Conversion Rate: Rate of sessions that converted.
- Apdex: Application Performance Index is a standard developed by an alliance of companies for measuring the performance of applications. A perfect Apdex score is 1.

Each KPI cell has a blue drop down arrow on the right side. Click the blue drop down arrow and select Analyze to investigate the KPI in more detail. To the immediate right of each KPI cell, you will see a direction arrow or sign and a number. The arrow indicates the KPI trend, the color indicates if the trend is good or bad and the number indicates the change in the KPI. Each KPI is compared to a seven-day time shift for the current dashboard timeframe.

![Executive Overview Dashboard](EO2-2.png)

The middle section is broken down into three sections. The far left section contains a Top N tile with counts for Satisfied, Tolerating or Frustrating sessions. The far right section contains a world map for Satisfied, Tolerating or Frustrating sessions. The middle section contains KPI metric counts (with comparison to a seven-day time shift) for: 
- Total User Session Count
- New User Session Count
- User Action Request Count
- Conversion Count
- Bounce Count
- Abandon Count
 
![Executive Overview Dashboard](AO2-3.png)

The bottom section charts customer satisfaction (Satisfied, Tolerating or Frustrating) over time. 

# Deploy

https://dynatrace.github.io/BizOpsConfigurator/#deploy/persona/Analyst/Business%20Observability/Executive%20Overview%20(%F0%9F%92%8E)
