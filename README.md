Name : SHREYAS THOSKAR U
Company: CODTECH IT SOLUTIONS
ID: CTO8DS365
Domain: CyberSecurity and Ethical Hacking
Duration: 5 DECEMBER 2024 - 5 JANUARY 2025
Mentor: SRAVANI GOUNI

OVERVIEW OF THE PROJECT:

Project : Vulnerability Scanner

Objective: The objective of this project is to create a tool that can scan a network or a website for common security vulnerabilities, such as open ports, outdated software versions, and HTTP header misconfigurations. This tool checks a target IP for open ports, evaluates the server’s software version, and inspects critical HTTP headers for proper security configurations.


Key Activities:
* Port Scanning: The tool scans a list of specified ports (e.g., 22, 80, 443, 8080) on a given target IP address to detect open ports. This helps in identifying potential entry points for unauthorized access.
* Software Version Check: The tool makes an HTTP request to the specified URL and retrieves the server information from the response headers. This allows it to detect the server type (e.g., Apache, Nginx, IIS), 
  which can reveal the software version being used and indicate if there are any known vulnerabilities associated with that version.
* HTTP Security Header Check: The tool checks for the presence of essential HTTP headers like Strict-Transport-Security and X-Frame-Options to ensure the server is configured with basic security protections. If 
  any of these headers are missing, the tool issues warnings to indicate potential security risks.


Technologies Used:
* Python: Python is used as the primary programming language for this project, leveraging built-in libraries such as socket for port scanning and requests for HTTP requests and header analysis.
* Requests Library: The requests library is used to send HTTP requests to the target URL and analyze the response headers.
* Socket Library: The socket library is used to create TCP/IP connections for port scanning, checking whether specific ports on a target machine are open.


Key Insights:
* Security of Web Servers: The project highlights the importance of basic security configurations, such as having the right HTTP headers (e.g., Strict-Transport-Security), which prevent certain web-based attacks 
  like clickjacking or man-in-the-middle attacks.
* Software Version Vulnerabilities: Detecting server software and version can give insights into whether the server is running outdated software that might be vulnerable to known exploits.
* Network Entry Points: Open ports can provide valuable information regarding possible entry points into a network or system. The tool helps identify which ports are open and could potentially be misused by 
  attackers.
* HTTP Header Security: The project emphasizes checking for crucial HTTP headers that add an additional layer of security to websites, particularly those related to HTTPS enforcement and frame protection.
