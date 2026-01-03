SSH Security Monitoring Dashboard 🛡️
Overview
This project is a Security Information and Event Management (SIEM) implementation designed to monitor, visualize, and analyze SSH authentication logs. Built using Splunk Enterprise, it transforms raw Linux server logs into actionable security intelligence, helping SOC analysts detect potential threats such as brute force attacks and unauthorized access attempts in real-time.

🚀 Key Features
Brute Force Detection: Uses statistical thresholds to identify IP addresses with high-volume failed login attempts.

Geospatial Intelligence: Visualizes the physical origin of attacks using Choropleth maps to spot anomalous traffic from non-business regions.

Threat Visualization: Interactive dashboards displaying Failed vs. Successful login trends and invalid user attempts.

Custom SPL Logic: meaningful data parsing and extraction using complex Search Processing Language queries.

🛠️ Technologies Used
Platform: Splunk Enterprise

Data Format: JSON (Linux SSH Logs)

Query Language: SPL (stats, top, iplocation, geom)

📊 Dashboard Insights
The dashboard is divided into three analytical zones:

Authentication Overview: KPIs for total events and success/failure rates.

Login Trends: Bar charts identifying usernames targeted by attackers.

Geo-Tracking: Map visualizations correlating IP addresses to specific countries.

🔧 How to Run
Ingest the ssh_logs.json file into a Splunk Index.

Copy the SPL queries from the /queries folder (or use the provided XML source).

Open the dashboard in Splunk to view the visualizations.
