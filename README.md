# Cyber-Journey
Day 1: Introduction to Red Team & Web Vulnerabilities
Date: [Bugünün Tarihi]

📌 Learned Concepts
Linux Permissions: Learned how to change file ownership and permissions using chmod.
Network Recon: Used nmap for scanning open ports (e.g. 22 SSH, 80 HTTP).
Burp Suite Basics: Captured and modified HTTP requests using the Proxy and Repeater tabs.
💥 Exploits Executed (Authorized Sandbox environments)
SQL Injection (Authentication Bypass):
Target: http://demo.testfire.net/login.jsp
Payload: admin' or '1'='1
Result: Successfully bypassed the login screen and gained Admin access.
Cross-Site Scripting (Reflected XSS):
Target: Search Box on Altoro Mutual
Payload: <script>alert('YASAR BURADAYDI!')</script>
Result: Executed arbitrary Javascript on the client side.
