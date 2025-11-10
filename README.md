# bigquery-usage-monitor

## Dashboard Overview

This repository contains a documentation and analysis for BigQuery usage monitoring dashboard. There was a time where our BigQuery reached the query usage limit, and the whole data division was down, because it wont run any query for some times. So, this dashboard provides insights into query costs, user behavior, and usage patterns across the team, to drive cost awareness across team members.

---

## Key Performance Indicators

### Total Q3 Cost

![Total Q3 Cost KPI](images/total-q3-cost.png)

The total Q3 cost metric displays the aggregate spending on BigQuery queries for the entire quarter. This KPI provides a high-level view of overall expenses and serves as the primary indicator of our BigQuery cost during the reporting period.

### Top User Cost

![Top User Cost KPI](images/top-user-cost.png)

The top user cost metric highlights the highest individual contributor to BigQuery costs during Q3. This KPI helps identify power users and potential optimization opportunities by focusing on the most expensive user's query patterns and usage behavior.

---

## Usage Visualizations

### 1. Users Usage by Cost

![Top Users by Cost](images/top-users-by-cost.png)

This horizontal bar chart ranks users by their estimated BigQuery costs, with color coding to indicate usage status (moderate vs. normal usage). The visualization helps identify the primary cost drivers within the team and enables targeted optimization efforts for high-cost users.

### 2. Team Usage Summary

![Team Usage Summary](images/team-usage-summary.png)

This stacked horizontal bar chart breaks down estimated costs by role inside the team, and month of query execution. The visualization provides insights into how different team roles (data engineers, data scientists, data analysts) contribute to overall costs and how usage patterns have evolved across the quarter.

### 3. Weekly Cost Trend

![Weekly Cost Trend](images/weekly-cost-trend.png)

This line chart displays the estimated BigQuery costs over a 14-week period from Week 27 to Week 40 in Q3 of the year. The trend analysis reveals cost patterns over time, highlighting periods of increased or decreased usage and helping identify any anomalies or significant changes in spending behavior.

### 4. Peak Usage Day (Daily Usage)

![Peak Usage Day](images/peak-usage-day.png)

This bar chart shows the estimated costs for each day of the week, identifying which days experience the highest BigQuery usage. Understanding daily usage patterns helps with capacity planning and can reveal workflow patterns that drive cost fluctuations throughout the week.

---

