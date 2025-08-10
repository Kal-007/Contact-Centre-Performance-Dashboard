📞 Contact Centre Performance Dashboard
📝 Project Overview
This project analyses key operational metrics from a contact centre to uncover performance trends, pinpoint underperformance areas, and highlight opportunities for service improvement.

For an Operations Supervisor role, this type of analysis is essential for:

Tracking team productivity and efficiency

Monitoring service quality through customer feedback

Identifying coaching and training opportunities for agents

Making data-driven decisions to improve KPIs

📂 Dataset
Source: PwC Call Centre Dataset (Kaggle)
Records: 5,000 calls
Fields Included:

Agent – Call handler’s name

Date & Time – When the call occurred

Topic – Call type (Technical Support, Payment, etc.)

Answered (Y/N) – Whether the call was answered

Resolved – If the issue was fixed on the first call

Satisfaction Rating – 1 to 5 scale

Average Talk Duration – Conversation length in HH:MM:SS

Speed of Answer – Time taken to pick up the call

🔍 Process & Approach
1. Data Preparation
Cleaned column names for consistency

Converted date/time formats into usable formats

Transformed talk duration into seconds to calculate AHT

Created binary indicators for answered calls and resolved calls

2. KPI Calculations
Average Handling Time (AHT): 292.44 seconds

First Time Resolution (FTR): 89.94%

Customer Satisfaction (CSAT): 3.40 / 5

3. Dashboard Visualisations
The dashboard includes:

AHT Trend Over Time – See efficiency day by day

CSAT by Agent – Compare satisfaction across team members

AHT by Topic – Identify call types that take the longest

FTR by Agent – Compare resolution effectiveness

FTR by Topic – See which issues are resolved most effectively

📊 Key Insights for Operations Supervision
Team Performance

AHT is generally stable but has spikes on specific days — could indicate staffing issues or surge in complex queries.

All agents have similar CSAT scores, suggesting consistent service delivery.

Process Improvement

“Admin Support” calls take longer on average — may require SOP review or agent refresher training.

High FTR rates in “Technical Support” and “Admin Support” show these areas have strong troubleshooting protocols.

Actionable Opportunities

Study methods used by top-performing agents (e.g., Greg, Jim) and share as best practice.

Aim to raise CSAT from 3.4 to >4.0 through improved follow-up and empathy training.

🚀 Skills Demonstrated (Relevant to Operations Supervisor Role)
Operational KPI Tracking – Turning raw data into meaningful metrics.

Performance Monitoring – Identifying trends, bottlenecks, and top/bottom performers.

Decision Support – Using visual dashboards to guide operational decisions.

Business Communication – Translating technical findings into management-ready insights.

📂 Project Files
call_centre_dashboard.ipynb – Full analysis and dashboard code

01 Call-Center-Dataset.xlsx – Dataset

README.md – Project overview and findings

contact_centre_dashboard.png – Dashboard snapshot

💡 Next Step (if implemented in real operations):

Automate daily dashboard updates

Integrate live KPI tracking for real-time decision-making

Include adherence and schedule compliance metrics