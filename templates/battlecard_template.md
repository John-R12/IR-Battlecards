# 📝 Battle Card – [Incident Type]

## 🎯 Purpose
Concise response guide for **[Incident Type]** incidents.  
Aligned with NIST SP 800-61r2 phases.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Identify indicators | Collect IoCs (logs, alerts, user reports, EDR, SIEM). | SOC |
| Assess scope | Determine affected users, systems, data. | SOC/IR |
| Classify severity | Rate incident criticality (Low/Med/High). | IR Lead |
| Confirm incident | Validate with threat intel / forensic evidence. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Isolate systems | Disconnect compromised hosts from network. | IT / IR |
| Block IoCs | Add IoCs to firewall, EDR, SIEM, proxy, mail gateway. | SOC |
| Preserve evidence | Ensure forensic images, logs, and artifacts are saved. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Remove malicious artifacts | Delete malware, phishing accounts, persistence mechanisms. | IR |
| Patch & harden | Apply patches, revoke credentials, update configs. | IT |
| Restore operations | Rebuild systems, validate backups, monitor closely. | IT / IR |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Internal notification | Inform IR lead, management, and legal. | IR Lead |
| External partners | Notify affected third parties, MSSP, or vendors. | IR Lead |
| Regulatory requirements | If applicable, notify regulators or authorities. | Legal / Compliance |
| Public relations | Prepare communication for customers or media if needed. | Comms / PR |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Conduct post-mortem / after-action review. | IR Lead |
| Update playbooks | Improve detection, logging, and response. | SOC / IR |
| Awareness & training | Share findings internally, update awareness training. | HR / Security Awareness |

---

## 📚 References
- NIST SP 800-61r2 – *Computer Security Incident Handling Guide*  
- Organization-specific IR policies and escalation matrix  
