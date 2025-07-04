# Basic Network Monitoring: Deploying an Intrusion Detection System IDS

<h2>Description</h2>

This project involved setting up a foundational network monitoring environment using an open-source Intrusion Detection System (IDS), Suricata, within a virtual machine. The goal was to capture, analyse, and interpret network traffic to identify potential security events and anomalous activities. This hands-on exercise demonstrates the critical first steps in network security monitoring and proactive threat detection.

<h2>Objective</h2>

The primary objective of this project was to deploy and configure the open-source Intrusion Detection System (IDS), Suricata, within a Linux virtual machine environment. This included setting up Suricata to monitor network traffic for suspicious activity using predefined rulesets, as well as generating various types of network traffic such as web browsing, ping requests, and DNS queries. The project also involved analysing and interpreting alerts and logs, specifically Suricata’s EVE.json output, to understand and investigate detected events. Overall, this work demonstrates foundational skills in network traffic analysis and threat identification within a security operations context.

<h2>Key Skills Demonstrated</h2>

* **Foundational IDS Deployment: Successfully deployed and configured an open-source IDS from scratch, a critical skill for network security.**
* **Importance of Rulesets: Understood how predefined rules (signatures) enable the IDS to identify known threats and suspicious patterns.**
* **Log Interpretation: Gained hands-on experience in analysing Suricata's eve.json logs, extracting key information like source/destination, protocol, and alert details. This is directly transferable to working with SIEMs.**
* **Network Visibility: Reinforced the concept that monitoring network traffic is essential for detecting activity that bypasses endpoint security or occurs at the network layer.**
* **Building a Home Lab: Strengthened skills in virtualisation and Linux system administration, valuable for future cybersecurity experiments and learning.**
* **Data Analysis for Security Investigations: Identifying anomalies and suspicious patterns.**
* **Proactive Security: Recognised how an IDS acts as a proactive defence mechanism, alerting analysts to potential breaches or policy violations in real time.**

<h2>Program walk-through:</h2>

<p align="center">
Step 1: Suricata Installation. Installed Suricata on the Ubuntu Server VM via the package manager. <br/>
   
<img src="https://github.com/user-attachments/assets/edf9672d-02b2-48a8-9aba-e85a74a47a79" width="653" alt="Step 1 Screenshot"/>
<br />
<img src="https://github.com/user-attachments/assets/42a15c97-2116-4383-b620-3e2c1e0b97d6" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 2: Suricata Configuration & Rule Management. Edited the main Suricata configuration file (/etc/suricata/suricata.yaml) to specify the network interface to monitor (e.g., eth0 or enp0s3), and ensured default rule sets were enabled (Suricata. rules or pulling ET Open rules). <br/>
   
<img src="https://github.com/user-attachments/assets/9ef935e0-c8b5-4707-b5c4-72f8d3bb88d5" width="653" alt="Step 1 Screenshot"/>
<br />
<img src="https://github.com/user-attachments/assets/ea46a941-fd7c-47e6-96db-aa94c8a18e1c" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 3: Generating Test Network Traffic. Now we’ll create some normal network activity to see if Suricata picks it up. <br/>
   
<img src="https://github.com/user-attachments/assets/4dff3fc3-1ba3-4289-801c-b440ea5b0ee1" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 4: Starting Suricata & Monitoring Logs <br/>
   
<img src="https://github.com/user-attachments/assets/3909937e-6ec5-487a-84ac-69d0455c7113" width="653" alt="Step 1 Screenshot"/>
<br />


<h2>Key Learnings & Takeaways:</h2>

* **Solidified understanding of how different SQL filtering operators (AND, OR, NOT, LIKE, IN, !=) can be combined for highly precise data retrieval.**
* **Gained practical experience in translating complex business and security questions into efficient database queries.**
* **Learned the importance of structured querying for effective data analysis in both security investigations and routine operations.**
* **Enhanced problem-solving skills by breaking down data requirements into logical SQL constructs.**
