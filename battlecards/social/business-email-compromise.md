# 📝 Battle Card – Business Email Compromise (BEC)

## 🎯 Purpose
Guide to detect and respond to **fraudulent email activity**, such as CEO fraud, invoice scams, or phishing targeting financial transactions.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Identify suspicious emails | Review reported emails for spoofing, unusual requests, or anomalies. | SOC / IR |
| Verify sender identity | Confirm authenticity with the sender or third-party services. | IR / IT |
| Analyze email headers & links | Detect redirection, spoofed domains, and malicious attachments. | SOC |
| Determine scope | Identify affected recipients, systems, and transactions. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Block malicious accounts | Suspend compromised mailboxes or accounts. | IT |
| Isolate affected systems | Disconnect endpoints if malware detected. | IT |
| Quarantine emails | Remove suspicious emails from mail servers. | SOC |
| Preserve evidence | Archive email headers, logs, and attachments. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Reset credentials | Force password resets for affected accounts. | IT |
| Harden email security | Enforce MFA, DMARC, SPF, DKIM, and anti-phishing tools. | Security |
| Validate systems | Scan endpoints for malware or compromise. | SOC / IT |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify management | Alert finance, IT, and security leadership. | IR Lead |
| Legal & compliance | Involve legal teams if financial loss or regulatory impact. | Legal |
| Vendor/bank coordination | Contact banks or payment processors if fraudulent transfers occurred. | Finance / IR |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Document the attack vector, gaps, and mitigation steps. | IR / Security |
| Awareness & training | Educate employees on BEC and social engineering risks. | Security Awareness |
| Strengthen policies | Improve email security rules and transaction verification procedures. | Security / Finance |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- FBI – Business Email Compromise Alerts  
