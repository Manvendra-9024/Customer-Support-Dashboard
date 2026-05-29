# Customer Support Dashboard

## Overview
Tracks and visualizes customer support operations including ticket volumes, resolution times, agent performance, and customer satisfaction scores.

## Tools & Technologies
- **Power BI** – Primary support dashboard
- **SQL** – Helpdesk database queries
- **Excel** – Weekly report templates
- **Python** – CSAT trend analysis

## Metrics Covered
- Total tickets by priority, status, and category
- Average first response and resolution time
- Agent performance leaderboard
- CSAT scores and NPS trends
- SLA compliance rate

## Project Structure
```
customer_support_dashboard/
├── dashboard/
│   └── support_dashboard.pbix
├── sql/
│   └── support_queries.sql
├── reports/
│   └── weekly_report_template.xlsx
├── analysis/
│   └── csat_analysis.py
└── README.md
```

## Setup
1. Connect Power BI to your helpdesk SQL database
2. Run `sql/support_queries.sql` to validate data
3. Open `dashboard/support_dashboard.pbix`
