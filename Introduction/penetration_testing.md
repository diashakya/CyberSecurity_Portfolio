## Penetration testing or (Pen Testing)

Penetration Testing (also called Pen Testing or Ethical Hacking) is a simulated cyberattack performed on a computer system, network, or web application to identify and fix security vulnerabilities before malicious hackers can exploit them.

# 5 stages of Pen testing

1. Planning and reconnaissance

This is the information-gathering phase where testers prepare for the attack.

Goal: Understand the target system and define the scope.

Activities:

Identify domain names, IP addresses, and technologies used.

Decide what kind of tests will be performed (external/internal, black-box/white-box).

Get written permission to test (important for legal reasons!).

Think of this as preparing a map before exploring unknown territory.

2. Scanning

Now testers interact with the system to find open doors (vulnerabilities).

Goal: Find weaknesses in the system.

Tools/Techniques:

Nmap: to detect open ports and services.

Vulnerability scanners (like Nessus or OpenVAS).

Banner grabbing, OS fingerprinting.

# Two types of scanning:

Static: Examining code or configuration without running the app.

Dynamic: Running the system and watching for weaknesses in real-time.

3. Gaining Access

Here, the tester attempts to exploit vulnerabilities to enter the system.

Goal: Break into the system like a hacker would.

Common attack methods:

SQL injection

Cross-site scripting (XSS)

Password cracking

Buffer overflow

Tools like Metasploit help automate attacks in a safe environment.

4. Maintaining access

Once access is gained, the tester tries to stay inside the system—just like a real attacker would.

Goal: Check if attackers can remain undetected.

Techniques:

Install backdoors

Create hidden admin accounts

Escalate privileges

This helps understand how deep an attacker could go if the system is compromised.

5. Analysis

After the test, all findings are analyzed and reported.

Goal: Help the organization fix the issues.

The report includes:

Vulnerabilities found

Data accessed

Methods used

Risk levels

Fix recommendations (patches, config changes, etc.)

This final stage is important for learning and improving security.