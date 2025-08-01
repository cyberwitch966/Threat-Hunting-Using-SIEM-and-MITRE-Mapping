# Threat-Hunting-Using-SIEM-and-MITRE-Mapping
Group 7 Repository containing Report, Logs and Slides for the second group project. 
It contains the full detailed report, mitre mapping, queries used, raw logs,
siem dashboards and powerpoint presentation in their respective folders. 
The full detailed [report](https://github.com/cyberwitch966/Threat-Hunting-Using-SIEM-and-MITRE-Mapping/tree/63e2874ff6105dbfd1fb94b1f2e5a426e3c1241b/report) contains the steps taken to simulate an attack using APTSimulator 
in order to obtain [raw logs](https://github.com/cyberwitch966/Threat-Hunting-Using-SIEM-and-MITRE-Mapping/tree/c93b239aa103ce66dab2546af9149f2f8aa21876/raw%20logs) from Windows Event Viewer. The logs can be viwed in the folder raw logs 
which contains logs from sources such as sysmon, security, system and windows defender. 
These logs were injested into splunk where a [dashboard](https://github.com/cyberwitch966/Threat-Hunting-Using-SIEM-and-MITRE-Mapping/tree/2b053e2bead777e4b1800a90eb099a20aa110206/privilege%20escalation%20dashboard) was created with a focus on privilege escalation. 
[Additional dashboards](https://github.com/cyberwitch966/Threat-Hunting-Using-SIEM-and-MITRE-Mapping/tree/80f9c0c445c78996aa5c28e09bd7c86f593e094e/additional%20dashboards%20and%20logs)) were created, showcasing the extra findings. 
Afterward the event ID's were used to [map to MITRE](https://github.com/cyberwitch966/Threat-Hunting-Using-SIEM-and-MITRE-Mapping/tree/80f9c0c445c78996aa5c28e09bd7c86f593e094e/MITRE%20Mapping), thus analyzing the path the attacker took. 
In addition, a key findings, remediations and lessons learned section was created in the final report. 
Lastly, a [powerpoint presentation](https://github.com/cyberwitch966/Threat-Hunting-Using-SIEM-and-MITRE-Mapping/tree/80f9c0c445c78996aa5c28e09bd7c86f593e094e/presentation) summarizing the proccess and findings can be found in the presentation directory. 
