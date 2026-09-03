<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,12,20&height=220&section=header&text=Amithesh%20Sequeira&fontSize=52&fontColor=ffffff&animation=fadeIn&desc=Securing%20Networks%20and%20Defending%20Systems&descSize=16&descColor=a0f0ff&descAlignY=78&fontAlignY=55" alt="header" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=00FFFF&center=true&vCenter=true&width=600&lines=Penetration+Tester+%7C+CTF+Runner-Up+%7C+NITK+3rd+Place;Building+federated+threat+intelligence+with+AI;Breaking+things+ethically.+Defending+everything+else.)](https://git.io/typing-svg)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-amithesh.vercel.app-00FF41?style=flat-square&logo=vercel&logoColor=white)](https://amithesh-portfolio.vercel.app/)&ensp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-amithesh--sequeira-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/amithesh-sequeira-01898b321)&ensp;
[![Email](https://img.shields.io/badge/Email-iamamithesh%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:iamamithesh@gmail.com)&ensp;
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Active-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com)&ensp;
![Visitors](https://komarev.com/ghpvc/?username=Ametheshh&style=flat-square&color=00FF41&label=Profile+Views)

</div>

---

## About

B.Tech CS & Cyber Security student at **NMAMIT, Nitte University** (2023–2027 · CGPA 7.88) with hands-on VAPT internship experience and multiple national CTF podium finishes. I sit at the intersection of offensive security and applied ML — currently engineering a privacy-preserving federated learning framework for cross-organization threat intelligence.

> **Currently:** Building `TrustMesh XDR` · Open to internships, research collaborations & CTF teams

---

## Skills

<div align="center">

**Security & Offensive**

[![Kali](https://skillicons.dev/icons?i=kali&theme=dark)](https://kali.org)&nbsp;
[![Linux](https://skillicons.dev/icons?i=linux&theme=dark)](https://kernel.org)&nbsp;
[![Bash](https://skillicons.dev/icons?i=bash&theme=dark)](#)

`Burp Suite` &ensp; `Nmap` &ensp; `Metasploit` &ensp; `Wireshark` &ensp; `OWASP Top 10` &ensp; `CVSS` &ensp; `OSINT` &ensp; `Digital Forensics`

<br/>

**AI / Machine Learning**

[![Python](https://skillicons.dev/icons?i=python&theme=dark)](https://python.org)&nbsp;
[![PyTorch](https://skillicons.dev/icons?i=pytorch&theme=dark)](https://pytorch.org)&nbsp;
[![TensorFlow](https://skillicons.dev/icons?i=tensorflow&theme=dark)](https://tensorflow.org)&nbsp;
[![sklearn](https://skillicons.dev/icons?i=sklearn&theme=dark)](https://scikit-learn.org)

`Federated Learning` &ensp; `SHAP` &ensp; `Isolation Forest` &ensp; `Autoencoders` &ensp; `Differential Privacy`

<br/>

**Development & Infrastructure**

[![Node](https://skillicons.dev/icons?i=nodejs&theme=dark)](https://nodejs.org)&nbsp;
[![React](https://skillicons.dev/icons?i=react&theme=dark)](https://react.dev)&nbsp;
[![PostgreSQL](https://skillicons.dev/icons?i=postgresql&theme=dark)](https://postgresql.org)&nbsp;
[![GCP](https://skillicons.dev/icons?i=gcp&theme=dark)](https://cloud.google.com)&nbsp;
[![Git](https://skillicons.dev/icons?i=git&theme=dark)](https://git-scm.com)&nbsp;
[![Java](https://skillicons.dev/icons?i=java&theme=dark)](#)

`AES-256` &ensp; `JWT` &ensp; `TOTP` &ensp; `Zero Trust` &ensp; `IAM` &ensp; `SIEM` &ensp; `SOC Operations`

</div>

---

## Projects

<details>
<summary>&nbsp;<b>TrustMesh XDR</b> &nbsp;—&nbsp; Federated Learning Threat Detection &nbsp;<code>Major Project · In Progress 2026</code></summary>

<br/>

**Stack:** `Python` `PyTorch` `Flower` `Differential Privacy` `Secure Aggregation` `STIX` `MITRE ATT&CK`

A privacy-preserving Federated Learning framework enabling multiple organizations to collaboratively train threat-detection models **without sharing raw security logs**. Addresses the fundamental tension between collaborative cyber defense and data sovereignty.

**What it does:**
- Organizations train locally on their own logs; only encrypted gradient updates leave the perimeter
- Integrates **Differential Privacy** + **Secure Aggregation** to defend against gradient leakage and membership-inference attacks
- Incident correlation engine fuses local alerts with validated CTI into multi-stage attack episodes
- Evaluated using **Incident Recall@50** for analyst alert prioritization quality

[→ View Repository](https://github.com/Ametheshh/TrustMesh-XDR)

<br/>
</details>

<details>
<summary>&nbsp;<b>Access Sentinel</b> &nbsp;—&nbsp; AI-Powered IAM Anomaly Detection &nbsp;<code>🥉 3rd Place · NITK / Saviynt Challenge</code></summary>

<br/>

**Stack:** `Python` `Scikit-learn` `PyTorch` `SHAP` `Streamlit`

Unsupervised ML ensemble (**Isolation Forest + Autoencoders**) that detects anomalous IAM access patterns in real-time identity logs — built for the NITK Saviynt Industry Challenge and placed 3rd.

**What it does:**
- Achieves **F1-score 0.80+** on anomalous IAM access detection across heterogeneous identity logs
- SHAP explainability surfaces human-readable threat indicators: geographic velocity, off-hours access, temporal deviations
- Produces transparent, analyst-ready alerts — no black-box decisions

[→ View Repository](https://github.com/Ametheshh/Access-Sentinel)

<br/>
</details>

<details>
<summary>&nbsp;<b>Risk-Based MFA</b> &nbsp;—&nbsp; Zero Trust Authentication Engine &nbsp;<code>Nov 2025</code></summary>

<br/>

**Stack:** `Node.js` `Express.js` `PostgreSQL` `AES-256` `JWT` `TOTP`

Zero Trust, risk-adaptive MFA system that dynamically escalates authentication challenges based on real-time behavioral and geolocation risk analysis. No static access decisions.

**What it does:**
- Real-time geolocation + behavioral analysis drives dynamic authentication escalation
- Layered security: `bcrypt` hashing → `AES-256` encryption → `Shamir's Secret Sharing` → `JWT` session management
- TOTP-based second factor triggered only when risk score crosses threshold

[→ View Repository](https://github.com/Ametheshh/Riskmfa)

<br/>
</details>

<details>
<summary>&nbsp;<b>Password Strength Analyser</b> &nbsp;—&nbsp; Entropy-Driven Credential Intelligence</summary>

<br/>

**Stack:** `Python` `Shannon Entropy` `Regex` `CLI`

Goes beyond character-class rules — applies information entropy, dictionary attack simulation, and pattern recognition (keyboard walks, leet-speak obfuscation, repeated sequences) to deliver precise credential strength scores with actionable remediation.

[→ View Repository](https://github.com/Ametheshh/Password-Strength-Checker)

<br/>
</details>

---

## Experience & CTF Record

| Date | Event | Role / Outcome |
|------|-------|----------------|
| **Jun – Aug 2025** | **EyeQ Dot Net Pvt. Ltd** | Cyber Security Analyst Intern · VAPT on live production systems · documented critical vulnerabilities with CVSS ratings · Burp Suite, Kali, Wireshark, Nmap · HTML Injection, Clickjacking, Broken Link Hijacking |
| **Nov 2025** | **CyberSiege National CTF** | 🥈 **2nd Place / 41 teams** · Cryptography, Web Exploitation, OSINT, Digital Forensics |
| **Feb 2026** | **NITK / Saviynt Industry Challenge** | 🥉 **3rd Place** · Access Sentinel ML IAM anomaly detection PoC |
| **Oct 2025** | **CySecK Bootcamp CTF · NITK** | 🏅 **Top 10 / 300+ participants** · Centre of Excellence for Cybersecurity, Karnataka |

---

## Certifications

<div align="center">

[![NPTEL Elite](https://img.shields.io/badge/NPTEL_ELITE_%F0%9F%8F%85-Internet_Crimes_%26_CyberSec_%C2%B7_100%25_TOP_1%25-FFD700?style=for-the-badge&labelColor=1a1a2e)](https://nptel.ac.in)

[![NPTEL](https://img.shields.io/badge/NPTEL-Systems_%26_Usable_Security-c0392b?style=flat-square&logo=coursera&logoColor=white)](https://nptel.ac.in)&ensp;
[![NPTEL](https://img.shields.io/badge/NPTEL-Cryptography_%26_Network_Security-c0392b?style=flat-square&logo=coursera&logoColor=white)](https://nptel.ac.in)&ensp;
[![Deloitte](https://img.shields.io/badge/Deloitte-Cyber_Job_Simulation-86BC25?style=flat-square&logo=deloitte&logoColor=white)](https://forage.com)&ensp;
[![Mastercard](https://img.shields.io/badge/Mastercard-Cybersecurity_Simulation-EB001B?style=flat-square&logo=mastercard&logoColor=white)](https://forage.com)

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Cyber_Security_101_(45h_53min)-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com)&ensp;
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Pre_Security_Learning_Path-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com)&ensp;
[![Cisco](https://img.shields.io/badge/Cisco-Introduction_to_Cybersecurity-1BA0D7?style=flat-square&logo=cisco&logoColor=white)](https://netacad.com)

</div>

<details>
<summary>&nbsp;<b>🖼️ Certificate Gallery</b> &nbsp;[click to expand]</summary>

<br/>

<!--
  Upload your certificate images to  assets/certs/  in this repo.
  Suggested filenames are used below. Rename yours to match or update the paths.
-->

<div align="center">

**NPTEL Elite — 100% · TOP 1%**

<table><tr>
<td align="center" width="50%">
<img src="./assets/certs/nptel-internet-crimes.png" width="100%" alt="NPTEL Elite Internet Crimes & Cyber Security 100%"/>
<sub><b>Internet Crimes & Cyber Security</b><br/>IIT Madras · Feb–Apr 2026 · Score: 100%</sub>
</td>
<td align="center" width="50%">
<img src="./assets/certs/nptel-systems-security.png" width="100%" alt="NPTEL Systems and Usable Security"/>
<sub><b>Systems & Usable Security</b><br/>IIT Indore · Jan–Feb 2025</sub>
</td>
</tr></table>

<br/>

**Industry Simulations**

<table><tr>
<td align="center" width="50%">
<img src="./assets/certs/deloitte.png" width="100%" alt="Deloitte Cyber Job Simulation"/>
<sub><b>Deloitte — Cyber Job Simulation</b><br/>Jan 2026 · via Forage</sub>
</td>
<td align="center" width="50%">
<img src="./assets/certs/mastercard.png" width="100%" alt="Mastercard Cybersecurity Simulation"/>
<sub><b>Mastercard — Cybersecurity Simulation</b><br/>Jan 2026 · via Forage</sub>
</td>
</tr></table>

<br/>

**Platform Certifications**

<table><tr>
<td align="center" width="33%">
<img src="./assets/certs/thm-cybersec101.png" width="100%" alt="TryHackMe Cyber Security 101"/>
<sub><b>TryHackMe</b><br/>Cyber Security 101 · 45h 53min</sub>
</td>
<td align="center" width="33%">
<img src="./assets/certs/thm-presecurity.png" width="100%" alt="TryHackMe Pre Security"/>
<sub><b>TryHackMe</b><br/>Pre Security Learning Path</sub>
</td>
<td align="center" width="33%">
<img src="./assets/certs/cisco-intro-cybersec.png" width="100%" alt="Cisco Intro to Cybersecurity"/>
<sub><b>Cisco Networking Academy</b><br/>Intro to Cybersecurity · Oct 2025</sub>
</td>
</tr></table>

<br/>

**Internship**

<table><tr>
<td align="center" width="65%">
<img src="./assets/certs/eyeq-internship.png" width="100%" alt="EyeQ Dot Net Internship"/>
<sub><b>EyeQ Dot Net Pvt. Ltd</b><br/>Cybersecurity Analyst Intern · Jun–Aug 2025</sub>
</td>
</tr></table>

</div>

<br/>
</details>

---

## Education

| Degree | Institution | Year | Score |
|--------|-------------|------|-------|
| **B.Tech CS & Cyber Security** | NMAMIT, Nitte University | 2023 – 2027 | CGPA **7.88 / 10** |
| Pre-University (PCMC) | St. Aloysius PU College, Mangaluru | 2021 – 2023 | **83.83%** |
| SSLC | St. Aloysius High School, Mangaluru | 2019 – 2021 | **84.48%** |

---

## Leadership

- **Team Lead, Employment Readiness Program — NMAMIT** *(2024–2026)*  
  Selected 2 consecutive years to lead mock interviews, resume workshops, and technical feedback sessions — impacting **100+ students annually**

- **Class Representative — NMAMIT** *(2023–2027)*  
  Re-elected for a **3rd consecutive term**; liaison between faculty and 75 students across academic scheduling and departmental representation

- **University Basketball — South Zone Inter-University Tournament** *(2024–2025)*  
  Represented NMAMIT at the South Zone Inter-University Basketball Tournament

---

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-00FF41?style=for-the-badge&logo=vercel&logoColor=white)](https://amithesh-portfolio.vercel.app/)&ensp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/amithesh-sequeira-01898b321)&ensp;
[![Email](https://img.shields.io/badge/Email-Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iamamithesh@gmail.com)

<br/>

*"Securing the perimeter. Training the models. Defending the network."*

<br/>

![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,12,20&height=120&section=footer&fontColor=ffffff&animation=fadeIn)

</div>
