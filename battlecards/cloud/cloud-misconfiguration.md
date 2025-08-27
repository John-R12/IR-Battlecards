# 📝 Battle Card – Cloud Misconfiguration

## 🎯 Purpose
Guide to handle **cloud resource misconfigurations** (e.g., open storage buckets, exposed services, overly permissive IAM policies).

---

## 🚨 Detection & Analysis
| Action | Description | Owner |
|--------|-------------|-------|
| Identify exposure | Scan for open ports, public buckets, security group misconfigurations. | SOC / Cloud Team |
| Validate severity | Determine if sensitive data or services are exposed. | IR |
| Check access logs | Identify if data has been accessed or exfiltrated. | Cloud Team |
| Confirm misconfiguration | Cross-verify with security baselines and IaC templates. | Security |

---

## 🛑 Containment
| Action | Description | Owner |
|--------|-------------|-------|
| Restrict access | Apply least privilege, tighten security groups, and firewall rules. | Cloud Team |
| Disable exposed endpoints | Shut down or isolate misconfigured instances. | IT |
| Rotate credentials | Revoke and re-issue exposed API keys, tokens. | IT |
| Preserve evidence | Save configuration snapshots, logs, and cloud audit trails. | IR |

---

## 🧹 Eradication & Recovery
| Action | Description | Owner |
|--------|-------------|-------|
| Fix misconfigurations | Apply security best practices and hardening templates. | Cloud Team |
| Validate remediation | Perform scans and configuration reviews. | SOC |
| Automate policies | Implement IaC security guardrails and compliance tools. | DevOps |

---

## 📋 Communication & Escalation
| Action | Description | Owner |
|--------|-------------|-------|
| Notify stakeholders | Inform security and business teams. | IR Lead |
| Vendor escalation | If using third-party cloud service, contact vendor. | IT |
| Legal/regulatory | If data was accessed, involve legal/compliance. | Legal |

---

## 🔄 Post-Incident
| Action | Description | Owner |
|--------|-------------|-------|
| Lessons learned | Review how misconfiguration occurred. | IR |
| Policy enforcement | Strengthen IaC pipelines and compliance scanning. | Security |
| Training | Educate cloud engineers on secure configuration. | DevOps/Security |

---

## 📚 References
- NIST SP 800-61r2 – *Incident Handling*  
- NIST SP 800-210 – *Cloud Security*  
