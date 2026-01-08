Vulnerability Report
CVE Disovered

(DESIGNED TO BE RUN ON KALI LINUX)

Notes
Nagios has patched version 2024R1.0.1 in all recent downloads. To determine if a target is vulnerable, ensure they are using an older download of 2024R1.0.1.

The updated script checks to make sure that the target system is vulnerable

Vulnerability Details:
Endpoint: /nagiosxi//config/monitoringwizard.php Nagios XI Version 2024R1.0.1
Vulnerability Type: Authenticated SQL Injection
Exploitation Result: Admin account creation and full remote code execution
Proof of Concept:
Attached is the Python script demonstrating the vulnerability

Recommendation:
To mitigate the risk of SQL injection, it is strongly advised to use parameterized queries or prepared statements when interacting with databases. Parameterized queries ensure that user input is treated as data, not executable code, making it much more difficult for attackers to inject malicious SQL statements.
