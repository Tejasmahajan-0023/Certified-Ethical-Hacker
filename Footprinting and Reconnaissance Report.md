**🚀Footprinting and Reconnaissance Report — Cyber Security**

<p align="center">
  <img src="https://github.com/user-attachments/assets/178caca7-00c0-4b8d-adf2-2cc2a8fccb9d" />
</p>

--------------------------------------------------------------------------------------------------------------------------------------------------

**🌐Introduction**

Footprinting and reconnaissance are the first phases of ethical hacking and penetration testing. The objective is to gather information about a target organization, system, or network using passive and active techniques. The information collected helps security professionals identify potential attack surfaces and assess security risks.

--------------------------------------------------------------------------------------------------------------------------------------------------

**Objectives**

1. Identify publicly available information about the target.
2. Discover domains, subdomains, and IP addresses.
3. Gather employee and organizational information.
4. Identify technologies and services used by the target.
5. Assess potential security risks from exposed information.

--------------------------------------------------------------------------------------------------------------------------------------------------

**Scope**

Target: Footprinting Reconnaissance

Assessment Type: Open Source Intelligence (OSINT) and Reconnaissance


--------------------------------------------------------------------------------------------------------------------------------------------------

**Methodology**

**4.1 Passive Reconnaissance :-**

Passive reconnaissance involves collecting information without directly interacting with the target systems.

Techniques Used:

WHOIS Lookup
DNS Enumeration
Search Engine Reconnaissance
Social Media Analysis
Public Document Metadata Analysis
GitHub Repository Analysis

**4.2 Active Reconnaissance :-**

Active reconnaissance involves interacting directly with target systems.

Techniques Used:

Network Scanning
Port Scanning
Service Enumeration
Subdomain Discovery

--------------------------------------------------------------------------------------------------------------------------------------------------

**Tools Used**

1. WHOIS 
<details>
<summary>Purpose</summary>

**Domain registration information**

</details>

2. nslookup

<details>
<summary>Purpose</summary>

**DNS records lookup**

</details>

3. Nmap

<details>
<summary>Purpose</summary>

**Port and service scanning**

</details>

4. theHarvester

<details>
<summary>Purpose</summary>

**Email and subdomain discovery**

</details>

5. Shodan

<details>
<summary>Purpose</summary>

**Internet-connected device discovery**

</details>

--------------------------------------------------------------------------------------------------------------------------------------------------

**Information Gathered**

**Domain Information :-**
1. Domain Name: example.com
2. Registrar: Example Registrar
3. Creation Date: XX/XX/XXXX
4. Expiration Date: XX/XX/XXXX

**DNS Records :-**
1. A Record
2. MX Record
3. TXT Record
4. NS Record
   
**Subdomains Discovered :-**
1. mail.example.com
2. portal.example.com
3. api.example.com
4. dev.example.com

**Email Addresses Found :-**
1. admin@example.com
2. support@example.com

**Technologies Identified :-**
1. Web Server: Apache/Nginx
2. CMS: WordPress
3. Programming Language: PHP
4. Cloud Provider: AWS/Azure

--------------------------------------------------------------------------------------------------------------------------------------------------

**GitHub Reconnaissance**

**Purpose** 

Analyze publicly available GitHub repositories associated with the target organization.

**Findings**

1. Public repositories discovered.
2. Developer usernames identified.
3. Technology stack identified.
4. Configuration files exposed.
5. API keys and secrets checked.

**Risk Assessment**

Potential risks include:

1. Hardcoded credentials
2. Exposed API keys
3. Internal documentation leakage
4. Sensitive configuration files


--------------------------------------------------------------------------------------------------------------------------------------------------

**Recommendations**

1. Remove sensitive information from public repositories.
2. Implement secret scanning on GitHub.
3. Restrict public exposure of internal documentation.
4. Regularly audit DNS records.

--------------------------------------------------------------------------------------------------------------------------------------------------

**Conclusion**

The footprinting and reconnaissance assessment successfully identified publicly available information about the target organization. While such information is often publicly accessible, attackers may leverage it to plan further attacks. Continuous monitoring, repository audits, and security awareness programs are recommended to minimize information exposure and improve overall security posture.


**I hope you found this helpful :)**

--------------------------------------------------------------------------------------------------------------------------------------------------



