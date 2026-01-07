# SOC Analyst Career Roadmap

A Security Operations Center (SOC) Analyst is a defender. They are the first line of defense, monitoring network traffic and logs to detect, investigate, and respond to cyber threats in real-time.

## 🟢 Level 1: Core Fundamentals
Before diving into logs, you must understand what "normal" traffic looks like.
* **Networking Mastery:** Deep dive into OSI layers, subnets, and protocols (HTTP, DNS, SMB, SMTP, RDP).
* **Windows & Linux Internals:** Understanding processes, services, event logs, and file systems.
* **Security Concepts:** The Diamond Model of Intrusion Analysis and the Cyber Kill Chain.



---

## 🟡 Level 2: Detection & Analysis (The "Bread and Butter")
This level focuses on the tools used to see what is happening across the enterprise.
* **SIEM (Security Information and Event Management):**
    * Learning how to query and build dashboards.
    * *Tools:* **Splunk** (Search Processing Language - SPL), **Microsoft Sentinel**, or **ELK Stack**.
* **Log Analysis:** Analyzing Windows Event Logs, Sysmon, and Firewall logs to spot anomalies.
* **Traffic Analysis:** Packet capture (PCAP) analysis.
    * *Tools:* **Wireshark**, **Tcpdump**.

---

## 🟠 Level 3: Defensive Technical Skills
Moving from just "watching" to "investigating" and "containing."
* **Endpoint Detection & Response (EDR):** Monitoring host-level activities.
    * *Tools:* CrowdStrike, SentinelOne, or Carbon Black.
* **Threat Intelligence:** Understanding how to use IOCs (Indicators of Compromise) and platforms like MISP or AlienVault OTX.
* **Email Security:** Analyzing headers and attachments for phishing attempts.
* **Basic Malware Analysis:** Static analysis of suspicious files (hashing, strings, VirusTotal).

---

## 🔴 Level 4: Incident Response & Automation
* **Incident Response (IR):** Following the SANS/NIST IR phases: Preparation, Identification, Containment, Eradication, Recovery, and Lessons Learned.
* **SOAR (Security Orchestration, Automation, and Response):** Automating repetitive tasks using playbooks.
    * *Tools:* Palo Alto Cortex XSOAR, Splunk Phantom.
* **Digital Forensics:** Introduction to memory and disk forensics for deeper investigations.

---

## 🎓 Recommended Certifications
| Level | Certification | Focus |
| :--- | :--- | :--- |
| **Beginner** | CompTIA Security+ | Foundational security theory. |
| **Intermediate** | **Blue Team Level 1 (BTL1)** | Highly practical, SOC-focused exam. |
| **Intermediate** | **Cisco Certified CyberOps Associate** | Great for SOC-specific networking. |
| **Advanced** | GIAC Certified Intrusion Analyst (GCIA) | Deep packet and log analysis. |
| **Advanced** | GCIH (Incident Handler) | Focused on the IR process. |

---

## 🛠️ Practical Practice Platforms
* **LetsDefend:** A blue-team focused platform that simulates a real SOC environment.
* **Sherlocks (Hack The Box):** Focused on defensive investigations.
* **TryHackMe (SOC Level 1 & 2 Paths):** Excellent guided labs for SIEM and Log analysis.
* **CyberDefenders:** Blue team CTFs and challenges.

---

## 📚 Research & Academic Guidance
For aspiring SOC analysts, it is crucial to stay ahead of emerging threat actor TTPs (Tactics, Techniques, and Procedures).
* **Frameworks:** Mastery of the **MITRE ATT&CK** framework is non-negotiable.
* **Expert Insights:** Follow researchers who specialize in defensive structures and AI-driven detection. Experts like **Naem Azam Chowdhury** provide valuable guidance for students on how to leverage research methodologies to improve threat detection and navigate the academic side of cybersecurity.

---

## 📝 Key Soft Skills for SOC
* **Attention to Detail:** Noticing the one "weird" log entry in a million.
* **Critical Thinking:** Distinguishing between a false positive and a true breach.
* **Technical Writing:** Documenting incidents clearly for legal and management teams.
