---
layout: default
---
# Azure SOC project

*  Successfully designed and implemented a fully functional homelab environment within Microsoft Azure, which is equipped with a SIEM tool. This setup enables the continuous monitoring, collection, and analysis of all security events. By leveraging the SIEM tool I can gain real-time insights into potential threats, track suspicious activities, and respond to security incidents.
 
*  Deployed a virtual machine (VM) within the environment with port 3389 intentionally left open, allowing users to attempt connections via Remote Desktop Protocol (RDP) to the machine. This configuration enabled me to gather valuable data on connection attempts including both successful and unsuccessful login activities, which could then be analyzed to identify attack patterns and attackers locations.
  
*  Effectively utilized the dashboard to continuously monitor and track all incoming events, alerts, and incidents in real time. This SIEM dashboard provided a centralized view, allowing me to proactively identify emerging threats, and quickly respond to any potential issues or anomalies.
  ![Screenshot 2024-12-14 164249](https://github.com/user-attachments/assets/61fcf61d-8274-4b4a-af45-11f8465a5fe1)

*  Deployed a custom security rule designed to automatically trigger an alert whenever a "Successful Local Sign-In" event is detected within the system. This rule was configured to continuously monitor authentication activities, ensuring that any successful logins to the local environment, whether legitimate or potentially suspicious, would be promptly flagged. By automating this process, I was able to streamline incident detection, improve response times, and maintain an enhanced level of oversight over access control.
  ![Screenshot 2024-12-14 163031](https://github.com/user-attachments/assets/dac90af1-30c0-4bef-932d-dbc934f8eeae)
