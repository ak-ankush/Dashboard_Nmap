# Dashboard_Nmap
This project presents an interactive Power BI dashboard that visualizes and analyzes network scan data collected using Nmap. The dataset contains sample data to demonstrate how Power BI can be used to visualize network security insights.

Total Rows Count - 1000

Total Column Count - 6

### Columns Explaination
1. IP Address – The unique identifier assigned to each scanned device within the network.
2. Host Status – Indicates whether the host is online or offline at the time of the scan.
3. Detected OS – The operating system detected on the scanned host, based on Nmap fingerprinting.
4. Open Port – Ports that are open and accessible on the scanned device, which could indicate running services or security risks.
5. Service – The specific service associated with each open port, such as HTTP, FTP, SSH, etc.
6. Vulnerability – Identified security vulnerabilities related to the open ports and services, based on Nmap scripts or third-party security databases.

### Summary of Insights
1. Most common OS - Ubuntu 20.04 & Windows Server.
2. Most frequently found services - SSH & PostgreSQL.
3. High-risk vulnerabilities present - 87 detected cases.
4. Commonly open ports - 22, 5432, 443, 25, 8080.
5. Most common vulnerability - default passwords

### Dashboard Output

![image](https://github.com/user-attachments/assets/a11b560b-219e-4c77-9d1f-41c99d4cb544)
