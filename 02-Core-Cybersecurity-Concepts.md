
# 02 – Core Cybersecurity Concepts

This file contains the **foundational cybersecurity concepts** every beginner or aspiring security professional should know.  
Understanding these concepts is crucial before moving on to hands-on labs, real-world testing, or advanced research.

---

## 🔐 CIA Triad

The **CIA Triad** is the backbone of cybersecurity. Every security control, policy, and system design decision revolves around these three principles:

1. **Confidentiality** – Data should only be accessible to authorized users.  
   *Example*: Encrypt sensitive files to prevent unauthorized access.  

2. **Integrity** – Data should not be altered without proper authorization.  
   *Example*: Use hashing or checksums to verify file integrity.  

3. **Availability** – Systems and data must be accessible when needed.  
   *Example*: Implement redundancy and backups to prevent downtime.  

> **Reference:** [OWASP - Security Principles](https://owasp.org/www-project-top-ten/)

---

## 👤 Authentication vs Authorization

These two terms are often confused but are **distinct and critical**:

- **Authentication** – Verifying *who* a user is.  
  *Techniques*: Passwords, biometrics, 2FA/MFA, certificates.  
  *Example*: Logging into Gmail requires your password + 2FA code.  

- **Authorization** – Determining *what* a user can do.  
  *Example*: A standard user cannot access admin-only sections on a website.  

> **Common vulnerability:** Broken Access Control (authorization flaw) leads to data leaks and privilege escalation.  
> **Reference:** [OWASP Broken Access Control](https://owasp.org/Top10/A01_2021-Broken_Access_Control/)

---

## 🧩 Common Threats & Attacks

Understanding attacker methods is key to building defenses. Some common threats include:

| Threat / Attack | Description | Example / Reference |
|-----------------|------------|------------------|
| Phishing & Social Engineering | Trick users into revealing credentials | [Phishing Guide](https://us-cert.cisa.gov/ncas/tips/ST04-014) |
| Malware & Ransomware | Malicious software that damages or locks systems | WannaCry attack (2017) |
| SQL Injection (SQLi) | Attacker injects malicious SQL into forms | [OWASP SQL Injection](https://owasp.org/www-community/attacks/SQL_Injection) |
| Cross-Site Scripting (XSS) | Inject malicious scripts into web pages | [OWASP XSS](https://owasp.org/www-community/attacks/xss/) |
| Broken Access Control / IDOR | Users can access unauthorized resources | [OWASP Access Control](https://owasp.org/Top10/A01_2021-Broken_Access_Control/) |
| Man-in-the-Middle (MITM) | Intercepting communication between users & systems | Use HTTPS / TLS to prevent |

---

## 🧱 Defense in Depth

**Defense in Depth** means **layered security**: no single control is enough. Multiple controls reduce risk.

**Examples:**
- Network: Firewalls, segmentation  
- Application: Input validation, authentication controls  
- Data: Encryption at rest & in transit  
- Monitoring: Logs, alerts, IDS/IPS  

> **Reference:** [NIST Defense in Depth](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)

---

## 🔍 Risk, Threat & Vulnerability

These are the **key building blocks of security assessments**:

- **Threat** – Something that can cause harm (attacker, malware, insider).  
- **Vulnerability** – A weakness that can be exploited (unpatched software, misconfigurations).  
- **Risk** – Likelihood and impact of a threat exploiting a vulnerability.  

> **Formula (simplified):**  
> Risk = Likelihood × Impact  

> **Reference:** [NIST Risk Management Framework](https://csrc.nist.gov/publications/detail/sp/800-37/rev-2/final)

---

## 🗂️ Security Controls

Security controls safeguard systems and reduce risk:

| Type | Example |
|------|---------|
| Preventive | Firewalls, strong passwords, input validation, MFA |
| Detective | Logs, SIEM alerts, intrusion detection systems (IDS) |
| Corrective | Incident response, patch management, backups |

> **Reference:** [ISO/IEC 27001 Controls](https://www.iso.org/isoiec-27001-information-security.html)

---

## 📜 Security Principles

Some guiding principles for secure systems:

- **Least Privilege** – Users should have only the access they need.  
- **Secure by Design** – Security should be part of the architecture from the start.  
- **Fail Securely** – Systems should fail in a safe state.  
- **Zero Trust** – Never trust, always verify.  
- **Assume Breach** – Design systems as if attackers are already inside.

> **Reference:** [OWASP Security Principles](https://owasp.org/www-project-top-ten/)

---

## 💡 Why These Concepts Matter

- Explain **why vulnerabilities exist**  
- Help **prioritize findings** in assessments  
- Enable **clear communication** with technical and non-technical stakeholders  
- Form the foundation for **all cybersecurity roles**

---

## 📚 Suggested References & Resources

1. **OWASP Top 10** – [https://owasp.org/www-project-top-ten/](https://owasp.org/www-project-top-ten/)  
2. **NIST Cybersecurity Framework** – [https://www.nist.gov/cyberframework](https://www.nist.gov/cyberframework)  
3. **TryHackMe / Hack The Box** – Hands-on labs  
4. **Krebs on Security Blog** – Real-world case studies  
5. **“The Web Application Hacker's Handbook”** – Practical web security  
6. **ISO/IEC 27001** – Information security management standards

---

➡️ **Next Step:** Move to **03-Hands-On-Learning** to practice these concepts in labs and exercises.
