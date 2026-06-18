**🚀Scanning-Networks Report — Cyber Security**

<p align="center">
  <img src="https://www.stationx.net/wp-content/uploads/2023/11/Nmap-Vulnerability-Scan-How-to-Find-Weak-Systems-Easily.png" />
</p>

--------------------------------------------------------------------------------------------------------------------------------------------------

**🌐Introduction**

Network scanning is a critical phase of the cybersecurity assessment process. After footprinting and reconnaissance have identified potential targets, network scanning is used to discover live hosts, open ports, running services, operating systems, and potential vulnerabilities within a network environment.

Ethical hackers and security professionals use network scanning techniques to understand the attack surface of a target organization and identify security weaknesses before malicious actors can exploit them.

--------------------------------------------------------------------------------------------------------------------------------------------------

**Objectives of Network Scanning**

The primary goals of network scanning include:

1. Discovering active hosts on a network
2. Identifying open and closed ports
3. Detecting running services and versions
4. Determining operating systems
5. Mapping network topology
6. Identifying potential security vulnerabilities

--------------------------------------------------------------------------------------------------------------------------------------------------

**Types of Network Scanning**

1. Host Discovery Scanning

Host discovery identifies live systems connected to a network.

**Common Techniques**
1. ICMP Ping Sweep
2. ARP Scanning
3. TCP Ping Scan
4. UDP Ping Scan

Example
nmap -sn 192.168.1.0/24


--------------------------------------------------------------------------------------------------------------------------------------------------

2. TCP Connect Scan

A full TCP three-way handshake is performed to determine port status.

**Advantages**

1. Reliable results
2. Easy to perform

**Disadvantages**

1. Easily detected by security monitoring systems

Example
nmap -sT 192.168.1.10

--------------------------------------------------------------------------------------------------------------------------------------------------

4. SYN Scan (Stealth Scan)

A SYN packet is sent without completing the TCP handshake.

**Benefits**

1. Faster than TCP Connect Scan
2. Less likely to be logged

Example
nmap -sS 192.168.1.10

--------------------------------------------------------------------------------------------------------------------------------------------------

5. UDP Scan

Used to identify services running on UDP ports.

**Common UDP Services**

1. DNS (53)
2. DHCP (67/68)
3. SNMP (161)
4. NTP (123)

Example
nmap -sU 192.168.1.10


--------------------------------------------------------------------------------------------------------------------------------------------------

**Service Enumeration**

After identifying open ports, service enumeration determines the exact service and version running.

Example
Nmap -sV 192.168.1.10

**Port	Service	Version**
1. 22	SSH	OpenSSH 9.x
2. 80	HTTP	Apache 2.4
3. 443	HTTPS	Nginx

--------------------------------------------------------------------------------------------------------------------------------------------------

**Advanced Nmap Scanning**

Aggressive Scan
nmap -A 192.168.1.10

Includes:

1. OS Detection
2. Version Detection
3. Script Scanning
4. Traceroute


--------------------------------------------------------------------------------------------------------------------------------------------------

**Vulnerability Scanning**

nmap --script vuln 192.168.1.10

Used to identify known vulnerabilities associated with discovered services.

--------------------------------------------------------------------------------------------------------------------------------------------------

**Security Risks Revealed by Network Scanning**

Network scanning may expose:

1. Unnecessary open ports
2. Outdated services
3. Weak configurations
4. Exposed administrative interfaces


--------------------------------------------------------------------------------------------------------------------------------------------------

**Best Practices for Defenders**

1. Disable unused services.
2. Close unnecessary ports.
3. Implement firewall rules.
4. Monitor network traffic.


--------------------------------------------------------------------------------------------------------------------------------------------------

**Conclusion**

Network scanning is a foundational cybersecurity activity that enables security professionals to understand network exposure, identify active services, and assess potential vulnerabilities. By leveraging tools such as Nmap and following ethical guidelines, organizations can proactively strengthen their security posture and reduce the risk of cyber attacks.


**I hope you found this helpful :)**


--------------------------------------------------------------------------------------------------------------------------------------------------


#CyberSecurity #EthicalHacking #CEH #NetworkScanning #Nmap #SOCAnalyst #PenetrationTesting #InformationSecurity #BlueTeam #RedTeam
















