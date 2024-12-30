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

The tool checks for the presence of essential HTTP headers like Strict-Transport-Security and X-Frame-Options to ensure the server is configured with basic security protections. If any of these headers are missing, the tool issues warnings to indicate potential security risks.

Technologies Used:
* Python: The code is written in Python, leveraging basic programming concepts like conditional statements, loops, and functions.
* Regular Expressions (re): The re module is used to match specific patterns in the password, such as digits, uppercase letters, and special characters.
* Standard Python Functions: Functions like input(), print(), and list manipulations (e.g., append()) are used.

Key Insights:
* Password Complexity: Password strength is determined by multiple factors, including length, character variety (upper, lower, digits, special characters), and avoiding commonly used passwords.
* Regular Expressions: Using re.search() simplifies the task of identifying specific patterns in strings, making it easier to evaluate password strength efficiently.
* Feedback Mechanism: Providing clear and actionable feedback helps users improve their passwords by addressing specific weaknesses.
* Security Considerations: Common password checks (like "123456" or "password") help mitigate weak password choices and encourage users to create more secure passwords.
* Scoring System: The scoring system helps categorize passwords into "Weak", "Moderate", or "Strong", offering a simple yet effective way to convey security level to users.
