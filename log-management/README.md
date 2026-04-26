🔍 Log Management Investigation (LetsDefend)
📌 Objective

Use SIEM log management to identify suspicious activity and analyze indicators of compromise (IOC).

🧪 Scenario

A suspicious file execution was detected:

File: nmap
MD5: 83e0cfc95de1153d405e839e53d408f5
🔎 Investigation Steps
Accessed Log Management in LetsDefend
Switched from network logs → endpoint/process logs
Searched using:
Partial hash: 83e0
Keyword: nmap
Located matching log entry
Verified:
File name
Hash value
Hostname
🖥️ Findings
Hostname: (PUT YOUR ANSWER HERE)
File Executed: nmap
Hash: 83e0cfc95de1153d405e839e53d408f5
⚠️ Analysis

The use of nmap indicates possible:

Internal reconnaissance
Network scanning activity
🛡️ Recommendations
Isolate affected host
Monitor network traffic
Perform endpoint scan
Investigate lateral movement
📸 Evidence
<img width="968" height="473" alt="image" src="https://github.com/user-attachments/assets/7c112121-b058-454f-a94d-29d94474b75d" />

✅ Conclusion

Suspicious reconnaissance activity was identified through log analysis.
