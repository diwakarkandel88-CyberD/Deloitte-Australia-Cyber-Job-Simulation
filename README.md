# Deloitte-Australia-Cyber-Job-Simulation
#Deloitte Australia — Cyber Job Simulation (Forage)

Platform: Forage Company: Deloitte Australia — Cyber Team Category: Incident Response / Log Analysis Date: August 2026

Hi there, I'm Diwakar. LinkedIn: https://www.linkedin.com/in/diwakarkandel88/ 

🔎 MSc Cyber Security Management student | Aspiring SOC Analyst | Actively building hands-on skills through labs and simulations

💡Lab Information:
Simulation: Deloitte Australia Cyber Job Simulation
Category: Incident Response, Log Analysis, Breach Investigation
Tasks completed: 1 (2-part investigation)


💡Objective:
The goal of this simulation was to support a client through a suspected data breach investigation — determining whether the breach could have originated from an external attacker with no VPN access, and identifying the responsible user by analyzing raw web activity logs.

💡Scenario:
A client (Daikibo) suspected a data breach on its internal telemetry dashboard. As part of Deloitte's cyber team, my task was to:

🔸Assess whether an attacker without VPN access could have caused the breach directly from the internet
Inspect a web_requests.log file covering the suspected attack window to identify suspicious activity

🔸Approach
   🔹Reviewed the log structure: each block represents one internal IP address's request history, sorted by time, spanning one or more browsing sessions
   🔹Reconstructed what normal user behavior looks like: login → dashboard resource loads (styles, scripts, images) → API requests for machine status
   🔹Compared this baseline against the data to spot deviations from typical human browsing patterns
   🔹Looked specifically for automated behavior — requests to the API repeating at exact, fixed time intervals, which isn't consistent with manual page refreshes (since there's no continuous polling in the legitimate app)
   🔹Identified the user ID tied to the anomalous, machine-like request pattern

💡Key Takeaway:
Incident response often comes down to pattern recognition rather than exotic tools. Understanding what normal traffic looks like makes anomalies — like scripted, precisely-timed requests — stand out clearly. This mirrors the analysis approach I used in my SSH brute-force investigation project, applied here to a different log format and threat scenario.

💡Skills Practiced:
🔹Log analysis and interpretation
🔹Breach/incident investigation methodology
🔹Anomaly detection through behavioral baselining
🔹Structured, evidence-based reasoning for security findings

💡Certificate:
             Verified completion certificate available on request / linked( https://www.theforage.com/completion-certificates/9PBTqmSxAf6zZTseP/E9pA6qsdbeyEkp3ti_9PBTqmSxAf6zZTseP_6a7e55a839236092b8144433_1786789477111_completion_certificate.pdf ) on my LinkedIn profile.
