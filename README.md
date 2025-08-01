# Threat-Hunting-Using-SIEM-and-MITRE-Mapping
Group 7 Repository containing Report, Logs and Slides for the second group project. 
It contains the full detailed report, mitre mapping, queries used, raw logs,
siem dashboards and powerpoint presentation in their respective folders. 
The full detailed [report]()
) contains the steps taken to simulate an attack using APTSimulator 
in order to obtain [raw logs]((https://github.com/cyberwitch966/Threat-Hunting-Using-SIEM-and-MITRE-Mapping/tree/main/raw%20logs)) from Windows Event Viewer. The logs can be viwed in the folder raw logs 
which contains logs from sources such as sysmon, security, system and windows defender. 
These logs were injested into splunk where a dashboard was created with a focus on privilege escalation. 
Afterward the event ID's were used to map to MITRE, thus analyzing the path the attacker took. 
Lastly, a key findings, remediations and lessons learned section was created in the final report. 
A powerpoint presentation summarizing the proccess and findings can be found in this repository under presentation. 
