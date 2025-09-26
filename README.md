# Elevate-Labs-Tasks-3

Task 3

# Perform a Basic Vulnerability Scan on Your PC

## Objective
Use free tools to identify common vulnerabilities on your computer.


### Tools Used

- **Kali Linux** for penetration testing and security auditing.
- **Nessus Essentials** Nessus Essentials is used to practice finding and fixing security vulnerabilities

## Steps

Below are the key steps taken in the VAPT process:

### 1. Install Nessus Essentials
Checked the given link below
https://www.tenable.com/products/nessus/nessus-essentials

- Select New Scan
- Click Basic Scan
- Give the ip of the machine to scan
- Start scan

### 2. Review the report for vulnerabilities and severity.



![]([https://github.com/Abhijithprashanth/Elevate-Labs-Tasks/blob/main/nmap%20version.png](https://github.com/Abhijithprashanth/Elevate-Labs-Tasks-3/blob/main/Screenshot%202025-09-26%20171853.png))

![](https://github.com/Abhijithprashanth/Elevate-Labs-Tasks-3/blob/main/Screenshot%202025-09-26%20171914.png)

![](https://github.com/Abhijithprashanth/Elevate-Labs-Tasks-3/blob/main/Screenshot%202025-09-26%20172046.png)


### 3. Research simple fixes or mitigations for found vulnerabilities.

Problem 1 : Your version of Node.js is outdated and has serious security issues

- If you are using Node 18, update to 18.19.1 or later
 - If you are using Node 20, update to 20.11.1 or later
 - If you are using Node 21, update to 21.6.2 or later

Problem 2 : Your system is running an outdated version of Node.js - a tool used to build servers and web apps. The version you ahve has security flaws that can be exploited by attackers

Update secure versions such as 
 - 18.20.1 or later
 - 20.12.1 or later
 - 21.7.2 or later
 

### 4. Document the most critical vulnerabilities.

Critical Vulnerability

CVSS Score: 9.8
VPR: 5.9
EPSS: 0.1041
Family: Misc.
Count: 1
Severity: CRITICAL

High Severity Vulnerabilities

CVSS Score: 8.2
VPR: 5.0
EPSS: 0.6447
Family: Misc.
Count: 1
Severity: HIGH

CVSS Score: 8.1
VPR: 6.7
EPSS: 0.0074
Family: Misc.
Count: 1
Severity: HIGH

CVSS Score: 7.7
VPR: 5.2
EPSS: 0.0006
Family: Misc.
Count: 1
Severity: HIGH

CVSS Score: 7.5
VPR: 5.1
EPSS: 0.0041
Family: Misc.
Count: 1
Severity: HIGH

![](https://github.com/Abhijithprashanth/Elevate-Labs-Tasks-3/blob/main/Screenshot%202025-09-26%20172117.png)

### 5. Conclusion
The vulnerability scan helped me identify open ports, outdated services, and missing patches on my system. I learned how to analyze scan reports, understand risk levels (Low to Critical), and apply simple fixes like updates, closing unused ports, and using firewalls. This gave me basic hands-on experience in vulnerability assessment and risk mitigation.
