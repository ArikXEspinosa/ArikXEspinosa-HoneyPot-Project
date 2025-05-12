# HoneyPot-Project

## Objective
The purpose of this project create a demo Honeypot to use to stimutlate attacks on SSH.

### Skills Learned


-Gained a deep understanding of honeypot functionality and its role in cybersecurity.

-Developed a custom honeypot script in Python to simulate a vulnerable service.

-Deployed and operated the honeypot on a Rocky Linux machine.

-Deployed and managed the honeypot on a Rocky Linux environment.

-Simulated brute-force attacks using Hydra from Kali Linux to test honeypot effectiveness.

-Created deceptive fake login prompts and scripted false flags to mislead attackers.

-Logged all attacker attempts with timestamps, IP addresses, and attempted credentials for analysis.

-Learned how to open, close, and monitor firewall ports using Linux tools and commands.

-Used systemctl to manage services and clear activity on ports, ensuring proper honeypot reset.

-Strengthened command-line proficiency with nano, systemctl, and other Linux tools.


### Tools Used

-Python – for writing the honeypot script and managing response logic.

-Rocky Linux – as the deployment environment for the honeypot.

-Kali Linux (Hydra) – to simulate brute-force attacks.

-Nano – for quick in-terminal script and config file editing.

-Firewall-cmd / iptables – for opening/closing ports and configuring firewall rules.

-Systemctl – to manage services and clear/reset port activity as needed.

-Syslog / Custom Logging – to capture and store detailed attack data.

-SSH / Linux Terminal – for server access and remote honeypot administration.




## Steps
1. Setup & Environment Preparation
Installed Rocky Linux as the base operating system for the honeypot deployment.

Updated system packages and installed necessary tools like Python, nano, and firewall-cmd.

Configured the firewall to control which ports were open, closed, or monitored using firewall-cmd.

2. Honeypot Script Development
Wrote a Python script to simulate a login service, intentionally made to look vulnerable.

Programmed the honeypot to accept fake credentials, log all login attempts, and timestamp each entry.

Designed it to mislead attackers by providing fake responses and simulated success messages.

3. Testing & Simulated Attacks
Deployed the honeypot and accessed it remotely to test functionality.

Used Hydra from a Kali Linux machine to simulate brute-force login attacks.

Verified that the honeypot captured each attempt along with method, IP address, and timestamp.

4. Firewall & Port Management
Opened and monitored specific ports using firewall-cmd for attack simulation.

Used systemctl to manage honeypot services and clear previous activity on ports to reset for new tests.

Ensured ports were properly secured post-testing.

5. Logging & Analysis
Configured the script to write logs to a designated file for later analysis.

Reviewed logs to analyze attacker behavior, patterns, and time-based activity.

Ensured logs were stored persistently and securely for educational and reporting purposes.

6. Documentation & Review
Created a presentation summarizing the honeypot's design, deployment, testing, and findings.

Share the documentation with the IT team for future reference.
### 📊 Presentation
[View Honeypot Network Documentation Presentation (Google Slides)](https://docs.google.com/presentation/d/1zn4ZKPaTL-WNcau4vFeQp6hTrQ5EaEq1/edit?usp=drive_link&ouid=112130089608892881782&rtpof=true&sd=true)

---
