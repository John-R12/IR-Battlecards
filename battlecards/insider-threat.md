# 📝 Battle Card – Insider Threat

## 🎯 Purpose
Concise response guide for **Insider Threat** incidents.  
Aligned with NIST SP 800-61r2 phases.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Identify suspicious activity | Look for abnormal access, privilege misuse, or data exfiltration. | SOC |
| Correlate events | Cross-check logs, DLP alerts, HR reports. | SOC / HR |
| Assess intent | Determine if the action was malicious, negligent, or accidental. | IR / HR |
| Confirm incident | Gather evidence (logs, emails, forensics). | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Restrict access | Limit or revoke user’s accounts, VPN, physical access. | IT / HR |
| Isolate systems | Secure impacted endpoints or accounts. | IT |
| Preserve evidence | Save chat logs, emails, HR reports, and system logs. | IR / Legal |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Remove malicious access | Disable accounts, credentials, and tokens. | IT |
| Recover affected systems | Restore from clean backups if tampering occurred. | IT |
| Apply preventive controls | Implement stricter monitoring, least privilege. | Security |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify management | Escalate to HR, legal, and executive leadership. | IR Lead |
| Engage HR/legal | Handle according to employment laws and policies. | HR / Legal |
| External escalation | Law enforcement if applicable. | Legal |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Conduct review with HR, Legal, Security. | IR Lead |
| Policy updates | Update insider threat detection & monitoring controls. | Security |
| Awareness training | Educate staff on acceptable use and security policies. | HR / Security |

---

## 📚 References
- NIST SP 800-61r2 – *Computer Security Incident Handling Guide*  
- NIST SP 800-53 – Insider Threat Controls  
