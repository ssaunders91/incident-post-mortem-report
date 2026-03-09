# 🛡️ Incident Post-Mortem Report: Taylor & Sons Construction Ltd

**Project Overview:** This document serves as a professional incident post-mortem report, produced as part of the NCFE Level 3 Cybersecurity Practices curriculum to demonstrate incident response analysis.

---

## 📝 Executive Summary
In March 2024, the family-owned construction company **Taylor & Sons Construction Ltd** suffered a cyber theft totalling **£550,000**. The breach was caused by a phishing attack that led to the installation of keylogging malware on company systems. While the bank recovered **£200,000**, the company sustained an unrecoverable loss of **£350,000**, exposing critical security weaknesses.

---

## 📊 Incident Profile

* **Date of Report:** 24th March 2024 
* **Incident Period:** 4 March 2024 – 10 March 2024 
* **Total Amount Stolen:** £550,000 
* **Funds Recovered:** £200,000 
* **Net Financial Loss:** £350,000 

---

## ⏱️ Timeline of Events

### The Lead-Up

* Employees accessed online banking using individual IDs and passwords.
* Transactions over £1,000 required answering two security challenge questions.
* **Security Gaps:** Multi-factor authentication (MFA) was not implemented, and the organisation lacked formal cybersecurity practices or staff training.



### The Breach & Detection

| Date | Time | Event |
| --- | --- | --- |
| **4 Mar 2024** | 09:15 AM | An employee opened a phishing email appearing to be from a materials supplier.
| **4 Mar 2024** | 09:17 AM | A malicious PDF attachment was opened, installing keylogging malware without detection.
| **4–8 Mar 2024** | - | Malware captured sensitive banking login credentials to access online accounts.
| **5–9 Mar 2024** | - | Attackers used stolen info to execute 6 unauthorised transactions totalling £550,000.
| **10 Mar 2024** | 11:30 AM | <br>**Detection:** The director received a bank alert regarding a suspicious £10,000 transaction.
| **10 Mar 2024** | 12:15 PM | Internal investigation revealed five additional unauthorised transactions.

 ---

## 🔍 Root Cause Identification

* **Phishing Success:** An employee opened a malicious email because staff had received no training on recognising threats.
* **Endpoint Failure:** Malware installation succeeded because there was no effective endpoint protection in place.
* **Authentication Weakness:** The absence of MFA allowed attackers to use stolen credentials to access banking services.
* **Lack of Monitoring:** No automated systems were in place to detect unusual activity, delaying the response and extending attacker access.

---

## 🛠️ Response & Recovery

* **10 March:** The bank was promptly contacted, and affected accounts were frozen.
* **11 March:** An internal investigation into the breach was initiated.
* **13 March:** All company devices were scanned, and compromised endpoints were isolated.
* **14 March:** Compromised bank accounts were closed and secure replacements were established.
* **22 March:** Legal action was launched in an effort to recover the remaining losses.

---

## 💡 Lessons Learnt

* Passwords and challenge questions alone are insufficient for protecting financial systems.
* Cybersecurity must be actively managed regardless of the size of the organisation.
* Fast threat detection and a structured response framework are key to reducing damage.
* Continuous monitoring and regular staff training are crucial preventative measures.

---

## 🚀 Recurrence Prevention Plan

* **By 1 April 2024:** Implement MFA for all internal systems and online banking.
* **By 8 April 2024:** Conduct phishing and cybersecurity awareness training for all staff.
* **By 15 April 2024:** Install advanced endpoint security tools, including keylogger detection.
* **By 22 April 2024:** Establish formal cybersecurity policies and a structured Incident Response Plan.
* **By 30 April 2024:** Set up real-time transaction alerts and anomaly detection for banking activity.

---

## 📢 Strategic Recommendations

* **Multi-Factor Authentication:** Apply MFA across all platforms to provide protection beyond passwords.
* **Formal Policies:** Develop protocols for password management, data protection, and incident response.
* **Regular Training:** Educate staff to recognise phishing and social engineering tactics.
* **Endpoint Protection:** Deploy robust anti-malware and anti-keylogging software.
* **Real-Time Monitoring:** Use automated tools to track financial activity and flag suspicious behaviour immediately.



This incident serves as a stark reminder that cybersecurity is a fundamental concern that must be embedded across all levels of an organisation.

---

**Would you like me to help you format a Profile README to showcase this report and your other projects on your main GitHub page?** 🚀
