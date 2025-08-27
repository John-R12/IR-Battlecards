# 📝 Battle Card – Supply Chain Attack

## 🎯 Purpose
Guide to detect and respond to attacks via **third-party software, services, or vendors**.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Identify unusual activity | Monitor network traffic, vendor services, and update channels. | SOC |
| Correlate alerts | Review logs, EDR alerts, and suspicious file changes. | SOC / IR |
| Verify vendor integrity | Confirm authenticity of software updates, patches, or services. | IR / Procurement |
| Determine impact | Identify affected systems, data, and processes. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Isolate affected systems | Disconnect compromised endpoints or servers. | IT / IR |
| Suspend vendor access | Temporarily revoke access to impacted systems. | IT / Vendor Management |
| Preserve evidence | Collect logs, update packages, and forensic snapshots. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Remove malicious software | Uninstall compromised components. | IT |
| Restore systems | Rebuild or restore from known good backups. | IT |
| Validate vendor updates | Verify future updates are signed and safe. | Security / Vendor Management |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify management | Alert IT leadership and risk teams. | IR Lead |
| Engage vendors | Coordinate with affected third parties. | Vendor Management |
| Regulatory/legal | Notify authorities if sensitive data was exposed. | Legal |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Review attack vector and vendor risk assessment. | IR Lead |
| Strengthen controls | Improve vendor onboarding, patch verification, monitoring. | Security / Procurement |
| Awareness & training | Educate staff on supply chain risks. | Security Awareness |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- NIST SP 800-161 – *Supply Chain Risk Management*  
