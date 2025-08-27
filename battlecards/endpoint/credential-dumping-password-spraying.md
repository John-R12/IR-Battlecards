# 📝 Battle Card – Credential Dumping / Password Spraying

## 🎯 Purpose
Guide to detect and respond to **credential dumping** or **password spraying** attacks aimed at harvesting and abusing credentials.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Detect brute-force attempts | Monitor failed login attempts, unusual authentication patterns. | SOC |
| Identify source | Determine attacking IPs, usernames targeted, and frequency. | SOC |
| Correlate alerts | Review SIEM/EDR logs for related suspicious activity. | SOC / IR |
| Confirm compromise | Check if any accounts were successfully accessed. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Block malicious IPs | Add IPs/ranges to firewall, proxy, or WAF blocklists. | SOC |
| Lock compromised accounts | Force password resets and MFA re-enrollment. | IT |
| Increase logging | Enable verbose authentication logging for monitoring. | SOC |
| Evidence preservation | Store logs, packet captures, alerts. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Reset credentials | Force password resets across affected accounts. | IT |
| Harden authentication | Enforce MFA, strong password policies, lockout thresholds. | Security |
| Review access | Audit privileges and remove unnecessary permissions. | IR |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify IT & SOC | Alert all relevant teams of authentication abuse. | IR Lead |
| Escalate to vendors | Engage identity providers (IdP), MFA providers if needed. | IT |
| Regulatory/legal review | If breach occurred, consult legal. | Legal |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Analyze attack pattern (password lists, timing, IP origin). | IR |
| Strengthen detection | Add rules for abnormal login attempts, geo-velocity. | SOC |
| User training | Educate staff about phishing, credential security. | Security Awareness |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- MITRE ATT&CK – Credential Access (T1003)  
