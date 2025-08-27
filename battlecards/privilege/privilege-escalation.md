# 📝 Battle Card – Privilege Escalation

## 🎯 Purpose
Guide to detect and respond to **unauthorized escalation of privileges** on endpoints, servers, or applications.

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Monitor logs | Check for abnormal use of admin privileges or sudo commands. | SOC / IR |
| Detect unusual processes | Look for exploits or tools used for privilege escalation. | SOC |
| Identify affected accounts | Determine which accounts were escalated and accessed. | IR |
| Correlate activity | Cross-check with network, system, and security alerts. | IR |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Disable compromised accounts | Lock affected accounts immediately. | IT |
| Isolate affected hosts | Disconnect from network if necessary. | IT |
| Preserve evidence | Collect logs, memory dumps, and relevant system snapshots. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Remove unauthorized access | Revoke escalated privileges and accounts. | IT / Security |
| Patch vulnerabilities | Apply fixes to software or configuration exploited. | IT |
| Validate remediation | Recheck systems for residual escalation attempts. | SOC / IR |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify management | Alert IT leadership and security teams. | IR Lead |
| Legal / Compliance | Evaluate regulatory impact if sensitive data accessed. | Legal |
| Security coordination | Inform SOC and endpoint teams for monitoring. | Security |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Analyze escalation path and vulnerabilities exploited. | IR / Security |
| Strengthen controls | Enforce least privilege, MFA, and endpoint hardening. | Security |
| Awareness & training | Educate admins and staff on secure privilege use. | Security Awareness |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- MITRE ATT&CK – Privilege Escalation (T1068)  
