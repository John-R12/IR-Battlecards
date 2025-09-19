# 📝 Battle Card – Insider Data Exfiltration

## 🎯 Purpose
Guide to detect and respond to **insiders exfiltrating sensitive data** (malicious or negligent).

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Monitor DLP systems | Detect unusual file transfers, USB usage, or uploads. | SOC |
| Review logs | Check access logs for sensitive file downloads. | IR |
| Identify insider activity | Determine if actions were intentional or accidental. | HR / IR |
| Confirm data scope | Identify what data was accessed and potentially exfiltrated. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Restrict account access | Disable or limit insider’s accounts immediately. | IT / HR |
| Stop data transfer | Block ongoing uploads or external communications. | SOC |
| Preserve evidence | Secure logs, DLP alerts, and communication records. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Remove unauthorized access | Revoke insider’s credentials and remote access. | IT |
| Secure sensitive data | Re-encrypt, move, or restrict sensitive assets. | Security |
| Forensic analysis | Identify full timeline of insider activities. | IR |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify management | Inform HR, Legal, and Security teams. | IR Lead |
| Legal proceedings | Engage legal counsel for regulatory and contractual obligations. | Legal / HR |
| Law enforcement | Contact authorities if criminal intent is confirmed. | Legal |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Review how insider bypassed controls. | IR |
| Strengthen monitoring | Enhance DLP, logging, and behavioral analytics. | Security |
| Awareness & training | Reinforce acceptable use and insider threat policies. | Security Awareness |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- NIST SP 800-171 – *Protecting Controlled Unclassified Information*  
