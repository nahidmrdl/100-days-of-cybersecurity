# 🚀 Cybersecurity on the Offense (Day 02 – Part 1)

## 🕵️ Attacker vs Threat Actor
An **attacker (cyberattacker)** is someone who tries to bypass system or network security without authorization for malicious purposes.  
A **threat actor (malicious actor)** is an entity that poses a cybersecurity threat. While the terms attacker and threat actor have similar meanings, *threat actor* emphasizes the **potential threat** the entity poses.

---

## 👥 Threat Actor Groups
Five main groups of threat actors:

- **🧑‍💻 Script Kiddie** → A novice hacker who uses programs or tools without understanding what’s happening behind the scenes.  
- **✊ Hacktivist** → Combines *hacker* and *activist*. Uses hacking for political or economic change.  
- **💰 Criminal Gang** → Organized national/international groups aiming to make money.  
- **🌍 Nation-State Hacker** → Highly trained experts providing strategic advantage to their countries.  
- **🏢 Malicious Insider** → Authorized user misusing access to harm the organization.  

---

## 🔎 Penetration Testing & Ethical Hackers
- **Penetration testing** → Simulates real hacking techniques to discover vulnerabilities.  
- **Ethical hackers** (offensive security researchers) → Use hacker mindset but for defensive purposes, helping organizations strengthen security.  

---

## 💣 Types of Cyberattacks
- **🚫 DoS Attack** → Complete or partial system outage.  
- **🌐 DDoS Attack** → Multiple sources overwhelm a target. Uses:  
  - **Bot (Zombie)** = infected device controlled remotely.  
  - **Botnet** = network of hundreds/thousands of bots flooding the target simultaneously.  
- **📧 Phishing** → Fake/trusted-looking messages tricking users into actions.  
- **🎯 Spear Phishing** → Targeted phishing (specific person/group/org).  
- **🦠 Malware** → Malicious software harming systems/data without consent.  
- **🔗 Man-in-the-Middle (MitM)** → Attacker intercepts client-server communication.  
- **🌍 DNS Attack** → Manipulates or disrupts domain resolution (e.g., hijacking, cache poisoning). Redirects users or hinders access.  
- **💉 SQL Injection** → Malicious SQL code injected into queries, often via web inputs. Can even delete entire databases.  

---

### 📘 Notes
- **DNS (Domain Name System)** → Core internet protocol mapping domain names to IPs.  
  Example: typing **bmw.com** → DNS resolves it to BMW’s server IP. Domain names are easier to remember than IP addresses.  

- **SQL (Structured Query Language)** → Programming language for accessing, managing, and querying databases.  

---

## 🤖 AI in Cyberattacks
Attackers leverage AI in multiple ways:  

- **⚡ Task Automation** → Automates attacks (e.g., massive phishing campaigns).  
- **🕵️ Detection Evasion** → ML-based malware adapts to avoid antivirus detection.  
- **🎯 Target Identification** → Algorithms scan data to find vulnerable/high-value targets.  
- **🎭 Social Engineering with AI** → Deepfakes (audio/video) used for more convincing manipulation.  

---

## 🌐 Threat Maps (Activities)

### 🟢 Kaspersky Cyberthreat Real-Time Map  
[cybermap.kaspersky.com](https://cybermap.kaspersky.com)  
- Navigate world map → see attack data by country.  
- Acronyms (e.g., **BAD** = Botnet Activity Detection).  
- *(Image will be added to Day02.md)*  

### 🔴 Fortinet Threat Map  
[threatmap.fortiguard.com](https://threatmap.fortiguard.com)  
- Shows scrolling live attack details (type, severity, location).  
- Includes legend of attack types + info about Fortinet.  

### 🔵 Bitdefender Cyberthreat Real-Time Map  
[threatmap.bitdefender.com](https://threatmap.bitdefender.com)  
- Displays live attacks (spam, threats, infections).  
- Tables show attack time, description, origin country, and target.  

---

## 🧩 Structure of a Cyberattack

### Lockheed Martin Cyber Kill Chain®
1. **Reconnaissance** → Gather info about target.  
2. **Weaponization** → Create malware to exploit vulnerability.  
3. **Delivery** → Send malware (email, website download, USB).  
4. **Exploitation** → Target executes malware → exploit runs.  
5. **Installation** → Malware gains persistence (backdoors, RATs, new accounts).  
6. **Command & Control (C2)** → Attacker communicates with compromised system.  
7. **Actions on Objectives** → Steal/modify/destroy data.  

![Kill Chain](assets/images/killchain.png)

---

### MITRE ATT&CK Matrix
- Framework of attacker **tactics, techniques, and procedures (TTPs)**.  
- **ATT&CK = Adversarial Tactics, Techniques & Common Knowledge** (pronounced “attack”).  
- Open source & freely available.  

![MITRE ATT&CK Matrix](assets/images/mitrematrix.jpg)


---

## 🎭 Social Engineering
**Definition** → Deception to manipulate individuals into revealing confidential or personal information.  

### Tactics
- **👥 Human Nature & Social Norms** → Exploiting trust/helpfulness.  
- **📋 Trust & Authority** → Impersonating officials/authority figures.  
- **💔 Emotional Manipulation** → Using fear, urgency, curiosity, excitement.  
- **📉 Lack of Awareness** → Targeting people unfamiliar with threats.  

📝 *Note: Tailgating → entering secure area by closely following an authorized person.*  
