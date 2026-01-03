SSH Security Monitoring Dashboard 🛡️🔍
Overview
SIEM project converting Linux SSH auth logs into real-time threat intel via Splunk Enterprise. Ideal for SOC analysts spotting brute force, unauthorized access, and anomalies through dynamic visualizations.
​

🚀 Key Features
Brute Force Alerts 💥: Highlights IPs with excessive failed attempts via stats thresholds

Geo Mapping 🌍: Choropleth visuals tracing attacks to global hotspots

Trend Analysis 📈: Failed vs. successful ratios and targeted invalid users

SPL Intelligence ⚙️: Advanced parsing with location/geo functions for precise insights

🛠️ Tech Stack
Core: Splunk Enterprise Free

Logs: JSON from /var/log/auth.log

Viz Tools: Panels, gauges, heatmaps, timelines

Extras: iplocation/geom for spatial data

📊 Dashboard Layout
Authentication KPIs 🎯
Total events | Success rate: 23% ✅ | Failure spikes: 77% ❌ | Risk score gauge

Attack Patterns ⚠️

Top targeted usernames (bar chart)

Invalid login attempts (pie chart)

Attacker IP leaderboard (table)

Global Threat Map 🗺️
Interactive choropleth: Attack volume by country/region clusters

🚀 Setup Guide
Upload ssh_logs.json to Splunk index 🗂️

Import dashboard XML from repo 📥

Launch in Search & Reporting app—live viz ready! ▶️


