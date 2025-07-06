# Digital-Forensics-Report
Digital Forensics Investigation Report for Cyborts Organization, Instructor: Malik Saif Islam

Prepared By:
Hamza Ali
Date:
05-July-2025

Table of Contents
1. Executive Summary  
2. Introduction  
3. Scope and Objectives  
4. Methodology  
5. Investigation Findings  
  5.1 How was the system initially compromised?  
  5.2 What evidence shows malware executed in memory only (file less)?  
  5.3 What user activity helped the malware persist?  
  5.4 What deleted or hidden files were staged for exfiltration?  
  5.5 What browser activity suggests credential theft or staging?  
  5.6 Can you build a precise attack timeline using event logs?  
  5.7 What network artifacts indicate exfiltration?  
  5.8 What malware behaviours and system changes were observed?  

6. Chain of Custody  
7. Conclusion
8. Recommendations and Mitigations  

1. Executive Summary
This investigation simulates a phishing attack to analyse the initial compromise and subsequent malware activity on a Windows system. Using a combination of email analysis, memory forensics, registry examination, file recovery, browser artifact analysis, event log correlation, and network traffic inspection, we identified a file less malware infection that persisted through user activity and staged data for exfiltration. The report details the attack timeline, evidentiary artifacts, and provides actionable recommendations to mitigate similar threats in the future.
2. Introduction
The purpose of this investigation is to simulate and analyse a phishing-based compromise to understand the attack vectors, malware behaviour, and persistence mechanisms involved. This exercise aims to enhance detection and response capabilities by thoroughly examining system artifacts, memory, network traffic, and user activity. The investigation was conducted in a controlled environment with authorized access to ensure comprehensive forensic analysis.
3. Scope and Objectives
This digital forensics task aims to investigate a simulated cyberattack involving a phishing compromise, focusing on identifying the initial breach vector, malware behaviour, persistence mechanisms, and data exfiltration indicators. The objective is to apply forensic techniques on system artifacts, memory, network captures, and logs to reconstruct the attack timeline, uncover hidden or deleted evidence, and provide a comprehensive analysis of the malware's impact and persistence on the compromised system.
4. Methodology
The investigation employed a multi-faceted approach combining phishing simulation, forensic analysis, and malware behaviour examination. Tools such as Volatility were used for memory forensics, Autopsy and FTK for file recovery, and Wireshark for network traffic capture. Registry hives and browser artifacts were analysed to identify persistence and credential theft, while Windows event logs were correlated to build a precise attack timeline. All findings were documented with supporting evidence for a thorough understanding of the compromise.


See the full report for details.
